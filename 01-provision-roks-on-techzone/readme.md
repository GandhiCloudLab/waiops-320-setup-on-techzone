# Provisioning ROKS Cluster On TechZone

This document explains about Provisioning IBM RedHat Openshift Kubernetes Service (ROKS)
cluster on Techzone.

## 1. Login into Techzone

Login into techzone using the URL https://techzone.ibm.com/

## 2. Choose ROKS Cluster

1. Click on `IBM Technology Zone` icon on the top
<img src="images/image-00001.png">

2. Type `ROKS` and press enter to search
<img src="images/image-00002.png">

3. Choose `Custom ROKS & VMware requests`
<img src="images/image-00003.png">

4. Click `Reserve` on the title `IBM RedHat Openshift Kubernetes Service (ROKS)`
<img src="images/image-00005.png">
<img src="images/image-00006.png">
<img src="images/image-00007.png">

## 3. Create Reservation

1. Choose `Reserve Now`
<img src="images/image-00008.png">

1. Enter all the fields values as given in screenshot. 
- Purpose: It can be Test or POC
- Worker Node Count : 5
- Worker Node Flavour : b3c.16x64
- Openshift Version : 4.8
<img src="images/image-00009.png">
<img src="images/image-00010.png">
<img src="images/image-00011.png">

Reservation is created and it will take 1 hour to complete. You will get a mail once the environment is ready.

## 3. Access Cluster

Goto to My Reservation page that lists all the reservation that you have made so far.

1. Click the view icon to open the particular cluster.
<img src="images/image-00012.png">

2. Click on `Open your IBM Cloud environment`
<img src="images/image-00013.png">

3. Click on  `Openshift web console `
<img src="images/image-00014.png">

Here is the Openshift web console .
<img src="images/image-00015.png">

