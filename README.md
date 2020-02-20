---
copyright:
  years: 2020
lastupdated: "2020-02-20"
lasttested: "2020-02-20"
---

# Creating a multizone highly available application using IBM Virtual Private Cloud

This tutorial will walk you thru creating a custom Virtual Private Cloud (VPC) within IBM Public Cloud.  

## Architecture

TODO:  upload architecture diagram  
TODO:  describe diagram with numbers and why

## Outline

For an overview of IBM Virtual Private Cloud (VPC), please refer to [About VPC](https://cloud.ibm.com/docs/vpc-on-classic?topic=vpc-on-classic-about).

1. Configure a Virtual Private Cloud (VPC).
2. Create Virtual Server Instances (VSI).
3. Install web-app workload.
4. Configure High Availability and horizontal scalability.
5. Test application resilency.

## Configuration Procedure

1.  Create VPC (naming convention)
2.  Create address-ranges to make readability better.
3.  Change name of default network access control lists (NACLs).
4.  Rename default security group and change rules.
5.  Create DB security group and add rules. (TODO:  start lax and test, then tighten down)

