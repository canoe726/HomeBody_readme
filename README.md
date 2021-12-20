# HomeBody Application

<!-- PROJECT LOGO -->
</br>
<div
  align="center">
  <div
    align="center">
    <a
      href="https://play.google.com/store/apps/details?id=com.fitbuddy.homebody">
        <img
          src="https://user-images.githubusercontent.com/36183001/140261891-ce43893c-5879-4884-b74f-6fbbd18e82af.png"
          alt="Logo"
          width="120"
          height="120">
        </img>
    </a>
  </div>
  <h1
    align="center">HomeBody</h1>
  <h5
    align="center"> 🤜 지속적으로 운동을 즐길 수 있는 스마트 홈트레이닝 서비스 🤛</h5>
  </br>
  <img
    width="727"
    alt="시작 페이지"
    src="https://user-images.githubusercontent.com/48276633/140633978-f738af7b-0fc3-4b72-90d3-21fa1ea4b65b.png"/>
  </br>
  </br>
  <div
    align="center">
    <a
      align="center" href="https://play.google.com/store/apps/details?id=com.fitbuddy.homebody">
      <img
        alt="googleplay"
        width="150pixel"
        src="https://user-images.githubusercontent.com/46745325/106137351-f013d480-61ad-11eb-8751-5e8818ad4f74.png"></img>
    </a>
  </div>  
  <div
    align="center">
    <a
      href="https://git.swmgit.org/swm-12/12_swm21/HomeBody_Flutter/-/boards">Issue Board</a>
    ·
    <a
      href="https://git.swmgit.org/swm-12/12_swm21/HomeBody_Flutter/-/releases">Release Note</a>
    ·
    <a
      href="https://git.swmgit.org/swm-12/12_swm21/HomeBody_Flutter">Project</a>
  </div>
</div>
</br>
</br>

<!-- TABLE OF CONTENTS -->
## 목차

</br>

- [HomeBody 프로젝트](#homebody-프로젝트)
  1. [프로젝트 소개](#1-프로젝트-소개)
  2. [차별화 요소](#2-차별화-요소)
  3. [HomeBody 주요 기능 소개](#3-homebody-주요-기능소개)

</br>

- [서비스 구성도](#서비스-구성도)
  1. [기술스택](#1-기술-스택)
  2. [시스템 아키텍처](#2-시스템-아키텍쳐)
     - [전체 시스템 아키텍처](#전체-시스템-아키텍처-및-기능-명세)
     - [Flutter App 구조](#flutter-app-구조)
     - [백엔드 구조](#백엔드-구조)
     - [마케팅 및 분석](#마케팅-및-분석)
     - [협업 관리 도구](#협업-관리-도구)

</br>

- [업데이트 노트](#업데이트-노트)
  1. [V 2.0.0](#v-200)
  2. [V 1.0.0](#v-100)

</br>

- [프로젝트 성과](#프로젝트-성과)
  1. [유저 분석](#1-유저-분석)
      - [로얄 유저 분석](#1-로얄-유저-분석)
      - [운동 관련 지표 분석](#2-운동-관련-지표-분석)
      - [전체 사용자 정보](#3-전체-사용자-정보)
  2. [마케팅 분석](#2-마케팅-분석)
      - [광고 캠페인 최적화](#1-광고-캠페인-최적화)
      - [광고 수익화 측면](#2-광고-수익화-측면)

</br>

- [FitBuddy 팀](#fitbuddy-팀)

- [시연 영상](#시연-영상)

</br>

- [라이선스](#라이선스)

---

</br>

<!-- HomeBody 프로젝트 -->
## **HomeBody 프로젝트**

</br>

### **1. 프로젝트 소개**
<img
  width="726"
  alt="간단 소개"
  src="https://user-images.githubusercontent.com/48276633/140634016-90ef107f-c50a-43fd-a87b-904f6a173c71.png"/>
  
- 휴대폰 전면 카메라와 AI 기술을 활용한 운동 자세 자동 카운팅
- 랭킹 및 메달 시스템을 통한 운동 동기부여
- 운동 지표 그래프 제공

</br>


### **2. 차별화 요소**
<img
  width="726"
  alt="문제 해결"
  src="https://user-images.githubusercontent.com/48276633/140634105-217117c6-dfd3-4403-b620-c36bb50a8947.png"/>

- Blaze Pose 기반 ML Kit 을 사용하여 보다 정확한 운동 카운팅
- 지속적 운동을 위한 랭킹 시스템
- 운동 현황에 대한 리포트 제공



</br>

### **3. HomeBody 주요 기능소개**

- 모든 운동은 3가지 부위 중 하나에 속한다

> Full Body, Upper Body, Lower Body

</br>

#### **A. 단일 운동**

- 원하는 운동을 가볍게 즐기기 위한 운동

- 총 38종류의 운동 (AI 운동 10종, 일반 운동 28종)

</br>

![단일 운동](https://user-images.githubusercontent.com/36183001/140318558-7061d9b5-426c-4461-a52e-d4a860f4490d.png)

</br>

#### **B. 1일 루틴**

- 운동할 부위에 따른 루틴 구성

- 3가지 난이도, 12종류의 루틴

- AI 운동과 일반 운동의 조합으로 구성

</br>

![1일 루틴](https://user-images.githubusercontent.com/36183001/140318563-feb8c16f-71b5-4654-ba52-8c359bd257c8.png)

</br>

#### **C. 7일 루틴**

- 꾸준히 운동하고 싶은 사용자를 위한 루틴

- 운동 종료화면 도달 시 다음 날짜의 운동이 해금됨

- AI 운동의 조합으로 구성

</br>

![7일 운동](https://user-images.githubusercontent.com/36183001/140318553-912e3945-29dd-4866-955a-ecedb0e77c71.png)

</br>

#### **D. 랭킹 시스템**

- 수행한 운동 기록에 따라 부위별 점수 부여

- AI 운동 20점, 일반 운동 10점(횟수), 2점(시간)

</br>

<img
  width="568px"
  alt="랭킹시스템"
  src="https://user-images.githubusercontent.com/36183001/140318548-cd6e003e-7894-473b-ae93-acc293df3095.png"
/>

</br>

#### **E. 메달 시스템**


- 누적 운동 횟수, 운동 시간에 따라 메달 부여

- 총 10종류의 메달로 구성됨

</br>

#### **F. 알람 기능**


- 원하는 날짜 및 시간에 따라 알람 설정

</br>

![KakaoTalk_Photo_2021-11-04-22-06-03 005](https://user-images.githubusercontent.com/36183001/140318539-c40d8d3f-da3b-42f9-bed9-95b62a5e8ec0.png)

</br>

---

</br>

<!-- GETTING STARTED -->
## **서비스 구성도**

</br>

### **1. 기술 스택**

</br>

<img src="https://img.shields.io/badge/Java 11-e74c3c?style=flat-square&logo=Java&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=Dart&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=Gradle&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=Android&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=Flutter&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/GitLab-FCA121?style=flat-square&logo=GitLab&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/SourceTree-0052CC?style=flat-square&logo=SourceTree&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=Fastlane&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=VisualStudioCode&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/AndroidStudio-3DDC84?style=flat-square&logo=AndroidStudio&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Google Ads-4285F4?style=flat-square&logo=GoogleAds&logoColor=white"/>&nbsp;
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/>&nbsp;

</br>

- 마케팅 및 이벤트 추적 도구
  > OneSignal, Mixpanel, AppsFlyer, Google Ads, Google AdMob

- 사용한 툴
  > Google Ml-kit, Proguard, Firebase Crashlytice, Firebase Performance, Firebase RemoteConfig

</br>
</br>

### **2. 시스템 아키텍쳐**

</br>

#### **전체 시스템 아키텍처 및 기능 명세**

</br>

```text
HomeBody 애플리케이션의 전체 시스템 아키텍처와 기능 명세는 다음과 같다.
```

</br>

> 전체 시스템 아키텍처

<img
  width="768px"
  alt="전체 시스템 아키텍처"
  src="https://user-images.githubusercontent.com/48276633/140643046-3cb43852-50c6-4027-abf7-f8364adf2908.png">

</br>
</br>

> 전체 기능 명세

<img
  width="768px"
  alt="전체 기능 명세"
  src="https://user-images.githubusercontent.com/48276633/140634091-8c42bc38-fe47-4b39-aff4-48cb47c829a8.png">

</br>

#### **Flutter App 구조**

</br>

```text
1. On-Device에서 ML-Kit을 통한 운동 동작 카운팅
2. Provider를 통한 앱 내 상태 관리
```
</br>
<img
  width="768px"
  alt="Flutter App 구조"
  src="https://user-images.githubusercontent.com/48276633/140642984-ef072ba1-0155-4182-b76f-5b0f873f4e6d.png">

</br>

#### **백엔드 구조**

</br>

```text
1. Spring Boot를 이용한 REST API
2. AWS로 인프라 구축
```

</br>
<img
  width="768px"
  alt="백엔드 구조"
  src="https://user-images.githubusercontent.com/48276633/140634200-5b024daa-d3c2-47d6-9625-15117f1a720f.png">

</br>

#### **마케팅 및 분석**

</br>

```text
1. 앱 내 이벤트 발생 시 연동된 플러그인으로 로그 전송
2. 광고 캠페인을 통한 유저 획득
3. 코호트 분석을 통한 전략적 업데이트 및 푸쉬 생성
```

</br>

<img
  width="768px"
  alt="마케팅 플로우"
  src="https://user-images.githubusercontent.com/48276633/140650010-d5dc64bc-98a6-46fa-8768-3256188a19b2.png">

</br>

#### **협업 관리 도구**

</br>

```text
1. 이슈관리를 통한 개발 내역 추적 가능
2. 깃플로우를 사용하여 코드 단위 관리
```

</br>

<img
  width="470px"
  alt="협업 관리 도구1"
  src="https://user-images.githubusercontent.com/48276633/140634127-f7aa03b3-528d-4b52-ad74-e40a73915362.png">&nbsp;&nbsp;<img
  width="470px"
  alt="협업 관리 도구2"
  src="https://user-images.githubusercontent.com/48276633/140634131-94024b01-1201-4bb3-bd52-f76d213c03b7.png">

</br>
</br>

---

</br>

<!-- 업데이트 노트 -->
## **업데이트 노트**

</br>

## **V 2.0.0**

---

</br>

### **V 2.5.0** (21.10.28)

<details>
  <p>

    1. 랭킹 페이지 추가
      - API 데이터 로컬 캐쉬, 리프레쉬 기능 추가
    
    2. 모든 운동에 팁 음성 추가
      - AI 가 아닌 운동
        (1) 운동 시작 후 15초마다 백그라운드로 팁 생성 

      - AI 인 운동일 경우 음성 나오는 로직
        (1) 시작, 끝 4초는 음성이 나오지 않게 설정
        (2) 40초 이상일 경우 팁 3가지, 그렇지 않으면 팁 2가지 재생
        (3) 팁 사이 재생 간격이 5초 이상이면 팁 재생

    3. 바텀 네비게이션 크기 조정
    
    4. 메인 탭 하단 배너 광고 추가
      - 보상형 광고 시청 시 메인 광고 배너도 제거
    
    5. 운동 메인 탭 상단바 부분 보상형 광고 아이콘 추가
    
    6. A/B 테스트 코드 제거
      - 광고 영상 보여주는 것으로 설정
      - 강제로 로그인하도록 하지 않고 첫 세션 때만 로그인 화면 생성
      - 운동 시작 전 영상을 이미지로 변경
    
    7. 운동 시작 시 음성이 꼬이는 문제 해결
      - 이미 선언된 클래스를 스레드에서 재정의하여 사용해 문제 발생
    
    8. 앱 로고 색상 변경
  </p>
</details>
</br>

### **V 2.4.0** (21.10.22)

<details>
  <p>

    1. 앱 전체 디자인 리뉴얼
    
    2. A/B 테스트 분석을 위한 사용자 그룹 믹스패널 Register 코드 적용
    
    3. Post API 데이터 형태 수정
      - AI 운동인 경우
        (1) value 값은 AI 운동을 N회 수행한 횟수를 보낸다
        (2) goal 값은 싱글/루틴에서 설정한 운동 목표 값을 보낸다    

      - AI 운동이 아닌 경우
        (1) value 값은 카메라가 켜지고 종료되는 시간 차이 값을 보낸다
        (2) goal 값은 반복 수행인 경우 (1회 수행 평균 * 전체 목표 횟수), 시간인 경우 (목표 시간) 값을 보낸다
    
    4. 운동 목록 리스트 화면에서 광고 위치 변경
      - 리스트 사이 배너가 아닌 항상 하단에 위치하도록 변경
  </p>
</details>
</br>

### **V 2.3.0** (21.10.22)

<details>
  <p>

    1. 믹스패널 이벤트 로그 추가 및 리팩토링
       
    2. 인 앱 메시지로 리뷰 유도
      - AI 운동 10회 이상, 앱 세션 시간이 5분 이상 사용자 대상
       
    3. 앱 A/B 테스트 수행
      - Firebase Remote Config 사용
      - 실험 1 : 로그인 강제 테스트
      - 실험 2 : 전면 광고 표시 여부 테스트
      - 실험 3 : 운동 준비 사진 및 동영상 비교 테스트
       
    4. 서버와 Post 데이터 주고받기
      - Firebase Auth 토큰 값 사용
 
    5. 광고 재생 후 AI 운동 화면이 2번 뜨는 문제 해결
       - 앱 생명주기와 타이머 트리거로 인해 발생한 문제 해결
       
    6. 운동 할 때 음성 추가
      - 운동 시간 절반 도달 시 (half time) 음성 추가
      - 운동 카메라 화면 활성화 시 (start + 운동 이름) 음성 추가
      - 운동이 끝나서 준비화면 이동 시 (take a rest) 음성추가
      - 빠르게 화면 이동 시 싱크가 물리는 현상 해결
  </p>
</details>
</br>

### **V 2.2.0** (21.10.22)

<details>
  <p>

    1. 루틴 운동 화면에 운동 진척도 보여주기
       - 현재 운동이 몇번째 운동인지 프로그레스바를 통해 표시
       
    2. 리워드 광고 기능 만들기
       - AdMob 보상형 광고 단위 생성
       - 1회 영상 시청 시 12시간 전면광고 제거 리워드 제공
       
    3. Fastlane CI / CD
      - 플레이스토어 배포 자동화
       
    4. OneSignal 맞춤형 메시지
      - 유저 태그 보내기
      - 세그먼트에 해당하는 사용자에게 자동으로 푸시 설정
       
    5. 운동 관련 이벤트 로그 수정
      - 운동 수행, 운동 스킵, 운동 종료 등
  </p>
</details>
</br>

### **V 2.1.1** (21.10.22)

<details>
  <p>

    1. 원하는 요일, 시간에 알람 기능이 되도록 업데이트
      - 알람 별 id 다르게 설정하여 에러 수정
  
    2. 앱 첫 세션시 알람 설정 팝업 생성
    
    3. FCM dependency 추가
      - 앱 푸시 생성
    
    1. 페이스북 광고 미디에이션 코드 추가
      - 앱 광고 실적 개선
    
    2. 버그 및 에러 해결
      - 광고 실행 후 운동화면 2번 활성화
      - 메달 획득 시작 시간, 끝 시간 계산 로직 수정
      - hign_knee → high_knee 이미지 이름 변경
    
    3. 운동 끝 화면에서 수행한 시간 및 AI 운동 횟수 정보 표시
  </p>
</details>
</br>

### **V 2.1.0** (21.10.22)

<details>
  <p>

    1. 1일 루틴 기능 추가
      - 각 부위별 3개 종류로 총 12개 1일 루틴을 제작하여 기능 추가
    
    2. 광고 노출 범위 변경
      - 배너 광고 : 운동 리스트 화면, 운동 쉬는 시간 하단
      - 전면 광고 : 짝수 번 앱 세션 마다 메인 화면에서 출력, 루틴 운동 
      시작 짝수 번 마다, 운동 끝 화면에 도달 시
    
    3. 앱 디자인 개선
    
    4. 구글 로그인 기능 추가
   
    5. 프로필 탭에 로그인 정보 출력 및 로그아웃 기능 추가
  </p>
</details>
</br>

### **V 2.0.0** (21.10.22)

<details>
  <p>

    1. 안드로이드 네이티브 앱을 플러터 앱으로 전환 후 배포
      - AI 운동 카메라는 Method Channel을 통해 네이티브에서 처리
  </p>
</details>
</br>

</br>

## **V 1.0.0**

---

</br>

### **V 1.0.10** (21.08.04)

<details>
  <p>

    1. 운동 추가 (하이니즈, 숄더프레스, 손머리위로올리기, 점핑잭)
    2. 운동 개선 (레그레이즈, *크런치)
    3. 단일 운동 탭에 운동 4개 추가
    4. AppsFlyer 연동 (Google Ads, Google AdMob, Mixpanel)
    5. 버그 핫픽스
  </p>
</details>
</br>

### **V 1.0.9** (21.07.27)

<details>
  <p>

    1. 서서하는 루틴 추가
    2. DB 구조 개선 및 적용
    3. 버그 핫픽스 (알람 설정)
  </p>
</details>
</br>

### **V 1.0.7&#126;8** (21.07.24)

<details>
  <p>

    1. 운동 개선 (런지)
    2. 네비게이션바 알람 설정 기능 추가
    3. OneSignal 유저 태그 설정
    4. Assets 데이터 구조 적용, DB 구조 개선 및 적용
    5. 운동 프로그레스바 적용
    6. 버그 핫픽스 (프로가드 ↔ ObjectMapper)
  </p>
</details>
</br>

### **V 1.0.5&#126;6** (21.07.17&#126;18)

<details>
  <p>

    1. 운동 추가 (사이드 니업)
    2. 단일 운동 기능 추가
    3. 푸쉬업 완화
    4. 버그 핫픽스
  </p>
</details>
</br>

### **V 1.0.4** (21.07.10)

<details>
  <p>

    1. 운동 추가(어깨게이터, 사이드니업) 및 완화(푸시업)
    2. 운동 리스트 파이어베이스 연동
    3. 운동 개수 조절
    4. 운동 순서 조절
  </p>
</details>
</br>

### **V 1.0.3** (21.07.04)

<details>
  <p>

    1. How To Use UI 개선
    2. 카메라가 켜진 후 5초간 운동 준비 크로마키 그림 표시
    3. 운동 next, prev 버튼 → 운동 SPIK 버튼
    4. 음성 추가
        - 운동 준비 화면 시작전 3, 2, 1 초 음성
        - 운동 준비 화면 SKIP 버튼 휘슬 효과음
        - 운동 자동으로 넘어가면 환호 효과음
    5. 광고 배너 추가
        - 메인 화면 뒤로가기 (중간)
        - 메인 화면 하단 (배너)
        - 운동 준비 화면 하단 (배너)
        - 운동 준비 화면 뒤로가기 (중간)
        - 운동 중 뒤로가기 (중간)
        - 운동 끝 광고 (전면)
    6. 메인 화면 네비게이션 드로어 추가
        - How To Use (슬라이더)
        - Contact (바로 이메일 앱으로 연결)
        - Open Source License
    7. 믹스패널 User 식별 기능 추가
  </p>
</details>
</br>

### **V 1.02** (21.06.27)

<details>
  <p>

    1. Mixpanel 에서 완료한 운동 개수 정보 오류 수정
    2. 메인_사용법_화면, 메인_화면으로 이동시 로그 보냄
    3. 전체적인 UI 개선
    4. 권한 거부시 발생하는 문제 해결 중
        - 앱 실행 중에 설정화면에서 권한 거부시 앱 크래쉬
        - 모두 승인하면 정상작동
    5. 프로그레스바 동기화 문제 해결
    6. Great 음성 중간에 끊기는 문제 해결
    7. 운동 카운트 세는 알고리즘 V1.01 로 원복
  </p>
</details>
</br>

---

<!-- 프로젝트 성과 -->
## **프로젝트 성과**

### **1. 유저 분석**

</br>

#### **(1) 로얄 유저 분석**

</br>

_`로얄유저 - 앱 세션시간 5분 이상, 운동 수행 10회 이상`_

</br>

```text
- 믹스패널에 집계된 전체 사용자 대비 로얄 유저의 비율은 약 6% (318/5,199)로 집계된다.

- PlayConsole 기준 활성 사용자 수 대비 로얄 유저의 비율은 약 8% (318 / 3,886)
```

<img
  width="768px"
  alt="앱 내 로얄 유저 비율"
  src="https://user-images.githubusercontent.com/36183001/140320377-00408a4d-6675-4742-8dcf-b8cb9b600baf.png"
/>

</br>

```text
- 전체 사용자의 총 운동 수행 누적 횟수는 23,782회이다.

- 총 운동 수행 횟수 대비 로얄 유저의 운동 수행 횟수 비율은 약 87%로 집계된다.
```

<img
  width="768px"
  alt="로얄 유저 운동 수행 누적 횟수"
  src="https://user-images.githubusercontent.com/36183001/140320253-b4532e8b-a6a4-4c4a-9865-33465e877e20.png"
/>

</br>

```text
- (로얄 유저)의 운동 종료 화면 도달 비율은 81%이다.

- (운동 수행 50회 이상 수행한 유저)의 운동 종료 화면 도달 비율은 93%이다.

- V1.0.0 버전 기준 로얄 유저와 비교 하였을 때 최대 3.5배 증가하였다.
```

<img
  width="768px"
  alt="로얄 유저 운동 수행 퍼널"
  src="https://user-images.githubusercontent.com/36183001/140319574-d6665ed7-ca4a-4cee-9f08-f37c12d7c6e3.png"
/>

</br>

#### **(2) 운동 관련 지표 분석**

</br>

```text
- 난이도가 낮은 7일 운동, 가볍게 즐길 수 있는 단일운동, 복근운동 위주의 루틴이 사용량이 가장 높다 
```

<img
  width="768px"
  alt="루틴별 이벤트 수행 분포"
  src="https://user-images.githubusercontent.com/36183001/140321754-2cb8ecfd-4f18-4013-b90f-be6dc8b901d3.png"
/>


</br>

```text
- AI 운동이 일반 운동보다 사용량이 월등히 높다.

- 어디서든 가볍게 운동할 수 있는 운동이 많이 실행되었다. 
```

<img
  width="768px"
  alt="운동 별 수행 분포"
  src="https://user-images.githubusercontent.com/36183001/140321780-36d36d34-8d9a-46e6-a69e-6310158bd52c.png"
/>

</br>

#### **(3) 전체 사용자 정보**

</br>

```text
- 상위 활성 사용자 국가 순위는 인도, 미국, 파키스탄 순이다.
```

<img
  width="768px"
  alt="국가별 앱 사용자 분포"
  src="https://user-images.githubusercontent.com/36183001/140322129-024509ca-8143-418d-a75f-a8ebf5fedd81.png"
/>

</br>

```text
- 사용자의 앱 평균 사용 시간은 4~6분을 기록하였다.
```

<img
  width="768px"
  alt="앱 평균 사용시간"
  src="https://user-images.githubusercontent.com/36183001/140322519-cd6acb92-5c9b-4a23-bd19-2979247fa292.png"
/>

</br>



### **2. 마케팅 분석**

</br>

#### **(1) 광고 캠페인 최적화**

</br>

- 앱 설치 수량 캠페인-1

```text
- 전세계 대상 평균 설치 CPI는 $0.07이다.

- 타겟되는 상위 국가는 인도, 파키스탄과 같은 국가이다. 
```

<img
  width="768px"
  alt="GoogleAds - 앱 설치 수량 캠페인-1"
  src="https://user-images.githubusercontent.com/36183001/140322030-15ab5713-a02f-497a-b747-5bf29f795e99.png"
/>

</br>

- 북미 타겟 앱 설치 전환 캠페인 (운동_진입 전환)

```text
- CPI가 높은 상위 4개 국가 대상 캠페인이다. (미국, 캐나다, 영국, 호주)

- 평균 CPI는 약 $1.3이며, (운동 시작) 액션 전환비용은 약 $2이다.
```

<img
  width="768px"
  alt="GoogleAds - 북미 타겟 앱 설치 전환 캠페인 (운동_진입 전환)"
  src="https://user-images.githubusercontent.com/36183001/140322038-c9b03413-09eb-4d16-a8a6-2867a1d5e009.png"
/>

`운동 시작은 운동 수행하기 전 카메라가 수행되는 이벤트를 뜻한다.`

</br>

```text
- CPI가 높은 상위 4개 국가 대상 캠페인이다. (미국, 캐나다, 영국, 호주)

- 평균 CPI는 약 $1.3이며, 인앱 액션 전환비용은 약 $6이다.

- 가장 높은 로얄 유저로의 전환을 보인다.
```

<img
  width="768px"
  alt="GoogleAds - 북미 앱 설치 전환 캠페인 CPI 1 05 (운동_수행)"
  src="https://user-images.githubusercontent.com/36183001/140322042-d3a9766f-266d-494f-b7af-6f771578fcef.png"
/>

`운동 수행은 카메라를 통해 실제 운동을 수행하는 이벤트를 뜻한다.`

</br>

#### **(2) 광고 수익화 측면**

</br>

```text
- V 2.0.0에서 운영하는 광고 단위는 배너, 전면, 보상형 광고이다.

- 총 호출 횟수는 약 71,200회이며 21.11.02일 기준 $67의 수익을 기록하였다.
```

<img
  width="768px"
  alt="전체 광고 노출 횟수"
  src="https://user-images.githubusercontent.com/36183001/140322685-17377c97-80e2-471b-b383-58e277a2d5e0.png"
/>

</br>

```text
- 국가별 eCPM 보고서를 통해 향후 앱 UI/UX, 캠페인 업데이트 방향을 결정할 수 있다.

- 많은 광고 호출이 발생하였으며 eCPM이 높은 국가는 미국, 영국, 캐나다가 있다.
```

<img
  width="768px"
  alt="국가별 광고 eCPM"
  src="https://user-images.githubusercontent.com/36183001/140322137-0949fb66-c222-4a26-b4cf-5ec49f3cb1f3.png"
/>

</br>

---

</br>

<!-- Fitbuddy 팀 -->
## FitBuddy 팀

</br>

### **Team21** - **FitBuddy** 팀 구성

<img
  width="120px"
  height="120px"
  alt="kim"
  src="https://user-images.githubusercontent.com/36183001/128629759-9a5f4191-607f-47cf-9b01-ba6675b855f5.png"></img>

> [김영배](https://github.com/canoe726) | 프론트엔드 앱 개발, 앱 마케팅

<img
  width="120px"
  height="120px"
  src="https://user-images.githubusercontent.com/36183001/128629756-e8206c17-2bee-46b0-bf70-0444be82ed49.png"></img>

> [이주원](https://github.com/wndnjs9878) **(팀장)** | 백엔드 개발, 시스템 아키텍처 설계

<img
  width="120px"
  height="120px"
  src="https://user-images.githubusercontent.com/36183001/128629760-896aa556-8770-49b2-8c0a-8e097b60855e.png"></img>

> [이태민](https://github.com/koalakid1) | 백엔드 개발, AI 운동 모델 개발

</br>

---

</br>

## 시연 영상 ###
[![Video Label](https://user-images.githubusercontent.com/48276633/140654930-ee11238e-88f3-452f-9322-0fc3484dd8ee.png)](https://youtu.be/mmIIc3WuqM4) 

- Single Exercise 
  https://youtu.be/clA6Nb2KaP4 <br>
- 1 Day Routine & Getting Medal 
  https://youtu.be/-ryPfkqeQQM <br>
- 7 Days Routine & Getting Medal 
  https://youtu.be/rHmG38GZqu8 <br>
- Ranking System 
  https://youtu.be/qHxAUwidWSY <br>
- Profile System 
  https://youtu.be/a5VvjPx5H94 <br>

</br>

<!-- LICENSE -->
## **라이선스**

</br>

> Distributed under the MIT License. See `LICENSE` for more information.

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- [contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/SWM12TH-FitBuddy/repo.svg?style=for-the-badge
[issues-url]: https://github.com/SWM12TH-FitBuddy/homebody_app/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[playstore-shield]: https://img.shields.io/badge/-GooglePlay-black.svg?style=for-the-badge&logo=googleplay&colorB=555
[playstore-url]: https://play.google.com/store/apps/details?id=com.fitbuddy.homebody -->

