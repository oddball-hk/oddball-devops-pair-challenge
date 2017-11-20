# Terraform Ansible Spec

Purpose of this is to build a simple terraform ansible test project.

Project should include these pieces:

## Terraform
  * RDS DB (postgres)
  * EC2 instance

## Ansible
A playbook to:
  * Install nodejs + npm
  * clone the application
  * Install npm package `forever`
  * Start the app

## Notes

## Terraform config

* Use variables so I can easily change settings on the DB.
* we can wire these up into a completely open security group for now.
* Include outputs so we can load our variables as json in ansible


## Ansible configuration
  * Install nodejs, npm and get a simple app that connects to a db up and running.
  * source code for this app available [here](https://github.com/oddballio/oddball-hello-db)
