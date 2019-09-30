AWS CloudFromation Template

TASK:
Use Configuration Management (CM) tools like Ansible. Pupppet or Chef to automate the implementation and installation of a basic (and static) Drupal or WordPress sample site.

METHOD:
Automate the task by using a CloudFormation template.

DELIVERABLES:
A CloudFormation template that accepts user input as parameters where applicable (for instance, Admin password). This template should setup a VPC, create suubnets, launch a CM instance, pull the neccessary code (modules, classes, recipes, etc) from a Git repo (or S3 bucket), and configure the web instance for basic Drupal or WordPress setup.
