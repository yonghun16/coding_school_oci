![header](https://capsule-render.vercel.app/api?type=waving&color=4078c0&height=180&section=header&text=레트로의%20귀환\(OCI\)&fontSize=45&animation=fadeIn&fontAlignY=38&desc=yonghun16&descAlignY=55&descAlign=85)

| 코딩스쿨 - 레트로의 귀환(OCI) |
|----------------------|
|<div><img src="https://github.com/yonghun16/coding_school_oci/blob/main/images/1.jpg?raw=true" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_oci/blob/main/images/2.jpg?raw=true" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_oci/blob/main/images/3.jpg?raw=true" width=800px /><br /><img src="https://github.com/yonghun16/coding_school_oci/blob/main/images/4.jpg?raw=true" width=800px /></div>|

<ul>
  <li>클라우드 인프라스트럭처(CLOUD INFRASTRUCTURE)는 현대 IT 서비스의 기반이 되는 클라우드 구조와 핵심 구성 요소들입니다.</li>
  <li>클라우드의 기본 개념부터 시작해, 대표 서비스 유형(IaaS, PaaS, SaaS)을 구분하고, Oracle Cloud를 중심으로 주요 퍼블릭 클라우드 제공자의 특징과 비교 분석까지 다뤄봅니다.</li>
  <ul>
    <li>핵심 개념 중심 구성: 가상 머신, 네트워크, 데이터베이스 등 클라우드의 핵심 요소</li>
    <li>프리티어 비교 학습: Oracle Cloud, AWS, GCP의 무료 요금제 및 성능 차이</li>
    <li>Oracle Cloud Infrastructure(OCI)에서 인스턴스를 생성하고 VCN 구성, Nginx 설치, 데이터베이스 설정</li>
  </ul>
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

