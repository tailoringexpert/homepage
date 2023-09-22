---
title: "Building and installation"
permalink: /platform/installation/
excerpt: "This side should give a brief overview which resources are import to build and run the tailoringexpert platform"
toc: true
toc_sticky: true
sidebar:
  nav: "platform"
---

This site is **Work in Progress**
{: .notice--danger}

This page shall give information on how to build and install the platform.

## build

### Prerequisites

#### backend

The backend part of the platform is implemented in Java. Therefor a Java version >= 17 is neesed.  
To build the platform in installed version of maven is also needed.


### Building the backend platform

First you need to clone the [backend platform](https://github.com/tailoringexpert/platform).
>  git clone https://github.com/tailoringexpert/platform

After that run 
> mvn install

in top directory of checked out directory. All dependencies are resolved by the maven build. 
 
It is important to mention that for further installation steps the `tailoringexpert-distribution` module generates artifacts to be used in later steps
{: .notice--info}

### Building the frontend platform

The example frontend is implemented as `vue` single page application, but there is a maven pom to build the distribution. A _simple_ 
> mvn install

is sufficent. All needed requirements will, hopfully, resolved and also a needed node instance will be installed in the project.


## installation

The The platform either be deployed as a

- containerized/dockerized
- traditional

system.

### containerized/dockerized

The [docker containers repository](https://github.com/tailoringexpert/docker-containers) provides `docker-compose` files and corresponding directory structure to create
docker images. Because no binaries are deployed in any public repository, you have to copy related files to correspondig directorie. There is a `README.md` in every directory
with instructions, what files should be in this directory.
{: .text-justify}

### traditional




 