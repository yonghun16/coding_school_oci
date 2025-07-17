## OCI VS AWS 속도 비교

- OCI  http://140.238.15.71:8081/ 
- 백엔드 평균 응답 시간 : 약 90ms
- 평균 이미지 로딩 시간 : 약 7.5초
<img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/oci.gif?raw=true">

- AWS  https://shimmering-moxie-d45a15.netlify.app/
- 백엔드 평균 응답 시간 : 약 700ms
- 평균 이미지 로딩 시간 : 약 16.5초
<img width=400 src="https://github.com/yonghun16/coding_school_oci/blob/main/images/aws.gif?raw=true">


- 사용한 이미지
  - 2.2mb 22장
  
- OCI 테스트 배포 환경
  - frontend page : OCI Free Tier
  - backend page : Root Block Volume in the OCI Free Tier
  - image source : Root Block Volume in the OCI Free Tier
 
- AWS 테스트 배포 환경
  - frontend page : Netlify
  - backend page : AWS EC2 Free Tier
  - image source : AWS S3 Free Tier

## 무료티어 스펙 비교 (2025년 기준)

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
