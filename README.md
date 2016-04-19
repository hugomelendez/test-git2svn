# test-git2svn
<<<<<<< 263462308723d831841656e85b3cc9250e5e5523
1. empezamos leyendo http://stackoverflow.com/questions/661018/pushing-an-existing-git-repository-to-svn
3. cd ~/workspace
4. git clone https://github.com/hugomelendez/test-git2svn.git
5. svnadmin create reposvn-test-git2svn
6. svn checkout file:///home/hmelendez/workspace/reposvn-test-git2svn/ svn-working-copy
7. cd test-git2svn/
8. svn mkdir --parents file:///home/hmelendez/workspace/reposvn-test-git2svn/trunk -m 'importing git repo'
9. git svn init file:///home/hmelendez/workspace/reposvn-test-git2svn/ -s

=======
1. empezamos
>>>>>>> Create README.md
