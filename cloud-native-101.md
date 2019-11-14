---
marp: true
title: Cloud Native 101
description: 
author: John Doe
date: 2019-11-03
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
  font-size: 20px;
}

h1 {
  font-size: 50px;
  color: #09c;
}

h2 {
  font-size: 40px;
}
</style>

<style scoped>
section {
  font-size: 20px;
}

h1 {
  font-size: 70px;
  color: #09c;
}

h2 {
  font-size: 40px;
}
</style>

Cloud Native 101
===

<!-- 2019. 11. 01  -->
<!-- <!-- footer: Copyright (c) 2019 SK Telecom Co. Ltd. All Rights Reserved. -->

---

# Cloud Native 101

<br>
<br>

**김영우** (Youngwoo Kim)
Data Labs, ICT기술센터, SK Telecom

---

<!-- _backgroundColor: white -->
# Cloud Native?

CNCF Cloud Native Definition v1.0, https://github.com/cncf/toc/blob/master/DEFINITION.md

> 클라우드 네이티브 기술을 사용하는 조직은 현대적인 퍼블릭, 프라이빗, 그리고 하이브리드 클라우드와 같이 동적인 환경에서 확장성 있는 애플리케이션을 만들고 운영할 수 있다. 컨테이너, 서비스 메시, 마이크로서비스, 불변의 인프라스트럭처, 그리고 선언적 API가 전형적인 접근 방식에 해당한다.

> 이 기술은 회복성이 있고, 관리 편의성을 제공하며, 가시성을 갖는 느슨하게 결합된 시스템을 가능하게 한다. 견고한 자동화와 함께 사용하면, 엔지니어는 영향이 큰 변경을 최소한의 노력으로 자주, 예측 가능하게 수행할 수 있다.

---

https://www.infoworld.com/article/3281046/what-is-cloud-native-the-modern-way-to-develop-software.html

> In general usage, “cloud-native” is an approach to building and running applications  
> that exploits the advantages of the cloud computing delivery model. “Cloud-native” is 
> about **how applications are created and deployed, not where.** It implies that the apps 
> live in the public cloud, as opposed to an on-premises datacenter.

> The CNCF defines “cloud-native” a little more narrowly, to mean using open source 
> software stack to be containerized, where each part of the app is packaged in its 
> own container, dynamically orchestrated so each part is actively scheduled and 
> managed to optimize resource utilization, and microservices-oriented to increase 
> the overall agility and maintainability of applications.

---

# References
- https://www.cncf.io/
- https://landscape.cncf.io/
- https://github.com/rootsongjc/awesome-cloud-native
