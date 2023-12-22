# Reverting Commits

Sometimes we commit some changes that should not have been there, or we merge some features to the main branch, which breaks some other features, and we would like to "undo" the changes that we made by mistake. 
In such scenarios, having the ability to revert your changes surely comes as a lifesaver.

You can refer to the following documentation to understand how git revert works: https://www.atlassian.com/git/tutorials/undoing-changes/git-revert

# Exercise

After fixing both the rhymes, it's time to add another rhyme to the mix. 
Fortunately, someone has already done the work to add "Humpty Dumpty" in the branch `surya/add-humpty-dumpty`, but it seems like they have messed up the other rhymes in their latest commit. 
Your job is to get the Humpty Dumpty merged to main, while making sure that other rhymes remain the same.
