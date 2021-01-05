---
layout: page
title: T4Framework
subtitle: 프레임워크 (Framework)
---
<img src="https://t4framework.com/img/Folders2.png" width="18px" height="18px"> [Home](https://t4framework.com/index) > [Features](https://t4framework.com/T4Framework_Features) > 프레임워크 (Flexible Framework)
<style> .embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0%; left: 0%; width: 99%; height: 99%; } </style>
<div class='embed-container'><iframe src='https://www.youtube.com/embed/zsMBieqbRaU' frameborder='0' allowfullscreen></iframe></div>
<hr>
### 1. UE4 Dedicated Server
- 개별 Actor, Component 단위의 Replication 기능은 사용하지 않음
  - 프로퍼티 업데이트 및 RPC
  - 안정성 및 최적화 측면에서 위험요소가 내재된 기능으로 판단
- 클라이언트는 오직 PlayerController 만 Replication 사용
  - PlayerController 는 MyPC 뿐 아니라 전반적인 PacketHandler 역할 담당
	- 일반적인 패킷 기반 서버 구성에서도 사용할 수 있도록 설계
- C/S 를 위한 별도의 ObjectID 와 컨테이너를 통해 GameObject 제어
- 이동 동기화를 Dead reckoning 구현
- 대규모 멀티플레이어 온라인 환경을 고려해 모든 캐릭터 이동은 새롭게 설계된 Movement Component 사용
- 편리한 존 기반 환경 설정과 Dedicated Server 에서의 동기화 지원

### 2. Multiple Games 및 Project
- 프로젝트 별 완전히 분리된 콘텐츠 데이터 및 제작 환경 제공
- 동일한 리소스 자원으로 다양한 장르 또는 짧은 미니 게임 제작 지원
- 프로젝트 별 게임 카메라와 UI 세트를 설정할 수 있도록 지원
- 프로젝트 별 게임 데이터를 손쉽게 이전할 수 있는 전용 마이그레이션 기능 지원

### 3. Replay
- 클라이언트 또는 툴에서의 게임 플레이를 녹화하여 재생할 수 있는 Playback 기능 지원
  - 사용자의 게임 활동을 녹화해 콘텐츠에 반영
  - 최적화 및 버그 디버깅등의 개발 자료로 확인

### 4. ETC
- 모바일 및 VR (Virtual Reality) 구현을 위한 기반 기능 지원
- 대량의 에셋을 손쉽게 검증할 수 있는 기능을 지원
<br>
