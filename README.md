# test-git2svn
1. empezamos leyendo http://stackoverflow.com/questions/661018/pushing-an-existing-git-repository-to-svn
2. cd ~/workspace
3. git clone https://github.com/hugomelendez/test-git2svn.git
4. svnadmin create reposvn-test-git2svn
5. svn checkout file:///home/hmelendez/workspace/reposvn-test-git2svn/ svn-working-copy
6. cd test-git2svn/
7. svn mkdir --parents file:///home/hmelendez/workspace/reposvn-test-git2svn/trunk -m 'importing git repo'
8. git svn init file:///home/hmelendez/workspace/reposvn-test-git2svn/ -s
