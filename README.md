# DevOps For The Desperate

![dftd](book-cover.png "Book front cover")

This repo is for the book [DevOps for the Desperate](https://nostarch.com/devops-desperate).

## Directories

Each one of these directories contain different material for different parts in the book.
Here is a quick overview of each directory:

* _ansible_: Contains the playbook and tasks to follow along in the first section of the book.
** _Ansible is a Configuration Management tool that cann orchestrate the provisioning of infrastructure like VMs. Ansible uses a declarative configuration style, whihc means it allows you to decribe what the desired state of the infrastructure should look like.

 - Infrastructure as code

* _monitoring_: Contains the k8s manifest files to install Prometheus, Alertmanager, and Grafana.

* _runbooks_: Contains a simple runbook for `telnet-server` and examples of a runbook broken up by alert. These are used in the alerts for Chapter 9.

* _telnet-server_: Contains the sample application that is used throughout two-thirds of the book.

* _vagrant_: Contains the Vagrantfile for the VM used in the first section of the book.

** _Vagrant automates the process of creating the VM, while Ansible configures the VM once it's running.
** _Configuration Management is the process of configuring resources for a specific purpose in a predictable, repeatable manner. 

* _apple-silicon_: Contains the Vagrantfile for the VM used in the first section of the book and minikube instructions.
