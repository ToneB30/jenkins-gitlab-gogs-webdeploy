*********************************************
Jenkins with 2 slaves, Nexus, GitLab and GoGS
*********************************************

.. image:: https://cdn.rawgit.com/odb/official-bash-logo/master/assets/Logos/Identity/PNG/BASH_logo-transparent-bg-color.png

In this repository 'Vagrantfile' will deploy 6 machines: 
1. Jenkins master (Same time Nexus)
2. Jenkins slave node1
3. Jenkins slave node2
4. GitLab server
5. GoGS server

You can take Jenkins 'admin' password in the Jenkins master server from file '/var/lib/jenkins/secrets/initialAdminPassword'
Jenkins master server listens on port 8080 Nexus listens on port 8081.

Gogs admin login: gogs
Gogs admin login password: gogspassword

=====
Usage
=====

* Just download repository and start virtual machines::

    # git clone https://github.com/jamalshahverdiev/jenkins-gitlab-gogs-webdeploy.git
    # cd jenkins-gitlab-gogs-webdeploy
    # vagrant up
