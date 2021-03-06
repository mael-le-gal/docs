---
title: 'Manage Object Storage with CyberDuck'
excerpt: 'Manage Object Storage with CyberDuck'
slug: manage_object_storage_with_cyberduck
section: 'Object Storage'
legacy_guide_number: g1868
---

**Last updated 8th January 2020**

## 
Object Storage is a storage solution that is managed primarily through the OpenStack API.

If you're not familiar with managing storage through command lines, there are some graphics solutions that use the OpenStack API for you. CyberDuck is one of these solutions and it is easy to configure. 

This guide will explain how to configure Cyberduck to manage your Object Storage using a graphical interface based on the Openstack APIs.


## Prerequisites

- You must have access to Horizon: [Accessing the Horizon interface](../../public-cloud/configure_user_access_to_horizon/)
- You must have your project and user ID, which you can get by downloading the OpenRC file in the [Access and Security](../../public-cloud/access_and_security_in_horizon/) menu in Horizon.




## 

- Download [Cyberduck](https://cyberduck.io/)
- Log in to a "Swift - OpenStack Object Storage" account


![objectstorage-cyberduck](images/Cyberduck.png){.thumbnail}

Enter the following information:

- Server: auth.cloud.ovh.net (Authentication server)
- Project:Domain:Username : OS_TENANT_NAME:default:OS_USERNAME
- Secret Key: your Horizon user password



- Log in



![objectstorage-cyberduck](images/img_2756.jpg){.thumbnail}


##

[Getting started with the Swift API](../../public-cloud/getting_started_with_the_swift_api/)