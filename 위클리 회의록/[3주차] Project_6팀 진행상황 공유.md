## 팀 구성원, 개인 별 역할

- 김겸호(숙소 관련 기능 구현)
1. 로그인, 배포 관련 안정화
2. 숙소 찜하기 기능
3. 숙소 검색
- 금시연(예약 관련 기능 구현)
1. 예약하기 체크인, 체크아웃 날짜 선택(예약 불가능한 날짜 비활성화)
2. 숙소, 멤버, 결제상태 관련 정보 추가
3. 이용 완료된 예약에 한해서 예약 상세 페이지에 리뷰 등록 버튼 추가
- 김경환(결제 관련 기능 구현)
1. 포인트 결제
2. 캐시 사용 상세 내역
3. 토스페이먼츠 구현, 토스페이먼츠와 포인트 결제 연결
- 배현준(회원 관련 기능 구현)
1. 회원가입 필드 Validation
2. 비밀번호 찾기
3. 프로필 이미지 추가
- 이유현(숙소 리뷰 기능 구현)
1. 리뷰 삭제 구현(백엔드, 프론트엔드)
2. 리뷰 상세, 수정(백엔드)
3. 호텔, 예약 정보 추가
- 정주영(마이페이지 관련 기능 구현)
1. 예약 내역 상세페이지 연결
2. 내가 찜한 숙소 목록
3. 내 정보 수정(닉네임, 프로필 이미지 변경)
4. 예약 내역에서 예약 상황(이용 예정, 취소, 이용 완료) 반영
</br>

## 팀 내부 회의 진행 회차 및 일자

- 1회차 - 2024.01.29(월), 디스코드 음성채널 진행, 전원 참석
- 2회차 - 2024.01.30(화), 디스코드 음성채널 진행, 전원 참석
- 3회차 - 2024.01.31(수), 디스코드 음성채널 진행, 전원 참석
- 4회차 - 2024.02.01(목), 디스코드 음성채널 진행, 전원 참석
- 5회차 - 2024.02.02(금), 디스코드 음성채널 진행, 전원 참석

</br>

## 현재까지 개발 과정 요약

1. 숙소 CRUD
   - 목표달성률 : 90%
   - 호텔 CRUD, 찜하기 구현
2. 예약 기능 
   - 목표달성률 : 90%
   - 예약하기, 예약 상세 페이지 구현
   - 예약 체크인, 체크아웃 날짜 정보 추가 
3. 결제 기능
   - 목표달성률 : 90%
   - 포인트 결제, 토스페이먼츠 결제, 복합 결제 구현
5. 회원 기능 
   - 목표달성률 : 90%
   - 로그인, 회원가입, 로그아웃 기능 구현 완료(JWT)
   - 소셜 로그인 기능 구현 완료(카카오, 구글, 네이버)
   - 회원가입 폼 validation 및 필드 추가 중
6. 숙소 리뷰 기능 
   - 목표달성률 : 90%
   - 리뷰 등록, 조회, 삭제 구현
7. 마이페이지 기능 
   - 목표달성률 : 90%
   - 회원 정보 수정 구현
   - 예약 내역 구현, 예약 관련 진행 상황 반영
8. 배포
   - 목표달성률 : 100%
   - 프론트엔드: Vercel, 백엔드: NCP 로 배포 완료

</br>

## 개발 과정에서 나왔던 질문

1. Entity에 Builder를 사용하면 더티 체킹으로 수정 사항이 DB에 반영되지 않나요?
   - Builder를 사용하면 더티 체킹으로는 수정사항이 반영되지 않고 save를 따로 호출해야 합니다.
   더티 체킹을 위해서는 엔티티에 update 메소드를 만들고 그것을 활용하는 것이 좋을 듯 합니다.

2. Entity에 Setter를 되도록이면 사용하지 않아야 하는 이유가 뭔가요?
   - Entity에 Setter를 사용하면 실수로 Entity.set(잘못된 값) 이런식으로 잘못된 값을 넣었을 경우 문제가 생기기 때문에 방어적으로 DB를 관리하기 위해서 Entity에는 Setter를 넣지 않는 것이 일반적입니다.
    

</br>

## 개발 결과물 공유

[프론트엔드](https://github.com/BES-HOTSIX/HOTSIX_FE)

[백엔드](https://github.com/BES-HOTSIX/HOTSIX_BE)

[6팀 노션](https://www.notion.so/6-6d76a8dca3b148a3ba72afe1a2ec23ea)

![6팀1](https://github.com/BES-HOTSIX/Docs/assets/96820952/758d256b-9579-4184-b31c-4b3d2bf65e8c)
