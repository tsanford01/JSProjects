# JSProjects
Projects designed by JS to pass knowledge.

	1. Create a repo for project: folders for playbooks, roles and docker
	2. Dockerfile - builds container with installed Ansible
		a. Container runs an ansible-playbook that runs locally and does a package update
	3. --Manual Steps
	4. On Build, 
		a. Create the image and pushes to dockerhub (manually)
	5. Pull down the image from DH and run a package update playbook against a remote machine
	6. End Manual Steps--
	7. --Automate the manual steps
	8. Using Github actions, run locally the package update using ansible playbook 
	9. Build the dockerfile and push to dockerhub using gh actions
  10. End Automation--
