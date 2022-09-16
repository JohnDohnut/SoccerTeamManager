# SoccerTeamManagementSystem

## Purpose
~~~
  - 축구팀 구성원의 정보관리 시스템 개발
  - DB연동과 WAS를 통한 환경 구축
~~~


## Function
### 선수/팀/감독 별 정보 관리
~~~
  1. 사용자는 선수/감독으로 분류된다.
  3. 각 선수는 자신의 경기 정보를 관리한다.
  4. 각 감독은 자신이 속한 팀을 관리한다.
  5. 각 팀은 자신에게 속한 선수들을 가진다.
  
~~~
### 정보 관리 상세
~~~
  
  1. 선수의 정보에는 선수의 정보(선수의 이름, 선수의 고유번호 등), 소속된 팀과 선수의 경기 기록들이 기록된다.
  2. 팀의 정보에는 팀의 정보(팀의 이름, 팀의 고유번호 등), 선수와 선수의 포지션이 기록된다.
  3. 감독의 정보에는 감독의 정보(감독의 이름, 감독의 고유 번호 등)와 관리중인 팀들이 기록된다.
  4. 선수의 경기 기록은 선수의 팀, 상대 팀, 기록의 형태 로 나뉜다.
~~~

### 계정 관리
~~~
  1. 모든 선수는 오로지 한 팀에만 종속될 수 있다.
  2. 선수는 오로지 자신의 기록(이름, 경기기록) 만을 수정할 수 있으며 그 외의 정보는 조회만이 가능하다.
  3. 감독은 여러 팀을 관리할 수 있다.
  4. 
~~~

### 편의 기능
~~~
  1. 감독은 자신이 관리하는 팀의 각 선수에 대하여 메세지를 Broadcast 할 수 있다.
  2. 각 선수는 1. 과 같이 Broadcast를 할 수는 없지만, 1:1 Message를 전송할 수 있다.
  
~~~

## Tech
~~~
Apache Tomcat
Spring boot
MySQL
~~~
## Flow

![image](https://user-images.githubusercontent.com/51821505/190554199-51cca9ae-e9c1-49b2-b810-5486b1fe5074.png)

## DB Schema
