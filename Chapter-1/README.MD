# Chapter 1

# 1. A quick tour for GCP Console

### Lab Details:

1. The Agenda of this GCP Lab is to Practice Logging into the GCP Console. Once Logged in, You can navigate  through the GCP Console to get yourself familiarized with the GCP Console. By the End of the Lab, you will understand how the GCP Console looks, Understand how you can serach various GCP services, and undersatnd various GCP resource locations and how they are categorized. 

2. Region: **Us-Central1.**

## What is GCP Console?

1. User can create, configure and manage various cloud resources such as Virtual Machines (Google Compute Engine Instances), Storage Buckets (Google Cloud Storage), Databases (Google Cloud SQL, Cloud Firestore, etc) and more.

2. The console offers monitoring and logging tools that allow users to monitor the performance, health and utilization of their resources. it also provides access to logs and metrics to troubleshoot issues.

3. Users can deploy applications and services easily and scale resources up or down based on demand using features like Google Kubernetes Engine for container orchestration.

4. The GCP console provides tools to manage access control, setup firewalls, and implement security policies to ensure the protection of resources and data.

5. Users can track and manage their usage and costs, set budgets, and view billing information to optimize their spending on cloud services.

## Architecture Diagram:

![Alt text](./GCP1.jpg)

## What is Google Cloud Shell?

* Cloud Shell is a Debian-based VM with 5 GB of free persistent disk storage that provides you with command-line access to your cloud resources directly from the browser.

## Google Cloud CLI Commands using Cloud Shell:

### Lab Details:

1. This lab walks you through Google Cloud CLI Commands using Cloud Shell 

2. You will be creating a VM instance and VCP network using Cloud Shell

### Lab Overview:

* Cloud Shell is Debian-based VM with 5 GB of free persistent disk storage that provides you with the command line access to your Cloud resourecs directly from your browser.

* You can easily manage your projects and resources without having to install Cloud SDK on your system.

* Gcloud is the command line interface to interact with most of the GCP services which are preinstalled in Cloudshell. By using Gcloud you can talk to compute Engine VMs, Managed Instance Groups, Create a database, and so on.

* Some Google Cloud Services have specific CLI tools for accessing the particular service.

  * Cloud Storage - gsutil 
  * Big Query - bq
  * Cloud Bigtable - cbt
  * Kubernetes(for managing pods and deployments)- Kubectl


### Lab Task:

  1. Login into the GCP Console

  2. Opening and exploring Cloudshell

  3. Creating a VPC using Cloud Shell

  4. Creating a VM instance using Cloudshell

  5. SSH into the VM instance

### Launching Lab Environment:

1. Launch the lab environment by clicking on the **start Lab** button from the right sidebar. This will create a GCP environment with the resourcesand rolesrequired for the lab.

2. Once the lab environment is ready, the **Open Console** button will be active. Click on the **Open Console** button, this will open Google Sign-in page. (Make sure you are using **Incognito Mode**).

3. Navigate back to Lab document, You will see **Lab Credentials**, Copy the credentials to sign-in to the console from the highlighted Email and password using Copy button.

# 2. Creating your first GCP VM:

## What is a GCP Compute Engine?

* GCP VM is an IaaS (Infrastructure as a Service). All you have got to make and put together your own VM Instances. You have complete control over the VMs instances and the runtime. GCP Compute Engine is the easiest way to use Google's Data Centers virtually. You have direct access to the packages and you put all the packages that you simply need, which is typically a web server, Database etc.

* A Compute Engine is comparable to a Virtual PC, where you would deploy a small website plus the database
and then setup the DNS yourself.

* GCE Instances are the most customizable unit there and thus should only be used when your application can't run on any other GCPS Services. Most of the time people use GCE to transfer their On-Prem applications to GCP since it requires minimal changes.

* Compute Engine offers a set of predefined machine types and custom machine types also so that you can use it while creating an instance. A predefined machine type has a defined number of VCPUs and amount of memory, where as in a custom machine type you can choose a number of VCPUs and memory.

* The only drawbacks is that you have to manage your app and VMs yourself including control of installed Disk Drives.

## Advantages: 

* Easy to Ramp up. There is no need to ramp up on kubernetes or App Engine.

* Complete control- You can leverage many compute engine features directly and install the software packages of your need.

* No need for public IPs.

## Disadvantages:

* Mostly do it yourself, which can be challenging, Although you can reuse solutions, sometimes lack experience may lead to a security breach.

## Architecture Diagram:




