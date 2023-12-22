# Resolving merge conflicts

Suppose if you are working on `Feature A`, while another person on your team is working on `Feature B`.
Working on `Feature A` affects the following files:

1. `File1.txt`
2. `File2.txt`
3. `File3.txt`

While working on `Feature B` affects the following files:

1. `File3.txt`
2. `File4.txt`
3. `File5.txt`

If the `Feature B` gets merged to the main branch before `Feature A`, while updating your branch with the base branch, you might see something known as merge conflict in `File3.txt`.

In simpler words, merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.

## Tools to resolve merge conflicts

Although you can manually resolve the merge conflicts by using command line and any text editor (see [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)), there are some other tools available which makes resolving merge conflicts easier to resolve:

- [IntelliJ IDEA](https://www.jetbrains.com/help/idea/resolving-conflicts.html)
- [VSCode](https://code.visualstudio.com/docs/sourcecontrol/overview#_merge-conflicts)
- [Vim](http://vimcasts.org/episodes/fugitive-vim-resolving-merge-conflicts-with-vimdiff/)

Based on your preference, you can choose whichever tool you are comfortable with to resolve merge conflicts.

# Exercise

This folder contains 2 rhymes:

1. [Mary Had a Little Lamb](MaryHadALittleLamb.md)
2. [Twinkle Twinkle Little Star](TwinkleTwinkleLittleStar.md)

But it seems like someone has messed up the rhymes!!
Fortunately, there is a branch that has the correct fixes for the rhymes, called `surya/fix-rhymes`.
Your task is to create a PR from that branch, and get it merged to main.

- Estimated time: 1 hour
