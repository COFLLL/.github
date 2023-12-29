<div align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FCOFLLL&count_bg=%23FF8D1D&title_bg=%2386757E&icon_color=%23E1DEDE&title=Views&edge_flat=false"/></a>
</div>
사진
사진

# 📑 INDEX
- [CoverFlow를 소개해요](https://github.com/COFLLL#-coverflow를-소개해요)

- [우리는 이렇게 일하고 있어요](https://github.com/COFLLL#-우리는-이렇게-일하고-있어요)

- [전략적으로 형상을 관리해요](https://github.com/COFLLL#-전략적으로-형상을-관리해요)

<br>

# 🚀 CoverFlow를 소개해요
## 💡 CoverFlow
```
Corporation + OverFlow

기업에 대한 질문과 답변이 넘쳐흐르는 서비스를 뜻합니다
```
사진

## 🎁 코드 소개
🌌 [프론트엔드 저장소](https://github.com/COFLLL/CoverFlow-FE) <br>

🌌 [백엔드 저장소](https://github.com/COFLLL/CoverFlow-BE)

## 🎁 기술 소개
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
        
# 🚀 우리는 이렇게 일하고 있어요
![팀 문화](https://github.com/COFLLL/.github/assets/119282494/236b6260-f799-463a-830c-b8ea5301e68c)





<br>

# 🚀 전략적으로 형상을 관리해요
## 🔥 Branch Strategy
### ✏ Git Repository
![image](https://github.com/COFLLL/.github/assets/98208452/5cb94b5b-db42-4ad9-8219-33bd25235390)
```
우리는

Local Repository <-> Fork Remote Repository(Origin) <-> 원본 Repository(Upstream)

구조로 Git Repository를 관리합니다.
```
### ✏ Organization
- Git Repository 관리와 프론트엔드/백엔드 레포지토리 분리를 위해 Organization을 사용합니다.

- Organization에 소속된 Repository를 Upstream Remote Repository(최신 소스코드 저장소)로 사용합니다.

### ✏ Branch Naming
```
type/#이슈번호 + (선택)설명       ex) feature/#22-delete-image

[type]
- main: 실제 운영 브랜치
- develop: 다음 버전 개발 브랜치
- feature: 기능 개발 브랜치
- hotfix: 버그 수정 브랜치
```

## 🔥 Commit Message Convention
### ✏ 메시지 형식
```
type: subject                    ex) feat: 이미지 삭제 구현
(선택)body                           - 특정 이미지를 삭제하기 위해 구현했습니다.
                                     - 전체 이미지를 삭제하기 위해 구현했습니다.

[type]
- feat: 기능 추가
- fix: 기능 변경 o 코드 수정 o
- refactor: 기능 변경 x 코드 수정 o (버그 픽스나 기능 추가 없는 코드 변화)
- style: 코드의 의미가 변경 안 되는 경우 (띄어쓰기, 포맷팅, 줄 바꿈 등)
- chore: 기능 변경 x 코드 수정 x
- test: 테스트 코드 추가/수정
- design: CSS 등 사용자 UI 디자인 변경 [FE]

[subject]
- 제목은 50글자를 넘지 않도록 합니다.
- 개조식 구문 사용 -> 중요하고 핵심적인 요소만 간추려서 (항목별로 나열하듯이) 표현합니다.
- 마지막에 특수문자를 넣지 않습니다. (마침표, 느낌표, 물음표 등)

[body](선택)
- 각 라인별로 balled list로 표시합니다. ex) - 어쩌구~
- 본문의 양에 구애받지 않고 최대한 상세히 작성합니다.
- “어떻게”보다는 “무엇을" “왜” 변경했는지 설명합니다.
```

## 🔥 Issue & PR Guide
- 개발 시작 전, 우선 Issue를 발행합니다.

- Issue는 태스크 단위로 발행합니다.

- Git Convention을 반드시 지킵니다.

- 각자의 branch에서 개발 후 develop branch로 PR 합니다. (develop, main으로 push 금지)

- PR에 댓글을 적극적으로 남깁니다.

- 최소 한 명 이상의 PR 승인이 이루어져야 Merge가 가능합니다.

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
