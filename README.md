# test1 Repo

This is a test repo.
The idea is to:
	=> (A) create a local respository 
			git init; git add . ; git commit -m "comment" .	
	=> (B) create a remote 'test1' respository on github.com
			create an account on github.com and press the button
			that says: create repository
	=> (C) push the local code to the remote respository
			git branch -M main 
			git remote add origin https://github.com/ketogene/test1.git
			git push -u origin main  (voila! :-)
	=> (D) make local changes and update the remote copy
			use vi to make changes to README.md
			git add README.md
			git commit -m "comment" README.md
			git push -u origin main (sends just the changes ?)
			(you can visually check your github account that the changes made it)
	=> (E) move to a new folder and pull the remote copy
			I created a new folder called: checkoutFromRemoteRepo
			I cd'd into it and then:
			git clone http://github.com/ketogene/test1.git
			So i didn't "checkout" the repo, i cloned it.
			(but voila! Like magic, it worked, how reassuring :-)

The overall aim, of-course, is to become familiar with git/github
And maybe then start to use git/github in my own projects going forward.
(for example, for academic work)

Good progress here.  But how to verify that the SSH keys at both ends are 
actually being used?


