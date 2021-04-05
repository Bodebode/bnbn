# bnbn
mkdir learning-git
(Will create a folder called ‘learning-git’ into the current directory)

cd Desktop (will change directory to desktop)
cd Desktop/learning-git (will change directory into that particular folder)

git init .
(Initialises git in the current directory

Touch to create

git add .
(Add something to the local repo)

To unstage commits on Git, use the “git reset” command with the “–soft” option and specify the commit hash.
$ git reset --soft <commit>
Alternatively, if you want to unstage your last commit, you can the “HEAD” notation in order to revert it easily.
$ git reset --soft HEAD~1


git commit --amend -m “this text is a placeholder for you to amend the comments that specifies what work was done”
(amends & updates the most recent comment made to the last commit)


git log 
(Shows you the logs and each commits with the hash included (copy the hash))


git show 914694e85017c6f2eff362d0dbb42fbe994fe911
(Shows you Author, Date, Time & Project including file names & diffs 


git status 
(Shows you the status)

To update items
  vi <index.js>
Then the code <console.log(“this is what I’ve added”);
Then I, then :wq to get out
Done

Git diff to verify

Don’t forget to re-add the newly changed code to the staged one with git add <index.js>

The git status to confirm its been added

Now to recommit the newly modified code, git commit -m ‘the message describing what you changed’
