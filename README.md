# git-and-github
<h1>LEARNING GIT AND GITHUB </h1>
<br>
git is the free and open source distributed version control system thats respnsible for everything GitHub
related that happen locally on your computer.
this Chat Sheet feature that most important and commonly use Git Commands for easy refrence.

<br>
<br>
<hr>
<h2>GIT</h2>
<p> version control system is tool that help to track code  </P>
<br>
 - popular 
 <br>
 - free and open source 
 <br>
 - fast and scalable
 <br>
 - track the histiry 
 <br>
 - collabration 
 <br>
 <br>
 <hr>


 <h2> GITHUb</h2>
 <p> website that allow devloper to store and manage thair code using Git  </p>

 <br>
 <hr>

 <h2>SET UP</h2>
 Configuring using information used across all local repositories
 <br>
 <h4> git config --global user.name "[firstname lastname]"</h4>
 set a name that is identifiable for credit when review version history.
 <br>
  <h4> git config --global user.email "[valid -email]"</h4>
 set an email address that will be associate with each history maker .
 <br>
 <h4> git config --global color.ui auto"</h4>
 set automatic command line coloring for git for easy reviewing 
 <br>
 <br>

 <br>

 <h2> SETUP AND INIT</h2>
 Configuring user information initializing and cloning repositires
 <br>
 <h4> git init  </h4>
 <p> initialize an exising direciry as a git repositry</p>
  <h4> git clon [url]  </h4>
 <p> reterive an entire repository from a hosted location via URL</p>
 <br>

 <hr>
 <h2> STAGE AND SNAPSHOT</h2>
 <P> worling with snapshot and the git staging area </p>

 <h4> git status </h4>
 <p> show modified fiels in working dirctory staged your next commit. </p>

  <h4> git add [file] </h4>
 <p> add a file it looks to your next commit(stage) </p>

  <h4> git resert [file] </h4>
 <p> unstage a file while returning the change in wroking directory. </p>

  <h4> git diff </h4>
 <p> diff of what is changed bot not staged </p>

 <h4> git diff --staged </h4>
 <p> diff of what is stage bit not yet committed </p>

  <h4> git commit -m "[descriptive message]"</h4>
 <p> show modified fiels in working dirctory staged your next commit snapshot. </p>

 <br>
 <hr>
 <h2> BRANCH AND MERGE </H2>
 <P>  isolating work in branches changing context and integrating changes </P>

<h4> git branch </h4>
<p> list your branches a* will appear next to the current active branch </p>
<h4> git branch [branch-name] </h4>
<p> create a new branch at the current commit</p>
<h4> git cheakout  </h4>
<p> switch your another branch and check it out into your working directory</p>
<h4> git merge [branch] </h4>
<p> merge the spacific branch history into the current one </p>
<h4> git log </h4>
<p> show all commit in the current history </p>

<br>
<hr>
<h2> INSPECT AND COMPARE </h2>
<P> Examining log diff and objects information </P>

<h4> git log </h4>
<p> show the commit history for currently active branch.  </p>

<h4> git log  brancheB.. branchA </h4>
<p> show the commit and branchA that are nor in branchB  </p>

<h4> git log --follow  [file]</h4>
<p>  show the diff of what is in branchA that is not in brachB</p>

<h4> git show [SHA]</h4>
<p>  show any object in git in human relable formate</p>

<br>
<hr>
<h2> TRACKING PATH CHANGES </h2>
<P> versioning file removeand path changes </P>

<h4> git rm [file] </h4>
<p> delete the file from project and stage the removal of commit</p>

<h4> git mv [existing -path ] [new - path] </h4>
<p> change an existing path and stage the move</p>

<h4> git log --stat -m </h4>
<p> show all commit logs with indication of any paths that moved</p>

<bt>
<hr>
<h2> SHARE AND UPDATE</H2>
<P> retrieving update from another repository and updating local repos </P>

<h4> git remote add [alias ] [ url] </h4>
<p> add git URL as alias </p>

<h4> git fetch [alias ] </h4>
<p> fetch down the all the branches from that git remote </p>

<h4> git merge [alias ] /[branch]</h4>
<p> merge the remote branch into your current branch to bring it up to date </p>
<h4> git push [alias ] /[branch]</h4>
<p> transmit local branch commit to the remote repository branch </p>

<h4> git pull </h4>
<p> fetach and merge any commit from the tracking remote branch  </p>

<br>
<hr>
<h2> REWRITE HISTPRY</h2>
<P> Rewrite branches updating commits and clearing history </P>
<h4> git rebase [branch ] </h4>
<p> apply any commits of current branch ahead of specified one  </p>

<h4> git rebase --herd [commit ] </h4>
<p> clear staging area , rewrite working tree from specified commit  </p>

<br>
<h2> temporary commits</h2>
<p> temporarily store modified , tracke  files in order to change brances </p>

<h4> git stash  </h4>
<p> save modified and staged changes  </p>

<h4> git stash  list</h4>
<p> list stack-order of stashed file changes </p>

<h4> git stash pop </h4>
<p>  write working from top of stash stack </p>

<h4> git stash drop </h4>
<p> discard the changes from top of stash stack </p>
















