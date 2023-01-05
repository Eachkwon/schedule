# Schedule Calendar 📆
![화면 캡처 2023-01-05 173203](https://user-images.githubusercontent.com/107821779/210736223-a00f577f-fcd8-4f76-95b9-2da45fa79d08.png)

## 프로젝트 소개
**Schedule을 통해 팀원 간의 스케줄을 관리하고 필요한 내용을 기록할 수 있습니다.**

📌 코드 생성 및 입력을 통한 '팀 가입 기능'

📌 팀원 간의 스케줄 공유가 가능한 '공유 캘린더 기능'

📌 할 일 목록, 기억해야 할 사항 등을 기록 가능한 '메모 기능'

## 팀원 소개
- 공상욱 조장
- 권유경 팀원
- 사상원 팀원
- 전인호 팀원

## Schedule Calendar 세부기능

#### [Membership and Login 기능]
-----------------------------
#### 1. 회원 가입
   * [ ID = username ]
   * [ PW = password, password2 ]

#### 2. 회원 가입 ID 중복 검사<br/>
   * ID 입력 받아 [db = username] 확인
   * true는 ID 사용, false는 재입력 
   
#### 3. 회원 가입 Password 이중 검사<br/>
   * PW 입력 받아 [db = password, password2 ] 확인
   * true는 사용, false는 [ 비밀번호가 일치합니다. ] 문구 출력
   
#### 4. 로그인 
   * ID | PW 입력 받아 [ db = username, password ] 확인
   * true는 main page 이동, false는 새로고침
<br/>

#### [Main Page 기능]
-----------------------------
#### 1. Main Calendar
   * 큰 사이즈로 중앙에 위치
   * 년, 월, 일 표준 달력으로 이동 및 사용 가능
   * 특정 날짜 선택 시 메모 기능 구현
   * 메모 발생 시 일정 표시 구현
   * 등록 및 삭제 구현 

#### 2. Second Calendar
   * 좌측 상단 작은 사이즈로 구현
   * Main Calendar와 똑같은 기능

#### 3. Calendar 동기화
   * [ Main Calendar ] [ Second Calendar ] 동기화 구현
   * 제목, 일시, 날짜, 인원, 세부내용 동기화 구현
   * 메모 발생 시 일정 표시 동기화 구현 
<br/>

#### [Modal 기능]
-----------------------------
#### 1. Popup
   * modal 사용하여 상태바, 주소창 제거
   * 자연스러운 popup 움직임 구현
   * Popup 창 밖 클릭시 닫힘 구현

#### 2. Popup Record
   * 제목, 구성원, 세부내용 text 방식 구현
   * 일시, 시간 목록 list에서 [ date | time ] 방식 구현
   * 확인 Popup 내용 Calendar에 저장
   * 닫기 Popup 내용 취소
<br/>

#### [Memo 기능]
-----------------------------
#### 1.Memo 기록  
   * text 타입으로 입력받아 기록 구현
<br/>

## 와이어프레임
![스크린샷 2022-06-23 오후 2 26 23](https://user-images.githubusercontent.com/100742282/175222004-a09bfb0f-ea29-487c-952d-74e25b4f655d.png)
