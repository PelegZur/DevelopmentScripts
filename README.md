# Development Scripts

1) <strong>git-pull-dev</strong>: pulls the 'development' branch and merges it into current branch.<br />
&emsp;<em>[Usage: git pull-dev]</em>
2) <strong>wshere</strong>: opens a file in a new WebStorm tab.<br />
&emsp;<em>[Usage: wshere \<file\>]</em>
3) <strong>git-alias-branch</strong>: creates an alias for a branch.<br />
&emsp;<em>[Usage: git alias-branch \<target\> \<alias\>]</em>
4) <strong>git-pull-other</strong>: pulls another branch and merges into current branch.<br />
&emsp;<em>[Usage: git pull-other \<target\> [--no-merge] ]</em>
5) <strong>bgrep</strong>: displays local branches containing a <em>grep</em> pattern and allows choice of checkout.<br />
&emsp;<em>[Usage: bgrep \<pattern\> ]</em>
6) <strong>git-cpbranch</strong>: copies the current checkout out branch name to clipboard.<br />
&emsp;<em>[Usage: git cpbranch ]</em>
7) <strong>git-publish</strong>: git pushes to the remote under a directory prefix and copies the remote branch name to clipboard using <em>git-cpbranch</em>.<br />
&emsp;<em>[Usage: git publish ]</em>
8) <strong>fixdiff</strong>: runs <em>eslint --fix</em> on all files in diff relative to a remote branch.<br />
Defaults to branch <em>master</em> and remote <em>origin</em>.<br />
&emsp;<em>[Usage: fixdiff [--branch <branch>] [--remote <remote>] ]</em>
