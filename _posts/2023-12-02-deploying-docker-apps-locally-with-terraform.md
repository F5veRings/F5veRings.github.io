---
layout: post
gisqus_comments: "true"
title: Deploying docker apps locally with Terraform
date: 2023-12-02T23:42:38.053Z
description: Part of the Terraform Introduction series
tags: docker, terraform, IaC, CI/CD
categories: tutorials
related_posts: "false"
---
We'll start with a Docker image hosting an NGINX server.
This guide assumes you installed Terraform in Windows 11 using chocolatey, and your docker engine is running properly.

Terraform takes in a config file, by default named main.tf
It is basically a configuration file containing dictionary maps that specify the desired infrastructure and the values required. 
