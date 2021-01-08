---
layout: page
title: T4Framework
subtitle: The Most Powerful MMO Action RPG Framework for UE4
---
<img src="https://t4framework.com/img/Folders2.png" width="18px" height="18px"> [Home](https://t4framework.com/index) > Tutorials

<style>.embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 3%; left: 5%; width: 92%; height: 94%; }</style>

### 1. 소개

- 언리얼 엔진의 무료 또는 유료 에셋을 T4Framework 에서 사용하는 방법을 소개합니다.
- 게임 개발 초보자도 쉽게 따라 할 수 있도록 게임 제작을 위한 A-Z 까지 모두 준비되어 있습니다.
- 복잡하고 어려운 기술적인 문제를 처음부터 고민하지 마시고, 그냥 따라만 해보시면 됩니다.

### 2. 준비

- Supported Engine Versions
  - 4.26 (Release Version : 4.26.0)
- T4Framework Downlaod
  - [GitHub/Tech4Labs/T4GameDeck](https://github.com/Tech4Labs/T4GameDeck)
- Example Project 
  - /Content/T4Tutorials/Step1_SkeletonCrew/Project/Tutorial_Step1_SkeletonCrewProject
- Required Asset
  - [Character] Skeleton Crew Bundle
    - [unrealengine.com/marketplace/product/skeleton-crew-bundle](https://www.unrealengine.com/marketplace/en-US/product/skeleton-crew-bundle)
    - /Content/SkeletonCrew
  - [FX] Paragon: Sparrow (FREE)
    - [unrealengine.com/marketplace/product/paragon-sparrow](https://www.unrealengine.com/marketplace/en-US/product/paragon-sparrow)
    - /Content/ParagonSparrow
  - [Map] Fantasy and Medieval Architecture Kit
    - [unrealengine.com/marketplace/product/fantasy-and-medieval-artchitecture-kit](https://www.unrealengine.com/marketplace/en-US/product/fantasy-and-medieval-artchitecture-kit)
    - /Content/FantasyVillage

### 3. 교정

- **튜토리얼 #6 : Map and NPC Spawn**
  - Project Settings 메뉴의 Project GameName 프로퍼티가 ProjectID 으로 이름이 변경되었습니다. (v1.2)
  - SkeletonCrewProject 프로젝트 생성 방법 (v1.2)
    - T4GameProject 에셋 생성 후 Content Editor 로 오픈합니다.
      - 콘텐츠 브라우저 => 마우스 우클릭 => T4Framework => Content => T4GameProject 선택 => 더블클릭 => SkeletonCrew 이름 변경
    - Project Settings 의 Project Initialization 버튼으로 기본 에셋 및 설정 자동 생성합니다.
      - <주의> T4GameProject 에셋의 이름인 "SkeletonCrew" 으로 필수 에셋이 자동 생성됩니다.

### 4. 과정

<center><b>[참고] 모든 영상에는 한글 자막이 포함되어 있습니다. 자막을 켜주세요!</b></center>
<center><b>[주의] 본 튜토리얼은 v1.0 버전 기준으로 작업되어 있어 최신 버전과 약간의 차이가 있을 수 있습니다.</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/MCfZAzuThAk' frameborder='0' allowfullscreen></iframe></div>
<center><b>#1 Character Setup : 캐릭터 기본 메시 및 애니메이션 설정 (Crossbowman)</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/QUjCAyhHibU' frameborder='0' allowfullscreen></iframe></div>
<center><b>#2 Weapon Equipment : 아이템 드랍 메시 및 캐릭터 무기 장착</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/iQpA5hsqqwc' frameborder='0' allowfullscreen></iframe></div>
<center><b>#3 Projectile Attack : 스킬 애니메이션과 발사체 공격 설정</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/i5v-t6q3mFw' frameborder='0' allowfullscreen></iframe></div>
<center><b>#4 Enemy AI Attack : NPC 등록 및 3가지 발사체 스킬 설정</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/TIJm9XPU4DM' frameborder='0' allowfullscreen></iframe></div>
<center><b>#5 Hit Reaction and Death : NPC 히트 리액션 및 사망 연출 설정</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/uMA97Sov5lQ' frameborder='0' allowfullscreen></iframe></div>
<center><b>#6 Map and NPC Spawn : 기본적인 맵 설정과 NPC 스폰 배치</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/ZBqJbzkHYp4' frameborder='0' allowfullscreen></iframe></div>
<center><b>#7 NPC Waypoints : NPC Waypoints 설정 (e.g. 순찰, 등장 연출)</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/_QVuQxRrbjs' frameborder='0' allowfullscreen></iframe></div>
<center><b>#8 Quest and Dialogue : 간단한 퀘스트와 NPC 대화 설정</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/Cgz1S6ZHa9I' frameborder='0' allowfullscreen></iframe></div>
<center><b>#9 Combat System : 캐릭터 별 특수 스킬 및 효과 설정</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/tmnTDLV4LSg' frameborder='0' allowfullscreen></iframe></div>
<center><b>#10 Game Settings : 게임 설정 및 클라이언트 실행</b></center>

<div class='embed-container'><iframe src='https://www.youtube.com/embed/NOZhEhQf3hI' frameborder='0' allowfullscreen></iframe></div>
<center><b>#11 New Features : 편의 기능 및 시간 변화(Time of Day) 소개</b></center>
