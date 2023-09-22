---
title: "Sources"
permalink: /platform/repositories/
excerpt: "This side should give a brief overview which resources are import to build and run the tailoringexpert platform"
toc: true
toc_sticky: true
sidebar:
  nav: "platform"
---

This site is **Work in Progress**
{: .notice--danger}


This side should give a brief overview which resources are import to build and run the tailoringexpert platform.
All sources are available by public [github repositories](https://github.com/tailoringexpert). Most important repositories are listed hereafter.
{: .text-justify}

Except the dependencies pom no artifact will be deployed to an officel repository.
{: .notice--info}

## [dependencies](https://github.com/tailoringexpert/dependencies)

This repository provides the basic parent pom that is used by the platform and shall be used by all tenants to ensure all tenants use the same libraries.


## [platform](https://github.com/tailoringexpert/platform)

These are the sources of the core platform.
{: .text-justify}

## [web](https://github.com/tailoringexpert/web)

An example web frontend. This is used for the demo system.
{: .text-justify}

## [demo](https://github.com/tailoringexpert/demo)

An example tenant implementation. This could be used as base for creating your "own" tenant.
{: .text-justify}

## [docker containers](https://github.com/tailoringexpert/docker-containers)

Infrastructure to create docker images.

## [ansible playbook](https://github.com/tailoringexpert/ansible-playbook)

A set of ansible playbooks to install 

- platform
- tenant implementation and
- catalog data
