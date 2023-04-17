# cp4d_deployment

TODO: 
- wirte bash script that loads the newest config from github
	- structure:
		cloud-pak-deployer
		config
			cpd-config
			cpd-status
		apply_changes_from_git.sh	
		credentials.sh
	- what it should do:
		- pull changes for cpd-config from github
		- run the cloud-pak-deployer script