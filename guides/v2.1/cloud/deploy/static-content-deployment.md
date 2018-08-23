---
group: cloud
title: Static content deployment strategies
functional_areas:
  - Cloud
  - Configuration
---

Static content deployment (SCD) has a great impact on the store deployment process that depends on the amount of content generated, such as images, scripts, CSS, videos, and web pages. Depending on your deployment needs, you can configure the SCD using one of several strategies:

-  SCD on build
-  SCD on demand
-  SCD on deploy (_default_)
-  Ideal state

The {{site.data.var.ct}} package contains the `config:dump` command that reads locales and saves them in the `app/etc.config.php` file.


## SCD on build

Generating SCD on the build phase is the optimal configuration for zero-downtime deployments, also known as the "ideal state".

## SCD on deploy

Generating SCD on the deploy phase is the default configuration. 

## SCD on demand

Generating SCD on demand is optimal for a development workflow. It decreases deployment time so that you can quickly review your implementations and run integration tests. 



