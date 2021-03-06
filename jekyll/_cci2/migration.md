---
layout: classic-docs
title: "Migration"
description: "Migration"
---

Migrate an existing 1.0 project to CircleCI 2.0.

Document | Description
----|----------
[Migrating from 1.0 to 2.0]({{ site.baseurl }}/2.0/migrating-from-1-2/) | Migrating a 1.0 Linux project to a CircleCI 2.0 configuration.
[iOS Migration]({{ site.baseurl }}/2.0/ios-migrating-from-1-2/) | Migrating a 1.0 iOS project to a CircleCI 2.0 configuration.
[Using the 1.0-to-2.0 config-translation Endpoint]({{ site.baseurl }}/2.0/config-translation/) | Instructions for using the `config-translation` endpoint to generate an initial CircleCI 2.0 configuration from your existing CircleCI 1.0 project for a limited set of languages: Ruby, PHP, Node.js, iOS (partial: 1.0 code signing is not supported - use Fastlane instead), Java (partial).
[CircleCI Configuration Generator](https://github.com/CircleCI-Public/circleci-config-generator) | This script extends our 1.0-to-2.0 config-translation endpoint: it will create a 2.0 test branch for your project, generate a 2.0 config file on that branch, and then push a commit to run 2.0 build on CircleCI
{: class="table table-striped"}

Conceptually, 2.0 is very different, read the following documents to get answers to common 2.0 questions and to begin to let go of the 1.0 mindset.

## Concepts 

Document | Description
---------|----------
[Concepts]({{ site.baseurl }}/2.0/concepts/) | A high-level overview of CircleCI 2.0 Steps, Image, Jobs, and Workflows concepts and the configuration hierarchy.
[Workflows]({{ site.baseurl }}/2.0/workflows/) | How to configure Workflows to increase the speed of your software development through faster feedback, shorter reruns, and more efficient use of resources.
[FAQ]({{ site.baseurl }}/2.0/faq/) | Frequently asked questions about CircleCI 2.0.
{: class="table table-striped"}
