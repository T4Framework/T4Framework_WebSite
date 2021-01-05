---
layout: page
title: T4Framework
subtitle: 액션 에디터 (Action Editor)
googlefonts: ["Noto Serif KR"]
---
<img src="https://t4framework.com/img/Folders2.png" width="18px" height="18px"> [Home](https://t4framework.com/index) > 액션 에디터 (Action Editor)
<style> .embed-container { position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; } .embed-container iframe, .embed-container object, .embed-container embed { position: absolute; top: 0%; left: 0%; width: 99%; height: 99%; } </style>
<div class='embed-container'><iframe src='https://www.youtube.com/embed/Z-DLnRLcHmI' frameborder='0' allowfullscreen></iframe></div>
<hr>
### 1. 액션 에디터는?
- 캐릭터 전투 및 각종 연출 효과 설정을 위한 액션 툴입니다.
- 언리얼 엔진의 복잡한 기능들을 사용자 관점에서 사용하기 쉽도록 설계되어 있습니다.
- 툴에서 변경한 내용을 빠르게 확인할 수 있는 다양한 기능을 지원하고 있습니다.

### 2. 주요 기능 소개
- 다양한 액션을 조합해 새로운 연출 제작 지원
  - 플레이 시작 및 전체 시간에 대한 타임라인 기반 편집
  - OneShot, Looping, Duration 등의 플레이 모드
  - 부모 캐릭터의 본(소켓)에 Attach 및 World 생성
  - Relative Transform에 대한 Local Offset
- 액션 리스트
  - 애니메이션 액션 (Animation Action)
    - 애니메이션 블렌딩 시간 설정 및 조합 설정
    - 연속 동작 설정 및 플레이 타임 조정
    - ex) 공격 및 루핑 애니메이션, 연속 기술 사용
  - 메시 액션 (Mesh Action)
    - Static Mesh 임의 시간 출력
    - ex) 활 또는 물체를 일정 시간 사용 후 삭제
  - 파티클 액션 (Particle Action)
    - 캐스케이드로 제작된 ParticleSystem 출력
    - ex) 마법, 버프, 히트 등의 각종 효과 표현용 파티클
  - 데칼 액션 (Decal Action)
    - 데칼 머트리얼 설정 및 출력 방향 설정
    - ex) 지저분한 바닥 표현
  - 오디오 액션 (Audio Action)
    - 사운드 에셋 및 Attenuation 세팅 설정
    - ex) 각종 효과 사운드 설정
  - 트레일 액션 (Trail Action)
    - 시작, 끝 지점에 Particle Trail 설정
    - ex) 검광, 체인 라이트닝
  - 프로젝타일 액션 (Projectile Action)
    - 발사체 Casting, Fire 등의 연출 설정
    - 직선, 곡사 등의 다양한 궤적 설정
    - ex) 화살, 총알 궤적
  - 무브먼트 액션 (Movement Action)
    - 지정 시간, 위치로의 이동 관련 설정
    - ex) 점프, 넉다운, 넉백
  - 리액션 액션 (Reaction Action)
    - 시작=>루핑=>끝 등의 가변 애니메이션 시퀀스 설정
    - 렉돌 또는 플린칭 등의 효과 설정
    - ex) 히트, 사망, 넉백, 에어본
  - 플레이 태그 액션 (PlayTag Action)
    - 엔티티에서 설정된 Attach/Material/Action 태그 플레이
    - ex) 머트리얼 교체, 무기 장착/해제, 특정 액션 실행
  - 머트리얼 파라미터 액션 (MaterialParameter Action)
    - 머트리얼 파라미터 업데이트 및 복원
    - ex) 히트 및 버프/디버프 시 Color 적용
  - 타임스케일 액션 (TimeScale Action)
    - 게임 시간을 느리게 또는 빠르게 설정
    - Timeline 구간 별 가변 속도 적용
    - ex) 슬로 모션
  - 카메라 워크 액션 (CameraWork Action)
    - 포인트를 기준으로 카메라 이동 설정
    - ex) 특정 액션 구간에 대한 카메라 강조 처리
  - 카메라 셰이크 액션 (CameraShake Action)
    - 카메라 흔들기
    - ex) 히트 구간 강조
  - 포스트 프로세스 액션 (Environment Action)
    - 스크린 기반 후처리 필터 및 효과 설정
    - ex) 흑백, 대비 등의 각종 필터 효과
  - 환경 액션 (Environment Action)
    - 특정 영역 내 동적인 환경 설정 적용
    - ex) 눈, 비등의 동적인 효과
  - 이벤트 액션 (Event Action)
    - 시스템에 의해 약속된 이벤트 설정
    - ex) 무기의 충돌 효과 시작과 끝
  - 브랜치 액션 (Branch Action)
    - 컨디션에 따른 분기 처리
    - ex) 비 또는 눈일 경우 다른 Action 실행
<br>