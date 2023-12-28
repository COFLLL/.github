<div align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FCorporationOverFlow&count_bg=%23ED6DA3&title_bg=%2386757E&icon=github.svg&icon_color=%23E1DEDE&title=Hits&edge_flat=false"/></a>
</div>

# 🚀 CoverFlow를 소개해요
## 💡 CoverFlow
```
    Corporation + OverFlow
    기업에 대한 질문과 답변이 넘쳐흐르는 서비스를 뜻합니다
```
사진

## 💻 기술 소개
### 🎉 프론트엔드
사진

### 🎉 백엔드
사진

### 🎉 Project Architecture
사진

## 🎁 팀원 소개
<table>
  <tr>
    <td align="center"><strong>프론트엔드</strong></td>
    <td align="center"><strong>백엔드</strong></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/raxchaz"><img src="https://avatars.githubusercontent.com/raxchaz" width="150px;" alt="">
    <td align="center"><a href="https://github.com/fakerdeft"><img src="https://avatars.githubusercontent.com/fakerdeft" width="150px;" alt="">
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/raxchaz"><b>raxchaz(라현지)</b></td>
    <td align="center"><a href="https://github.com/fakerdeft"><b>fakerdeft(조만제)</b></td>
  </tr>
</table>
        
<br>
        
# 🚀 이렇게 일하고 있어요
### ✅ 데일리 미팅으로 하루를 시작해요
- 평일 9시 (최대 30분)
- 간단한 진행 상황 및 작업 이슈 브리핑

### ✅ 회고로 일주일을 마무리해요
- 매주 금요일 20시
- 기술회고와 감정회고 진행

### ✅ 멤버들의 시간은 소중해요
- 사유 없는 지각 시, 벌금 1000원

### ✅ 기약 있는 회의가 좋아요
- 안건 별 진행 시간 지정
- 쉬는 시간은 유동적으로 결정

### ✅ 의견 충돌은 유연하게 대처해요
- 모두가 동의할 수 있는 충분한 논의
- 반대 의견이 있을 시 구체적인 이유와 대안을 제시
- 의사 결정 방법은 **과반수로** 결정

### ✅ 의사소통 이렇게 해요
- 9시에서 5시 사이의 소통을 적극 활용
- 메시지 확인했다면, 이모지 남기기

### ✅ 함께 성장해요
- 새로 배운 내용이나 모르는 내용을 공유하고 기록
- 이슈에 대한 고민은 Who가 아닌 Why

<br>

# 🚀 약속은 꼭 지켜요
## 🌭 Branch Strategy
### ✏ Git Repository
사진

### ✏ Organization
- Git Repository를 팀원들과 사용하기 위해 GitHub에서 제공하는 협업 서비스이다
- 소속된 Repository를 Upstream Remote Repository(최신 소스코드 저장소)로 사용한다

### ✏ Branch Naming
```
type/#이슈번호 + (선택)설명       ex)feature/#22-delete-image
```
- type
  - main: 실제 운영 브랜치
  - develop: 다음 버전 개발 브랜치
  - feature: 기능 개발 브랜치
  - hotfix: 버그 수정 브랜치

## 🍕 Commit Message Convention
### ✏ 메시지 형식
```
type: subject                    ex)feat: 이미지 삭제 구현
(선택)body                          - 특정 이미지를 삭제하기 위해 구현했습니다.
                                    - 전체 이미지를 삭제하기 위해 구현했습니다.
```
- type
  - feat: 기능 추가
  - fix: 기능 변경 o 코드 수정 o
  - refactor: 기능 변경 x 코드 수정 o (버그 픽스나 기능 추가 없는 코드 변화)
  - style: 코드의 의미가 변경 안 되는 경우 (띄어쓰기, 포맷팅, 줄 바꿈 등)
  - chore: 기능 변경 x 코드 수정 x
  - test: 테스트 코드 추가/수정
  - design: CSS 등 사용자 UI 디자인 변경 [FE]

- subject
  - 제목은 50글자를 넘지 않도록 한다.
  - 개조식 구문 사용
    - 중요하고 핵심적인 요소만 간추려서 (항목별로 나열하듯이) 표현
  - 마지막에 특수문자를 넣지 않는다. (마침표, 느낌표, 물음표 등)

- body(선택)
  - 각 라인별로 balled list로 표시한다.
    - 예시) - 어쩌구~
  - 본문의 양에 구애받지 않고 최대한 상세히 작성한다.
  - “어떻게”보다는 “무엇을" “왜” 변경했는지 설명한다.

## 🍔 Issue & PR Guide
```
- 개발 전 Issue 발행 우선
- Issue는 태스크 단위로 발행하기
- Git Convention을 반드시 지키기
- 각자 Branch에서 개발 후 develop Branch로 PR하기 (develop, main으로 push 금지)
- PR에 댓글 적극적으로 남기기
- 최소 한 명 이상의 PR승인이 이루어져야 Merge 가능
```

### ✏ Issue 형식
#### Feature
```
---
name: "[Feature]"
about: 기능 개발 이슈
title: "[Feature] - [도메인] 제목"
labels: ''
assignees: ''
---
    
## ✏️Description
- <!--작업사항을 입력해주세요-->

## ✅TODO
- [ ] <!--todo-->
- [ ] <!--todo-->
- [ ] <!--todo-->

## 🐾ETC
```
#### Bug
```
---
name: "[BugFix]"
about: 버그 관련 이슈
title: "[BugFix] - [도메인] 제목"
labels: ''
assignees: ''
---

## 🗺️Location
- <!--버그 발생 위치-->

## 🤷WHAT
- <!-- 어떤 문제가 발생했는지 -->

## ✏️HOW
- <!-- 어떻게 해결했는지 -->

### ✅TODO
<!-- (선택) 간단한 설명 적어주심 착한사람! -->
- [ ] <!-- todo -->

### 🐾ETC
```
### ✏ Pull Request 형식
#### 제목
```
[type] - [도메인] 제목
    
type
- Feature
- BugFix
```
#### 본문
```
## ✨이슈 번호
<!-- 이슈 번호는 꼭 적어주세요. -->
ex) *closed #000

## ✏️내용

## 📸스크린샷

## 🎁참고사항
```
