![header](https://capsule-render.vercel.app/api?type=waving&color=4078c0&height=180&section=header&text=레트로의%20귀환\(OCI\)&fontSize=45&animation=fadeIn&fontAlignY=38&desc=yonghun16&descAlignY=55&descAlign=85)

| 코딩스쿨 - 레트로의 귀환(OCI) |
|----------------------|
|<div><img src="https://github.com/yonghun16/coding_school_introduction_to_jaypro/blob/main/previews/preview1.jpeg?raw=true" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_introduction_to_jaypro/blob/main/previews/preview2.jpeg" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_introduction_to_jaypro/blob/main/previews/preview3.jpeg" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_introduction_to_jaypro/blob/main/previews/preview4.jpeg" width=800px /></div>|

<ul>
  <li>제이프로(JayPro)는 노드 기반 시각화 코딩 방식을 통해 학습자의 논리적 사고와 문제 해결력을 자연스럽게 길러주는 코딩 교육 플랫폼입니다.<br />
    블록형 코딩보다 한 단계 더 발전된 노드 기반 인터페이스를 활용해, 학습자는 데이터 흐름과 명령 구조를 직관적으로 이해할 수 있으며, 복잡한 알고리즘도 시각적으로 표현하고 연결할 수 있습니다.<br /><br />
    제이프로는 다음과 같은 특징을 갖고 있습니다:<br />	
    <ul>
      <li>노드 기반 구조: 복잡한 코드도 흐름도로 쉽게 표현하며, 알고리즘 설계 능력 강화</li>
      <li>모듈형 설계: 기능을 블록처럼 조립하며 문제 해결력 및 창의력 향상</li>
      <li>초보자 친화적: 텍스트 코딩 진입 전에 논리 흐름을 체득 가능</li>
      <li>다양한 프로젝트 적용: APP 제작, 시뮬레이션 등 실습 중심 학습 가능</li>
    </ul>
    <br />
    제이프로는 초등 고학년부터 중·고등학생, 코딩 입문자까지 누구나 쉽게 접근할 수 있으며, 소프트웨어 교육의 새로운 접근 방식을 제시합니다.</li>
</ul>


## OCI(instance, storage, DB 통합) VS AWS(분산 서비스) 속도 비교

- OCI  http://140.238.15.71:8081/ 
- 백엔드 평균 응답 시간 : 약 90ms
- 평균 이미지 로딩 시간 : 약 8초
<img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/oci.gif?raw=true">

- AWS  https://shimmering-moxie-d45a15.netlify.app/
- 백엔드 평균 응답 시간 : 약 700ms
- 평균 이미지 로딩 시간 : 약 14.5초
<img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/aws.gif?raw=true">


- 사용한 이미지
  - 2.2mb 22장
  
- OCI 테스트 배포 환경
  - frontend page : OCI Free Tier
  - backend page : Root Block Volume in the OCI Free Tier
  - image source : Root Block Volume in the OCI Free Tier
  - <img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/oci.png?raw=true">

 
- AWS 테스트 배포 환경
  - frontend page : Netlify
  - backend page : AWS EC2 Free Tier
  - image source : AWS S3 Free Tier
  - <img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/aws.png?raw=true">

### 무료티어 스펙 비교 (2025년 기준)

| 항목                | OCI (Oracle Cloud Free Tier)                                    | AWS (AWS Free Tier)                                          |
|--------------------|-----------------------------------------------------------------|--------------------------------------------------------------|
| **가상 머신**         | 2개 VM.Standard.A1.Flex (ARM, 1 OCPU, 6GB RAM 각)               | 1개 t2.micro 또는 t3.micro (1 vCPU, 1GB RAM)                   |
| **가상 머신 시간**     | **항상 무료 (Always Free)**                                       | 월 750시간 (12개월 한정)                                        |
| **Block Volume**    | 2개 볼륨, 총 200GB (Always Free)                                 | 30GB EBS (GP2 or GP3, 12개월 한정)                             |
| **Object Storage**  | 10GB Standard Object Storage (Always Free)                     | 5GB Standard S3 (12개월 한정)                                  |
| **DB (관계형)**      | 2개 Autonomous DB (Oracle DB, 20GB 각, Always Free)              | 750시간 RDS (MySQL, PostgreSQL 등, 12개월 한정)                 |
| **함수형 컴퓨팅**      | 2백만 호출/월 (OCI Functions, Always Free)                        | 1백만 호출/월 (AWS Lambda, Always Free)                        |
| **로딩 밸런서**       | 1개 Load Balancer (10Mbps, Always Free)                         | N/A (유료)                                                    |
| **모니터링/알림**     | 500만 메트릭, 1GB 로그 (Always Free)                               | CloudWatch: 10개 지표, 5GB 로그 (12개월 한정)                     |
| **기타**            | ARM + x86 VM 선택 가능                                            | ARM (Graviton) 사용 시 일부 프리티어 불가                          |


### Powerd by
<!-- OCI --><a href="https://www.oracle.com/cloud/"><img src="https://img.shields.io/badge/OCI-F80000?style=flat&logo=Oracle&logoColor=white" /></a>
<!-- AWS --><a href="https://aws.amazon.com/"><img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=AmazonAWS&logoColor=white" /></a>	
