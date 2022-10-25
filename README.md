## $5 Tech Unlocked 2021!
[Buy and download this product for only $5 on PacktPub.com](https://www.packtpub.com/)
-----
*The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# Mastering Ceph
This is the code repository for [Mastering Ceph](https://www.packtpub.com/virtualization-and-cloud/mastering-ceph?utm_source=github&utm_medium=repository&utm_content=9781785888786), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
Mastering Ceph covers all that you need to know to use Ceph effectively. Starting with design goals and planning steps that should be undertaken to ensure successful deployments, you will be guided through to setting up and deploying the Ceph cluster, with the help of orchestration tools. Key areas of Ceph including Bluestore, Erasure coding and cache tiering will be covered with help of examples. Development of applications which use Librados and Distributed computations with shared object classes are also covered. A section on tuning will take you through the process of optimisizing both Ceph and its supporting infrastructure. Finally, you will learn to troubleshoot issues and handle various scenarios where Ceph is likely not to recover on its own.

By the end of the book, you will be able to successfully deploy and operate a resilient high performance Ceph cluster.

## Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter1.
Chapter1, Chapter3, Chapter4, Chapter6, and Chapter7 does not contain code files.

The code will look like the following:
       
           ceph_origin: 'upstream'
           ceph_stable: true # use ceph stable branch
           ceph_stable_key: https://download.ceph.com/keys/release.asc
           ceph_stable_release: jewel # ceph stable release
           ceph_stable_repo: "http://download.ceph.com/debian-{{ ceph_stable_release }}"
           monitor_interface: enp0s8 #Check ifconfig
           public_network: 192.168.0.0/24
           journal_size: 1024

### Software requirements:

* VirtualBox: https://www.virtualbox.org/wiki/Downloads
* Vagrant: https://www.vagrantup.com/downloads.html
* Ansible

## Related Products:

* [Ceph Cookbook]( https://www.packtpub.com/virtualization-and-cloud/ceph-cookbook?utm_source=github&utm_medium=repository&utm_content=9781784393502 )

* [Learning Ceph]( https://www.packtpub.com/virtualization-and-cloud/learning-ceph?utm_source=github&utm_medium=repository&utm_content=9781783985623 )

* [Learning Ceph - Second Edition]( https://www.packtpub.com/virtualization-and-cloud/learning-ceph-second-edition?utm_source=github&utm_medium=repository&utm_content=9781787127913 )



### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781785888786">https://packt.link/free-ebook/9781785888786 </a> </p>