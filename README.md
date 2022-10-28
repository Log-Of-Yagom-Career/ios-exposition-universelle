# 만국박람회 프로젝트

### 프로젝트 저장소
>프로젝트 기간 : 2022-10-17 ~ 2022-10-31<br>
소개: JSON 데이터를 활용하여 만국 박람회 전시작을 볼 수 있는 어플리케이션의 제작<br>
**리뷰어** : [**Tony**](https://github.com/Monsteel)

## 팀원
    
| Baem🐍 | Woong🫠 |
|:---:|:---:|
|[Github](https://github.com/Dylan-Yoon)|[Github](https://github.com/iOS-Woong)|
    


---

## 타임라인: 시간 순으로 프로젝트의 주요 진행 척도를 표시

### Week 1
- **2022-10-17(월)** - STEP1 PR
  - JSON 데이터를 토대로 인스턴스화 할 데이터 타입 작성
  - STEP1 Pull Request
 
- **2022-10-18(화)** - STEP1 Merged
  - STEP2에 필요한 내용 개인 공부
      - (TableView, JSON Data Handling)
  - expositionParis JSON 데이터 디코딩
  - 첫 번째 화면인 PosterView 구현

- **2022-10-19(수)** - STEP2 PR
    - 두 번째 화면인 EntryView 구현
        - TableView
        - Item JSON Decoding
    - 세 번째 화면인 DetailEntryView 구현
        - Segue를 이용해 데이터 전달
    - 기본적인 Layout구현

- **2022-10-20(목)**
    - 파일 분리
    - 개인 공부 및 리펙토링
  
- **2022-10-21(금)** 
  - `Readme.md` 작성

### Week 2
- **2022-10-24(월)**
    - 뱀 감기
- **2022-10-25(화)**
    - autolayout 설정
- **2022-10-26(수)** - Step2 Merged
- **2022-10-28(금)** - Step3 PR
    - `Readme.md` 작성
    - step3 마무리
---

## 프로젝트 내용

### 주요 기능

### 구현 기능


- **Controller**
    - PosterViewController.swift
    - EntryViewController.swift
    - DetailEntryViewController.swift
- **Models**
    - ExpositionParis.swift
    - Items.swift
    - JSONDecoder.swift
- **View**
    - EntryTableViewCell.swift
    - Main.storyboard
 
### 실행 화면

| PosterView | EntryView | DetailEntryView |
|:---:|:---:|:---:|
|![](https://i.imgur.com/bn7033z.png)|![](https://i.imgur.com/9bYn0K3.png)|![](https://i.imgur.com/3ArymCJ.png)|


| iPhone11 | iPhone8 | iPhone13mini |
|:---:|:---:|:---:|
|![](https://i.imgur.com/2FR8ZjY.gif)|![](https://i.imgur.com/624DoBa.gif)|![](https://i.imgur.com/tm3LvLY.gif)|




## 트러블슈팅
### [STEP 1 - 데이터 타입 정의]
[JSON 포멧 데이터 활용](https://github.com/Dylan-yoon/ios-exposition-universelle/wiki/기술적도전-&-트러블슈팅#%EF%B8%8F-tableview의-활용--tableviewcell)

### [STEP 2 - 화면 UI 구성]

[TableView의 활용](https://github.com/Dylan-yoon/ios-exposition-universelle/wiki/기술적도전-&-트러블슈팅#%EF%B8%8F-tableview의-활용--tableviewcell)
[화면 전환시 데이터 전달](https://github.com/Dylan-yoon/ios-exposition-universelle/wiki/기술적도전-&-트러블슈팅#-화면-전환시-데이터-전달)
[스크롤뷰 오토레이아웃](https://github.com/Dylan-yoon/ios-exposition-universelle/wiki/기술적도전-&-트러블슈팅#%EF%B8%8F-scrollview-오토레이아웃)

### [STEP 3 - 화면 UI AutoLayout 구성]
[Dynamic Type의 활용](https://github.com/Dylan-yoon/ios-exposition-universelle/wiki/기술적도전-&-트러블슈팅#%EF%B8%8F-accessibility-inspector의-활용)

---

## 참고 

### 참고한 페이지
[Apple Developer Document - Codable](https://developer.apple.com/documentation/swift/codable/)

[Cory의 블로그 - ScrollView AutoLayout](https://corykim0829.github.io/ios/UIScrollView-with-storyboard/#)

[Apple Developer Document - TableView](https://developer.apple.com/documentation/uikit/uitableview/)

[boost course의 yagom 강의](https://www.boostcourse.org/mo326/lecture/18732?isDesc=false)

[Apple Develioper Library_ autolayout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/AnatomyofaConstraint.html#//apple_ref/doc/uid/TP40010853-CH9-SW1)

[Accessibility Inspector (WWDC 2019)](https://developer.apple.com/videos/play/wwdc2019/257/)

[Writing Great Accessibility Labels (WWDC 2019)](https://developer.apple.com/videos/play/wwdc2019/254/)
