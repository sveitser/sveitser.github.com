---
layout: post
title: "Liquid Feedback with Docker for Dimsumlabs"
description: "Self Hosted Direct Democracy"
category: 
tags: [liquid feedback, lqfb, docker, hackerspace, democracy]
---
{% include JB/setup %}

At [dimsumlabs.com](http://dimsumlabs.com) we recently decided to experiment with democratic decision
making online. [Liquid Feedback](http://liquidfeedback.org/) occured as the
tool most fit for the job. Unfortunately the [installation
process](http://dev.liquidfeedback.org/trac/lf/wiki/installation) involves
quite a few steps.

Here's a
[Dockerfile](https://github.com/dimsumlabs/liquid_feedback_docker/blob/master/Dockerfile) based on 
[Phusion/Baseimage](https://github.com/phusion/baseimage-docker) which 
should make it rather straightforward to give Liquid Feedback a spin.

If interested see  [https://github.com/dimsumlabs/liquid_feedback_docker](https://github.com/dimsumlabs/liquid_feedback_docker).

