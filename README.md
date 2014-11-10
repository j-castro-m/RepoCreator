RepoCreator
===========

Shell Script to place al /usr/bin to create remote git projects.

Instructions:
	- Insert the values of "INITIAL_ROOT","REPOSERVER" AND "REPOUSER"
	- chmod +x RepoCreator.sh
	- sudo cp RepoCreator.sh /usr/bin
	- (Optional) Add your ssh key to "authorized_keys" in the server
	- you can launch the creator with the command:
	      $ ssh username@reposerver RepoCreator.sh
	      $ ssh username@reposerver RepoCreator.sh --no-verbose