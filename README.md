# 🎉 FestaPick
모두가 함께 만들어가는 축제 플랫폼

[![Website](https://img.shields.io/badge/Website-festapick.com-0ea5e9?logo=vercel&logoColor=white)](https://www.festapick.com)

---

//가운데 정렬(h3) + 이모티콘
**함께 즐기기고 함께 만드는 축제의 모든 순간** 
<img width="1536" height="1024" alt="KakaoTalk_Photo_2025-10-05-17-41-17" src="https://github.com/user-attachments/assets/f1c3b239-52a7-4329-accf-f17bb096b77e" />

//notion 

Festiapick 가이드북

## 2) 소개
FestaPick은 **축제 참여자**와 **축제 관리자(주최측)** 모두가 함께 쓰는 플랫폼입니다.  

- 축제별로 운영되는 채팅방을 통한 참여자간 정보 공유 💬
- 여행 MBTI 입력을 통한 사용자 맞춤 축제 추천
- 간편한 축제 등록 및 관리 지원
- 공지사항을 통해 빠른 정보 전달

---

## 3) 핵심 기능

### 👤 사용자 기능

---

#### 성향 기반 축제 맞춤 추천  

- 지도에 있는 **픽픽(PickPick)** 이를 선택해 지역을 설정하고, **여행 MBTI**를 입력하면 사용자의 성향에 맞는 축제를 추천받을 수 있습니다.  
- 추천받은 축제 중 마음에 드는 축제를 클릭하면 **상세 정보를 조회**할 수 있습니다. 


---

#### 좋아요 / 리뷰 작성  
- 마음에 드는 축제는 **좋아요**를 눌러 저장할 수 있습니다.  
- 다녀온 축제에 대해서는 **리뷰를 작성**해 다른 사용자와 경험을 공유할 수 있습니다.  


---

####  실시간 소통 (채팅)  
- 각 **축제별 채팅방**에서 참여자들과 실시간으로 정보를 공유할 수 있습니다.  
- **마이페이지**에서는 참여 중인 채팅방의 **알림 여부를 확인**할 수 있습니다.  


### 🧩 관리자 기능


#### 축제 관리자 등업 신청  
 - 축제를 직접 관리하고 싶다면 **관리자 등업**을 신청할 수 있습니다.  
 - 신청 시 **소속 정보와 관련 서류**를 제출합니다.  
 - **Admin 승인 후** 등업 여부가 결정됩니다.


#### 등록된 축제에 대한 관리자 신청  
- **관광공사(TourAPI)** 에 등록된 축제에 대해 **관리자 권한**을 신청할 수 있습니다.  
 - **Admin 승인 후**, 해당 축제에 대한 **수정·삭제·공지사항 등록 권한**을 획득합니다.


#### 나의 축제 등록하기  
- 축제 관리자는 새로운 **축제를 등록**할 수 있습니다.  
- 등록된 축제는 **Admin의 승인 후** 일반 사용자에게 노출됩니다.  



#### 등록 축제 관리  
- 자신이 등록한 축제에 대해 **공지사항을 등록**할 수 있습니다.  
- 축제 정보를 **수정 및 삭제**할 수 있습니다.  

---

## 3) 기술 스택
- **Backend**: Spring Boot 3.x, Java 21, JPA/Hibernate, QueryDSL  
- **DB/Cache**: MySQL (RDS), Redis (ElastiCache)  
- **Infra**: AWS EC2, ECR, S3, Route53, Nginx, Docker, GitHub Actions
- **Observability**
  - Logs: Elasticsearch, Logstash, Kibana (ELK), Filebeat  
  - Metrics: Prometheus, Spring Boot Actuator  
  - Dashboards: Grafana

---

## 4) 시스템 아키 텍쳐
<img width="452" height="456" alt="image" src="https://github.com/user-attachments/assets/1b398ff1-4724-4b55-808f-5ee7ecba4f51" />


## 5) ERD

<img width="1000" height="574" alt="image" src="https://github.com/user-attachments/assets/813cbf1f-b166-46f4-9a8f-b29c13d6bc1a" />


## 5) 팀원 소개

<table>
  <thead>
    <tr>
      <th>이진원</th><th>이윤재</th><th>주연학</th><th>하석현</th><th>문수호</th><th>심영찬</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="https://github.com/jinwon1234.png" width="150" height="150" alt="이진원"></td>
      <td><img src="https://github.com/YUNJAEGOONER.png" width="150" height="150" alt="이윤재"></td>
      <td><img src="https://github.com/jyhyt1567.png" width="150" height="150" alt="주연학"></td>
      <td><img src="https://github.com/studyhard01.png" width="150" height="150" alt="하석현"></td>
      <td><img src="https://github.com/dib3474.png" width="150" height="150" alt="문수호"></td>
      <td><img src="https://github.com/skybluesharkk.png" width="150" height="150" alt="심영찬"></td>
    </tr>
    <tr>
      <td>BE</td><td>BE</td><td>BE</td><td>AI</td><td>FE</td><td>FE</td>
    </tr>
    <tr>
      <td><a href="https://github.com/jinwon1234">GitHub</a></td>
      <td><a href="https://github.com/YUNJAEGOONER">GitHub</a></td>
      <td><a href="https://github.com/jyhyt1567">GitHub</a></td>
      <td><a href="https://github.com/studyhard01">GitHub</a></td>
      <td><a href="https://github.com/dib3474">GitHub</a></td>
      <td><a href="https://github.com/skybluesharkk">GitHub</a></td>
    </tr>
  </tbody>
</table>
