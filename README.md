# git-study
SVN 
export source R1 ~ RN 
svn_source_export.sh


GIT

# Common commit message format
#
[PROJECT][CATEGORY][ITEM][NO] subject
#[DESCRIPTION]

# --------------------
# [PROJECT] Type can be 
# --------------------
# [CATEGORY] Type can be 
# --------------------
# [ITEM] Type can be 
# --------------------
# [NO] Issue No. 
# --------------------
# "SUBJECT" can be start 
# < Using a Maximum Of 50 Characters >
#
#    add      (add files)
#    feat     (new feature)
#    fix      (bug fix )
#    adjust   (modify value for optimization)
#    remove   (remove feature)
#    refactor (refactoring production code)
#    docs     (changes to documentation)
#    style    (formatting, missing semi colons, etc; no code change)
#    test     (adding or refactoring tests; no production code change)
#    chore    (updating grunt tasks etc; no production code change)
#    revert   (revert mistake commit to previous )
#    patch    (update from qualcomm & code aoura & third party )

# --------------------
# [DESCRIPTION] If need type can be 
# --------------------

# --------------------
# Example
# [COMMON][KERNEL][QUALCOMM][PATCH] feat support for qualcomm USF QMP Phy on SDM450
# --------------------

# --------------------
# Remember to
#    Capitalize the title in the “[]”.
#    Use lower case the subject in the “”.
#    Be careful write commit message,it is listing in the release note with final result.
#    Do not big-bang commit, Use only one commit for single feature.
#    Do not make debug message more then necessary. it's make hard to other developers.
#    Do not use macro like as __DATE__ __TIME__ in code, it's increse OTA update package size.
#    Do not interrupt the build process with an error commit.  
#    If need use the description to explain what and why vs. how.
# --------------------

# --------------------
# cp ./.git_commit_msg.txt ~/.git_commit_msg.txt
# git config --global commit.template ~/.git_commit_msg.txt
# --------------------
