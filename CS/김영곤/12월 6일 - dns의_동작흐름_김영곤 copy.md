# TIL - [DNS의 동작흐름]

## 📅 날짜
[2024-12-06]

---

## 📌 학습 키워드
- [DNS의 동작흐름]

---

## 📖 오늘 배운 내용

### 🔹 Keyword1: [DNS의 동작흐름]

1. 도메인이란

    네트워크에서 특정 주소에 요청을 보낼 때 숫자로 이루어진 주소는 사람이 기억하기가 상대적으로 힘들다. 이를 위해서 단어로 만든 주소이다.

    IPv4 : 111.111.111.111 -> domain : www.example.com

1. DNS란 Domain Name System

    도메인을 IP주소로 변경해주는 시스템이다.

1. DNS의 동작 흐름

    1. 클라이언트에서 ISP 네임서버로 요청
    2. ISP 네임서버에서 IANA로 요청 -> 최상위 네임서버 주소 응답
    3. 최상위 네임서버에 요청 -> 2차 네임서버 주소 응답
    4. 2차 네임서버에서 응답

    캐시가 있다면 위 과정을 안거치고 처리
---
