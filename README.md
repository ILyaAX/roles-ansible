# roles-ansible
DevOspSchool test # 9

Write the Ansible roles that prepare the build environment and the production environment on the two nodes. A project is built on the build node and run on the production node.


A role is created for the build-node - building the application image in the docker container and sending it to registry.
Created a role for the production node - deploying the container with the application from the image stored in the registry.