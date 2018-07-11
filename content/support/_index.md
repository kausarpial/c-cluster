---
title: "Support"
date: 2018-07-11T13:06:40+06:00
---

## Support

When you are using CloudyCluster through the AWS Marketplace, the support included is next business day email support at [support@cloudycluster.com](mailto:support@cloudycluster.com).  
Please include your account ID in any support communications and the version you are using.

If you would like additional options for support, Omnibond offers custom plans please contact [sales@omnibond.com](mailto:sales@omnibond.com)

<br>

#### Current Issues

If there are outstanding issues with AMIs in the AWS Marketplace we will put that information here and give you an ETA as soon as possible.

Current Release is 1.4.0 with an available 1.4.1 update at control node launch.

1.4.1 is available as an online update and resolves the following issues:

1. Enabling a login node for direct scheduler interaction (from the Administration tab), did not work properly in all situations. 
2. Updated new instance types for placement groups that were overlooked in the 1.4.0 release
3. Updated support for a couple of resources that would not work with 17 digit ids
4. Fixed an MFA feature broke the ability to support limited CIDR for ingress to Login node.

To apply the update, launch a new 1.4.0 control instance, then when you create a new HPC Environment you will have an option for 1.4.1 under version (where it normally says current version), select 1.4.1 and any login/scheduler nodes created as part of this environment will be updated to the new version.
