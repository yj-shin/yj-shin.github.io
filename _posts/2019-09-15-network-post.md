---
layout: post
categories: posts
title: "클라우드 컴퓨팅 기술인재 양성과정 포트폴리오"
subtitle: Network.
tags: [sample post, readability, test, intro]
date-string: SEPTEMBER 15, 2019
---

cisco packet tracer - 6.0.1

switch - 2960(3번째 선택)
![Smithsonian Image](/images/network/switch.png)
{: .image-right}

router - 2621XM(4번째 선택)
![Smithsonian Image](/images/network/router.png)
{: .image-right}

// 라우터 포트 3개 이상 설정할 경우
power off 후 NM-2FE2W 드래그 한 후 power on
![Smithsonian Image](/images/network/router_setting.png)
{: .image-right}


빠져나오기 - ctr + shift + 6

[라우터 살리기]
enable
show running - config
conf t
int fa 0/0
no shutdown

[EIGRP routing protocol 설정]
router eigrp 100
network 11.0.0.0

[IP address 설정]
int fa 0/0
ip address 11.1.2.1 255.255.255.0
int fa 0/1
ip address 11.1.3.1 255.255.255.0



