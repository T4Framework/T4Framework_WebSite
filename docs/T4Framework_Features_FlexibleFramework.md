---
layout: page
title: T4Framework
subtitle: 유연한 프레임워크 (Flexible Framework)
---
<img src="https://tech4labs.com/img/Folders2.png" width="18px" height="18px"> [Home](https://tech4labs.com/index) > [Features](https://tech4labs.com/T4Framework_Features) > 유연한 프레임워크 (Flexible Framework)

<style> .embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 1%; left: 0%; width: 99%; height: 99%; } </style>
<div class='embed-container'><iframe src='https://www.youtube.com/embed/OqDk2P-oLSA' frameborder='0' allowfullscreen></iframe></div>
<hr>
#### 1. UE4 Dedicated Server 지원
- 개별 Actor, Component 단위의 Replication 기능은 사용하지 않음
  - 프로퍼티 업데이트 및 RPC
  - 안정성 및 최적화 측면에서 위험요소가 내재된 기능으로 판단
- 클라이언트는 오직 PlayerController 만 Replication 사용
  - PlayerController 는 MyPC 뿐 아니라 전반적인 PacketHandler 역할을 담당
	- 일반적인 패킷 기반 서버 구성에서도 사용할 수 있도록 설계
- C/S 를 위한 별도의 ObjectID 와 컨테이너를 통해 GameObject 제어
- 이동 동기화를 Dead reckoning, 가속 이동 테스트
- 대규모 멀티플레이어 온라인 환경을 고려해 모든 캐릭터 이동은 새롭게 설계된 Movement Component 사용
- 편리한 존 기반 환경 설정과 Dedicated Server 에서의 동기화를 지원합니다.

#### 2. 워크플로 소개
- 모바일 및 VR (Virtual Reality) 구현을 위한 기반 기능 지원
- 손쉬운 게임 모드 설정 및 사용과 리플레이 시스템과의 연동 지원
- 클라이언트 또는 툴에서의 게임 플레이를 녹화하여 재생할 수 있는 Playback 기능
- 자체 커맨드렛을 통해 자동으로 파라곤 에셋의 마이그레이션을 지원합니다.
- 파라곤 캐릭터의 스킬(애니메이션 & 파티클)을 자동으로 생성하고 테스트 하실 수 있습니다.
- 대량의 에셋을 손쉽게 검증할 수 있는 기능을 지원합니다.
<br>
