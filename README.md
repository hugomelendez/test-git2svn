# test-git2svn
1. empezamos leyendo http://stackoverflow.com/questions/661018/pushing-an-existing-git-repository-to-svn
<<<<<<< HEAD
3. cd ~/workspace
4. git clone https://github.com/hugomelendez/test-git2svn.git
5. svnadmin create reposvn-test-git2svn
6. svn checkout file:///home/hmelendez/workspace/reposvn-test-git2svn/ svn-working-copy
7. cd test-git2svn/
8. svn mkdir --parents file:///home/hmelendez/workspace/reposvn-test-git2svn/trunk -m 'importing git repo'
9. git svn init file:///home/hmelendez/workspace/reposvn-test-git2svn/ -s
=======
2. cd ~/workspace
3. git clone https://github.com/hugomelendez/test-git2svn.git
4. svnadmin create reposvn-test-git2svn
5. svn checkout file:///home/hmelendez/workspace/reposvn-test-git2svn/ svn-working-copy
6. cd test-git2svn/
7. svn mkdir --parents file:///home/hmelendez/workspace/reposvn-test-git2svn/trunk -m 'importing git repo'
8. git svn init file:///home/hmelendez/workspace/reposvn-test-git2svn/ -s
>>>>>>> 72c061e114f5c208692c762307ef634de7e32276
