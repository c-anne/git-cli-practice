1.Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.
	git status - I just used this to check the status of the repository i'm in therefore letting me know I was in a repository.

    2.Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.
	git commit -m "Hello world"

    
3.Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.
	git status
4.Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.
	git show abc123

5.Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.
	git log -n 3


6.Assuming that you are currently within a Git repository, write the command (or commands) that will check to see if the remote repository contains any new commits.
	git log origin/master