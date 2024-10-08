---
title: 리눅스프로그래밍 프로젝트
summary: 2023년 4월 - 2023년 6월
date: 2024-10-04
type: docs
featured: true
tags:
    - linux
---

2023년 1학기 리눅스프로그래밍 개인 프로젝트 

1개의 리눅스 운영체제에서 돌아가는 프로그램 개발하기

개요
- 파일을 요청해서 주고 받는 서버/클라이언트 프로세스 개발

서버
- 서버는 동작하는 동안, 클라이언트들이 요청하는 파일을 IPC-Socket을 통해 전송함
- 없는 파일(또는 잘못된 이름)을 요청한 경우, 실패 메시지 전달
- 서버는 요청받은 파일을 표준출력 하고, 해당 파일을 요청한 클라이언트에 전송해 줌
- 서버는 멀티 스레드 기반으로 설계하여, 복수 클라이언트들의 동시 요청을 처리할 수 있어야 함
- 별도의 종료루틴은 없음

클라이언트
- 클라이언트는, 실행시 argv[1]로 요청할 파일을 입력받음
- 서버에 연결해서, 파일을 요청하고 전송이 완료되면 프로세스를 종료함
- 없는 파일(또는 잘못된 이름)을 요청한 경우, 서버로부터 실패 메시지를 전달받으면, 이를 표준출력 해주고 종료함



### 결과보고서
{{< icon name="download" pack="fas" >}} {{< staticref "uploads/linux.pdf" >}} 다운로드{{< /staticref >}} 결과 보고서.
