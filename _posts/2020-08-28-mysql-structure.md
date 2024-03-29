---
title: 'Mysql의 구조'
excerpt: 'Mysql의 구조에 대해 공부하도록 하겠습니다.'
categories: [Mysql]
tags: [Mysql]
last_modified_at: 2020-08-28T01:00:00-02:00
toc: true
toc_label: '목차'
sitemap :
changefreq : daily
priority : 1.0
---

<br>

**표(table)**

| id  | title    | description    | created  |
| --- | -------- | -------------- | -------- |
| 1   | 안녕     | 나는 안녕 .... | 2020-3-6 |
| 2   | 반가워요 | 나는 방가 .... | 2020-5-6 |

Table은 데이터의 기본 저장구조입니다..

## 1. 데이터베이스(database)?

위와 같이 생긴 `표(tablue)`들을 그룹핑한 것을 `데이터베이스(database)`라고 합니다.  
`MySQL`에서는 데이터베이스 라는 표현과 함께 `스키마(schema)`라는 표현도 함께 사용합니다.

## 2. 스키마(schema) ?

어떠한 웹을 운영하는데 사용되는 데이터들을 데이터베이스에 저장한다고 하면 <br>`글을 저장하는 표`, `회원정보를 저장하는 표`, `댓글을 저장하는 표` ... 등등 생기게 됩니다. <br>`스키마(schema)`는 여기서 나눠진 표(table)들을 서로 그룹핑할 때 사용하는 폴더라고 생각하면 됩니다.

## 3. 데이터베이스(database) == 스키마(schema)

결국 보면 `데이터베이스`와 `스키마`는 같은 의미입니다.

다른 데이터베이스 제품에서는 서로 다른 의미로 구별 되기도 합니다.<br>
예를 들어 `오라클`에서의 `schema`는 특정 `database`의 부분을 의미 합니다.
