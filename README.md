# Intel HPC Developers Conference

Here you will find the preparation information, materials, and requirements to be part of the [Intel HPC DevCon](http://www.intel.com/content/www/us/en/events/hpcdevcon/overview.html) as part of Supercomputing 2016 ([click here to register for free](https://hpcdevcon.intel.com/register/devcon.aspx)).

As you can see on the [agenda](http://www.intel.com/content/www/us/en/events/hpcdevcon/agenda.html), there are two sessions dedicated to Singularity:

1. [Session 1, Saturday 12th at 2:05-3:30pm - HPC Containers & Singularity (Overview and Tutorial)](http://www.intel.com/content/www/us/en/events/hpcdevcon/technical-sessions.html#singularity)

2. [Session 2, Sunday 13th at 9:45-10:35am - HPC Containers and & Singularity (Advanced Tutorial)](http://www.intel.com/content/www/us/en/events/hpcdevcon/technical-sessions.html#lbnl)



## Session 1 Overview
This session will consist of a presentation covering an introduction to Singularity (about 30-45 minutes depending on questions) and a lab followup with the remainder of the time.

The lab will have the session attendees install Singularity on a computer that they "own" (either a laptop they have with them, a Linux workstation or server they have root on, or a cloud based Linux instance they have control of (e.g. AWS)). Once they have installed Singularity on their end-point, we will start off by using a container in the Docker registry and then walk through building and modifying a Singularity container image. The lab will then cover various methods and usage models of the container images on resources where you may or may not have root access.


### Session 1 Lab Requirements
To be part of this lab, you will have to have each of the following:

* You must have a general working knowledge of Linux and be familiar with installing packages, updates, etc.
* It is necessary that you have root (`sudo`) access to at least one Linux computer via a terminal. This could be a physical Linux laptop, workstation, or server that you control and can `ssh` into, or it could be a virtual machine on your laptop that you bring with you.
* The Linux computer that you will be using for the duration of the Lab should be of the following:
	* A recent version of Linux (of the vintage of RHEL6 or newer)
	* For simplicity, either an RPM or Debian based derivative of Linux (e.g. Centos, SL, RHEL, Ubuntu, Debian, etc..)
	* Development tools should be installed (`yum groupinstall "Development Tools"`)
	* This should **not** be a production server!


## Session 2 Overview
This section will focus on more advanced usage of Singularity, including workflow integration, more detailed build and bootstrap recipes, and depending on time and interest, resource management, MPI, and GPUs.

### Session 2 Lab Requirements
This lab will leverage what we did with Session 1, so you will need to come to the lab with Singularity installed on an end point that you control (as root) and have a basic working knowledge of Singularity (preferably you were at Session 1).
