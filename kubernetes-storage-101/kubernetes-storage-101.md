---
marp: true
title: Kubernetes Storage 101
description: Kubernetes Storage 101
author: Youngwoo Kim <ywkim@apache.org>
date: 2019-11-03
paginate: true
---
<!--
theme: gaia
class: lead
size: A4
backgroundColor: white
-->

<!-- Global style -->
<style>
section {
  font-size: 25px;
}

h1 {
  font-size: 45px;
  color: #09c;
}

h2 {
  font-size: 40px;
}
</style>

<style scoped>
h1 {
  font-size: 70px;
  color: #09c;
}
</style>

Kubernetes Storage 101
===

<!-- 2019. 11. 01  -->

<!-- <!-- footer: Copyright (c) 2019 SK Telecom Co. Ltd. All Rights Reserved. -->

---

# Kubernetes Storage 101

<br>
<br>

김영우 (Youngwoo Kim)
Data Labs, ICT기술센터, SK Telecom

---

# What is Kubernetes? 

- Kubernetes is an open source **container orchestration engine** for automating deployment, scaling, and management of containerized applications. The open source project is hosted by the Cloud Native Computing Foundation

![bg right](https://selleo.com/uploads/kubernetes.jpg)

---

# Kubernetes Volumes vs Persistent Volume

- There are currently two types of storage abstracts available with Kubernetes: `Volumes` and `Persistent Volumes`. 
- A Kubernetes volume exists only while the containing pod exists. Once the pod is deleted, the associated volume is also deleted.
- Kubernetes persistent volumes are used in situations where the data needs to be retained regardless of the pod lifecycle. Kubernetes volumes are used for storing temporary data

---

# Volume Plugins (aka Types of Volumes)

- https://kubernetes.io/docs/concepts/storage/volumes/#types-of-volumes

---

# Dynamic Volume Provisioning

---

# Container Storage Interface (CSI)

- CSI is a community-driven effort to standardize how file and block storage are exposed to and accessed by container orchestrators, such as Cloud Foundry, Kubernetes, and Mesos.
- Kubernetes and CSI
![height:400px](https://blogs.vmware.com/cloudnative/files/2019/04/kubernetes-csi-components.png)
- Kubernetes CSI Drivers
  - https://kubernetes-csi.github.io/docs/drivers.html

---

# Kubernetes Storage

| Storage Activity | Kubernetes storage primitive |
| --- | --- |
| Provisioning | Persistent Volume |
| Configuring | Storage Class
| Attaching | Persistent Volume Claim |

---

# Persistent Storage Strategies for Kubernetes

![height:500px](https://images.xenonstack.com/blog/object-storage-kubernetes.png)

https://www.xenonstack.com/blog/persistent-storage/

---

# Cloud Native Storage

https://landscape.cncf.io/category=cloud-native-storage&format=card-mode&grouping=category


---

# Related Projects

- Rook
- GlusterFs

---

# 참고

- https://kubernetes.io/
- https://kubernetes-csi.github.io/

---

# Image Credits

- https://blogs.vmware.com/cloudnative/2019/04/18/supercharging-kubernetes-storage-with-csi/

---

![bg](https://media1.tenor.com/images/9203d2b993225b80a0d242c271d137a8/tenor.gif?itemid=5508214)
