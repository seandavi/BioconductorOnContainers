# Bioconductor on Containers

# Instructor(s) name(s) and contact information

Nitesh Turaga <nitesh.turaga@roswellpark.org> (Github: @nturaga)

# Workshop Description

Bioconductor provides Docker containers which aim to provide isolated
and reproducible environments for analysis. These containers avoid
complex installation issues for the user. This workshop will focus on
how to use Bioconductor docker images, talk about the different kinds
of flavors of Bioconductor Docker images are present and as a final
advanced topic we will cover how to extrapolate these Docker images to
use on cloud services and also on HPC infrastructure with Singularity.

## Pre-requisites

* Basic knowledge of R syntax / how to install packages the
  Bioconductor way (using `BiocManager()`).

* Docker needs to be installed on your local machine. Please
  [install](https://docs.docker.com/install/) ahead of time. If you
  are planning to attend this workshop and are having issues
  installing Docker please email me ahead of time, I will help you
  through it.

* Some familiarity with HPC infrastructure (if this is relevant to
  participant).

List relevant background reading for the workshop, including any
theoretical background you expect students to have.

* (Required) Install Docker https://docs.docker.com/install/ ahead of
  time. Help will not be provided during the workshop.

* (Optional) Read about Bioconda and `conda` if you are interested.

## Workshop Participation

Participants are expected to launch Docker images on their local
machines, mount volumes, and set ports. They will learn to selectively
use a required set of packages for the particular Docker image. There
is going to be a live demonstration of usage of Docker, and
participants are exptected to follow along.

## _R_ / _Bioconductor_ packages used

* BiocManager

## Time outline

An example for a 1 hour 45-minute workshop:

| Activity                     | Time |
|------------------------------|------|
| Why Docker                   | 10m  |
| Bioconductor on Docker       | 10m  |
| Flavors of Bioconductor      | 10m  |
| Which flavor to use          | 10m  |
| How to mount volumes         | 10m  |
| Docker on the cloud          | 10m  |
| Mount volumes on the cloud   | 10m  |
| Localize select packages     | 10m  |
| HPC-Singularity containers   | 5m   |
| Launch and run parallel jobs | 10m  |
| Questions                    | 10m  |

# Workshop goals and objectives

## Learning goals

Participants will understand **how** and **why** and **when** to use
Bioconductor with Docker images. Workshop will differentiate the
**flavor** of Bioconductor containers, and how set them up in a
reproducible fashion. The workshop will describe practice how to use
Docker images and mount volumes as needed from their local machine,
which will design a working evironment which does not need any
installation of system dependencies. The workshop will also outline
how to use Docker on cloud services such as Google cloud and AWS,
breifly, allowing users to launch an image on a cloud instance, giving
them instant access to Bioconductor facilities. We will discuss
briefly how to set up Singularity containers on high performance
computing platforms, and point out resources to enable parallel
computing with containers, taking away the burden to ask system
administrators to install resources for them.

## Learning objectives

Participants will learn how to use the Bioconductor Docker images.
Using these Docker images, they will practice important topics for
creating reproducible environments for their analysis, such as,
mounting volumes as needed from their local machine, adding additional
packages. They will be able to identify the correct flavor of the
Bioconductor docker image for their needs.
