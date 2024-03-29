# [4주차] Project_3팀 진행상황 공유

## 팀 구성원, 개인 별 역할

### 김경환 (팀장)

- 스프링 배치를 통한 정산
- 플랫폼 매니저를 위한 환전

### 금시연

- 호스트에게 실시간 채팅 문의

### 김겸호

- 호스트, 일반 사용자 분리
- 호스트 페이지 구현
- 이벤트 구현

### 이유현

- 숙소 주변 행사 추천

### 정주영

- 숙소 주변 인프라 검색 기능

## 팀 내부 회의 진행 회차 및 일

- 1회차(2024.3.18) : 디스코드 진행 , 김겸호 불참 그 외 전원 참석
- 2회차(2024.3.19) : 디스코드 진행 , 전원 참석
- 3회차(2024.3.20) : 디스코드 진행 , 김경환 불참 그 외 전원 참석
- 4회차(2024.3.21) : 디스코드 진행 , 전원 참석
- 5회차(2024.3.22) : 디스코드 진행 , 전원 참석

## 현재까지 개발 과정 요약 (최소 500자 이상)

- 금시연
  - 목표: 채팅 기능 구현
  - 진행 상황:
    * 채팅방 퇴장 기능, 채팅방 구분(문의 진행중/종료).
    * 마이페이지에서 채팅방 최신순으로 정렬.
    * 안읽은 메세지 개수 표시
    * 예약 관련 테스트 코드 작성 중

- 김겸호
  - 목표: 호스트와 일반 고객 기능 분리
  - 진행 상황: 
    * 호스트모드에서 예약, 매출 현황 조회.
    * 쿠폰 발급, 결제 시 쿠폰 사용.
    * 정산 시 쿠폰 사용 금액 차감
    * 쿠폰 이용기간, 할인 금액 제한


- 김경환
  - 목표: 정산 관련 기능 구현 및 문서화
  - 진행 상황: 
    * 스프링배치 테스트코드 작성.
    * 마이페이지에서 정산 내역 조회.
    * DataInit 리팩토링 외 코드 리팩토링

- 이유현
  - 목표: 숙소 주변 행사 검색 관련 기능 구현
  - 진행 상황: 
    * 숙소 주변 행사 검색, 지도에 마커 표시 
    * 행사 관련 DB 작업 진행 중

- 정주영
  - 목표: 숙소 주변 편의시설 관련 정보 제공
  - 진행 상황: 
    * 네이버맵 마커 커스터마이징.
    * 리스트에서 마우스오버 시 마커 표시.
    * 마커 클릭 시 네이버 검색 가능


Github Repository URL: https://github.com/BES-HOTSIX

<img src="https://i.imgur.com/VheKeSp.png" width="900">
