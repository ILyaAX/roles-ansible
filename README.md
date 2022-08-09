# roles-ansible
DevOspSchool test # 9

Write the Ansible roles that prepare the build environment and the production environment on the two nodes. A project is built on the build node and run on the production node.

Created a role for build-server (server-build) - building the application in maven and transferring the artifact to the production node.

Created role for production-server (server-prod) - deploying environment and running application from artifact.


A role was created for the build-node (docker-build) - assembling the application image in the docker container and sending it to the registry.

Created role for production-node (docker-prod) - deploying the container with the application from the image stored in the registry.