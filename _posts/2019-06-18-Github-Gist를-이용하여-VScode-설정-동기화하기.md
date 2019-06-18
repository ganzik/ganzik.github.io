---
title: "Github Gist를 이용하여 VScode 설정 동기화하기"

date: 2019-06-18

related: false

comments: true

read_time: false

toc: true
toc_sticky: true

categories:
  - VScode
tags:
  - VScode
  - Visual Studio Code
  - Github
---

Github Gist를 이용하여 여러기기에 VScode Extention을 공유하는 방법에 대해 알아보자

## Settings Sync

<https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync>

VScode Extention중 하나인 Settings Sync 마켓플레이스 공식 페이지이다. 설치와 관련된 자세한 설명을 볼 수 있다.

설치와 사용하는 방법을 간단하게 요약하면 아래와 같다

## VScode에서 Extention 설치하기

Extentions(ctl+cmd+x) -> code-setting-sync

## Github Personal Access Token 생성하기

GitHub 계정의 Personal Access Token을 이용해서 gist를 업로드, 다운로드하여 동기화하기 위해 토큰을 생성

![generate new token](/assets/images/gist_1.png)
GitHub 계정 로그인 > Settings > Developer settings> Personal Access Tokens > Generate New Token

![check gist](/assets/images/gist_2.png)
토큰 사용 용도로 gist를 체크

![generated new token](/assets/images/gist_3.png)
생성된 토큰은 복사해서 보관

## 셋팅값을 Gist에 업로드

Shift + Alt + U

VScode Output에 Gist Id가 생성된다

CODE SETTINGS SYNC UPLOAD SUMMARY  
Version: 3.2.9

GitHub Token: ~~~  
GitHub Gist: ~~~  
GitHub Gist Type: Secret

## 다른 기기에서 Gist에 업로드된 셋팅값 다운로드하기

Shift + Alt + D
