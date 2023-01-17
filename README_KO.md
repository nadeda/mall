# 쇼핑몰 

<p> 
  <a href="#public account"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E5%85%AC%E4 %BC%97%E5%8F%B7-macrozheng-blue.svg" alt="공식 계정"></a> 
  <a href="#공식 계정"><img src="http://macro-oss .oss-cn-shenzhen.aliyuncs.com/mall/badge/%E4%BA%A4%E6%B5%81-%E5%BE%AE%E4%BF%A1%E7%BE%A4-2BA245.svg " alt="커뮤니케이션"></a> 
  <a href="https://github.com/macrozheng/mall-learning"><img src="http://macro-oss.oss-cn-shenzhen. aliyuncs.com/mall/badge/%E5%AD%A6%E4%B9%A0%E6%95%99%E7%A8%8B-mall--learning-green.svg" alt="학습 튜토리얼">< /a>  
  <a href="https://github.com/macrozheng/mall-swarm"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/Cloud%E7%89%88%E6%9C%AC-mall--swarm-brightgreen.svg" alt="SpringCloud 버전"></a>
  <a href="https://github.com/macrozheng/mall-admin-web"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E5%89%8D%E7%AB%AF%E9%A1%B9%E7%9B%AE-mall--admin--web-green.svg" alt="앞- 프로젝트 종료 "></a>
  <a href="https://gitee.com/macrozheng/mall"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E7%A0% 81%E4%BA%91-%E9%A1%B9%E7%9B%AE%E5%9C%B0%E5%9D%80-orange.svg" alt="코드 클라우드"></a> 
</ p> 

## 친절한 알림 

> 1. **빠른 체험 프로젝트**: [온라인 액세스 주소](https://www.macrozheng.com/admin/index.html). 
> 2. **완전 학습 튜토리얼**: [《몰 학습 튜토리얼》](https://www.macrozheng.com). 
> 3. **마이크로서비스 버전**: Spring Cloud 2021 및 Alibaba 기반 프로젝트: [mall-swarm](https://github.com/macrozheng/mall-swarm). 
> 4.
> 5. **프로젝트 교류**: 단체 교류 프로젝트에 참여하고 싶은 친구들은 [몰 프로젝트 교류 모임](#公共号)에 가입할 수 있습니다. 

## 서문 

`mall` 프로젝트는 현재 널리 사용되는 기술을 사용하여 구현되는 완전한 전자 상거래 시스템을 구축하기 위해 노력하고 있습니다. 

## 프로젝트 문서 

- 문서 주소: [https://www.macrozheng.com](https://www.macrozheng.com) 
- 대체 주소: [https://macrozheng.github.
 
## 프로젝트 소개 

`mall` 프로젝트는 전면- 엔드몰 시스템 및 백그라운드 관리 시스템은 SpringBoot+MyBatis 기반으로 구현되어 Docker 컨테이너에 배포됩니다. 프런트 엔드 몰 시스템에는 홈페이지 포털, 상품 추천, 상품 검색, 상품 표시, 장바구니, 주문 프로세스, 회원 센터, 고객 서비스, 도움말 센터 및 기타 모듈이 포함됩니다. 배경 관리 시스템에는 상품 관리, 주문 관리, 회원 관리, 프로모션 관리, 운영 관리, 콘텐츠 관리, 통계 보고서, 재무 관리, 권한 관리 및 설정과 같은 모듈이 포함됩니다. 

### 프로젝트 데모 

#### 백그라운드 관리 시스템 

Front-end 프로젝트 `mall-admin-web` 주소: https://github.com/macrozheng/mall-admin-web 

프로젝트 데모 주소: [https://www .macrozheng .com/admin/index.html](https://www.macrozheng.com/admin/index.html)   

![백그라운드 관리 시스템 기능 데모](http://img.macrozheng.com/mall/project /mall_admin_show .png) 

#### 프론트엔드몰 시스템 

프론트엔드 프로젝트 `mall-app-web`주소: 계속 지켜봐주세요......

프로젝트 데모 주소: [https://www.macrozheng.com/app/mainpage.html](https://www.macrozheng.com/app/mainpage.html) 

![프런트엔드 몰 시스템 기능 데모](http :/ /img.macrozheng.com/mall/project/mall_app_show.png) 

### 조직 구조 

``` lua 
mall 
├── mall-common -- 도구 및 일반 코드 
├── mall-mbg -- 생성된 데이터베이스 MyBatisGenerator 운영 코드 
├── mall-security -- SpringSecurity는 공개 모듈을 캡슐화합니다 
. ├── mall-admin -- 백그라운드 몰 관리 시스템 인터페이스 
├── mall-search -- Elasticsearch 기반 상품 검색 시스템 
├── mall-portal -- front desk 몰 시스템 인터페이스 
└── mall-demo -- 프레임워크 구축시 테스트 코드 
``` 

### 기술 선택 

#### 백엔드 기술 

| 기술 | 설명 | 공식 홈페이지 | 
| ---------------------------------- | ------------------ - | ------------------------------------------------ - | 
| Spring Boot | 웹 애플리케이션 개발 프레임워크 | https://spring.io/projects/spring-boot | 
| SpringSecurity | 인증 및 권한 부여 프레임워크 | https://spring.io/projects/spring-security | 
| MyBatis | ORM 프레임워크 | http: //www.mybatis.org/mybatis-3/zh/index.html |
| MyBatisGenerator | 데이터 레이어 코드 생성기 | http://www.mybatis.org/generator/index.html | 
| Elasticsearch | 검색 엔진 | https://github.com/elastic/elasticsearch | 
| RabbitMQ | Message Queue | https : //www.rabbitmq.com/ | 
| Redis | 메모리 데이터 저장소 | https://redis.io/ | 
| MongoDB | NoSql 데이터베이스 | https://www.mongodb.com | | Kibana  
| LogStash | 로그 수집 도구 | https://github.com/elastic/logstash |
| 로그 시각화 보기 도구 | https ://github.com/elastic/kibana | 
| Nginx | ​​정적 리소스 서버 | https://www.nginx.com/ | 
| 도커 | 애플리케이션 컨테이너 엔진 | https://www.docker.com | 
| Jenkins | 자동 배포 도구 | https://github.com/jenkinsci/jenkins | 
| Druid | 데이터베이스 연결 풀 | https:// github .com/alibaba/druid | 
| OSS | 오브젝트 스토리지 | https://github.com/aliyun/aliyun-oss-java-sdk | 
| MinIO | 오브젝트 스토리지 | https://github.com/minio/minio | 
| JWT | JWT 로그인 지원 | https://github.com/jwtk/jjwt | 
| Lombok | Java 언어 향상 라이브러리 | https://github.com/rzwitserloot/lombok | 
| Hutool | Java 도구 클래스 라이브러리 | https:/ / github.com/looly/hutool|
| PageHelper | MyBatis 물리적 페이징 플러그인 | http://git.oschina.net/free/Mybatis_PageHelper | 
| Axios | 프런트 엔드 HTTP 프레임워크 | https://github.com/axios/axios | 
| Swagger-UI | API 문서 생성 도구 | https://github.com/swagger-api/swagger-ui |
| Hibernator-Validator | 검증 프레임워크 | http://hibernate.org/validator | 

#### 프런트 엔드 기술 

| 기술 | 설명 | 공식 웹 사이트 | 
| ---------- | ---- --- -------------- | -------------------------------- --- --- | 
| Vue | 프론트엔드 프레임워크 | https://vuejs.org/ | 
| Vue-router | 라우팅 프레임워크 | https://router.vuejs.org/ | 
| Vuex | 글로벌 상태 관리 프레임워크 | https:// vuex.vuejs.org/ | 
| 요소 | 프런트 엔드 UI 프레임워크 | https://element.eleme.io | 
| v-charts | Echarts 기반 차트 프레임워크 | https://v-charts. js.org/ | 
| Js -cookie | 쿠키 관리 도구 | https://github.com/js-cookie/js-cookie |
| nprogress | 진행률 표시줄 제어 | https://github.com/rstacruz/nprogress | 

#### 아키텍처 다이어그램 

##### 시스템 아키텍처 다이어그램 

![시스템 아키텍처 다이어그램](http://img.macrozheng.com/ mall/project/mall_micro_service_arch.jpg) 

##### 비즈니스 아키텍처 다이어그램 

![시스템 아키텍처 다이어그램](http://img.macrozheng.com/mall/project/mall_business_arch.png) 

#### 모듈 소개 

### ## 백그라운드 관리 시스템 `mall-admin` 

- 상품 관리: [Functional Structure Diagram-Commodity.jpg](document/resource/mind_product.jpg) 
- 주문 관리: [Functional Structure Diagram-Order.jpg](document/resource/ mind_order.jpg) 
- 프로모션 관리: [기능구조도-Promotion.jpg](document/resource/mind_sale.jpg) 
- 콘텐츠 관리: [기능구조도-Content.jpg](document/resource/mind_content.jpg) 
- 사용자 관리: [기능구조도-User.jpg](document/resource/mind_member.jpg) 

##### 포그라운드몰 시스템 `mall-portal` 

[기능구조도-Foreground.jpg](document/resource/mind_portal.jpg )
 
#### 개발 진행 

![프로젝트 개발 진행 차트](http://img.macrozheng.com/mall/project/mall_dev_flow.png) 

## 환경 구축 

# ## 개발 도구 

| 도구 | 도움말 | 공식 웹사이트 | 
| ------------- | ------------------- | --- - ------------------------------------------------------------- | 
| 아이디어 | 개발 IDE | https://www.jetbrains.com/idea/download | 
| RedisDesktop | redis 클라이언트 연결 도구 | https://github.com/qishibo/AnotherRedisDesktopManager | 
| Robomongo | mongo 클라이언트 연결 도구 | https:// robomongo.org/download | 
| SwitchHosts | 로컬 호스트 관리 | https://oldj.github.io/SwitchHosts/ |
| X-shell | Linux 원격 연결 도구 | http://www.netsarang.com/download/software.html |  
| Navicat | 데이터베이스 연결 도구 | http://www.formysql.com/xiazai.html |
| PowerDesigner | 데이터베이스 설계 도구 | http://powerdesigner.de/ | 
| Axure | 프로토타이핑 도구 | https / /www.axure.com/ | 
| MindMaster | 마인드 맵 디자인 도구 | http://www.edrawsoft.cn/mindmaster | 
| ScreenToGif | gif 기록 도구 | https://www.screentogif.com/ | 
| ProcessOn | Flowchart 그리기 도구 | https://www.processon.com/ | 
| PicPick | 이미지 처리 도구 | https://picpick.app/zh/ | 
| Snipaste | 화면 캡처 도구 | https://www.snipaste .com/ |
| Postman | API 인터페이스 디버깅 도구 | https://www.postman.com/ | 
| Typora | 마크다운 편집기 | https://typora.io/ | 
 
### 개발 환경

| 도구 | 버전 번호 | 다운로드 | 
| ------ - ------ | ------ | ------- ------------------------ | 
| JDK | 1.8 | https://www.oracle.com/technetwork/java/javase/downloads/jdk8 - downloads-2133151.html | 
| Mysql | 5.7 | https://www.mysql.com/ | 
| Redis | 7.0 | https://redis.io/download | 
| MongoDB | 5.0 | https://www.mongodb . com/다운로드 센터 |
| RabbitMQ | 3.10.5 | http://www.rabbitmq.com/download.html |  
| Nginx | ​​1.22 | http://nginx.org/en/download.html | 
| Elasticsearch |7.17.3 |https://www.elastic.co/downloads/elasticsearch|
| Logstash | 7.17.3 | https://www.elastic.co/cn/downloads/logstash | | Kibana | 
7.17.3 | https://www.elastic.co/cn/downloads/kibana | 

### 구축 단계 

> Windows 환경 구축 

- Windows 환경 구축은 [Windows 환경에서의 쇼핑몰 구축](https://www.macrozheng . com/mall/deploy/mall_deploy_windows.html); 
- 참고: mall-admin만 시작하고 Mysql과 Redis만 설치하면 됩니다. 
- `mall-admin-web` 프로젝트를 복제하고 IDEA로 가져와 컴파일을 완료합니다. 최종 프로젝트 주소](https://github.com/macrozheng/mall-admin-web); 
- `mall-admin-web` 프로젝트의 설치 및 배포는 [몰 프런트엔드 설치 및 배포]를 참조하세요. 프로젝트](https: //www.macrozheng.com/mall/deploy/mall_deploy_web.html). 

> 도커 환경 구축
 
- 가상 머신을 사용하여 CentOS7.6을 설치하십시오. [가상 머신 설치 및 Linux 사용, 이 문서로 충분합니다.] (https://www.macrozheng.com/tool/linux_install.html) ;
- Docker 환경 설치는 [개발자에게 필요한 Docker 명령어](https://www.macrozheng.com/mall/reference/linux_command.html)를 참고하세요 
. [SpringBoot 애플리케이션 빌드 Docker 이미지에 Maven 플러그인 사용](https://www.macrozheng.com/project/maven_docker_fabric8.html)을 참조하세요. 
- 이 프로젝트를 Docker 컨테이너에 배포하는 방법은 다음을 참조하세요. to: [Linux 환경에서의 Mall 배포(Docker 컨테이너 기반)] (https://www.macrozheng.com/mall/deploy/mall_deploy_docker.html) 
- 이 프로젝트는 Docker Compose를 사용합니다. Linux 환경(Docker Compose 기반)](https://www.macrozheng.com/mall/deploy/mall_deploy_docker_compose.html); 
- Linux에서 본 프로젝트의 자동 배포는 [Mall의 Linux에서 자동 배포]를 참조하십시오. (Jenkins 기준)](https://www.macrozheng.com/mall/deploy/mall_deploy_jenkins.html) 

> 관련 환경 배포 

- ELK 로그 수집 시스템 구축 참조: [로그 수집을 달성하기 위한 SpringBoot 애플리케이션 통합 ELK] (https://www.macrozheng.com/mall/reference/mall_tiny_elk.html );
- MinIO를 사용하여 파일을 저장하려면 다음을 참조하십시오. 
- 읽기-쓰기 분리 솔루션은 다음을 참조하십시오 
. 솔루션은 [Docker 환경 Redis 클러스터의 Miaojian](https://www.macrozheng.com/blog/redis_cluster.html)을 참조하십시오. 

## 

공식 계정 우회하지 않고 배우고 공식 계정 "**macrozheng**"에 주목하고 "**학습 루트**"라고 답장하고 쇼핑몰 프로젝트 전용 학습 루트를 얻으십시오! 

WeChat 그룹 통신을 추가하고 공식 계정 배경에서 "**그룹 추가**"라고 답장하면 됩니다. 

![공개 계정 이미지](http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/banner/qrcode_for_macrozheng_258.jpg) 

## 라이선스 

[Apache 라이선스 2.0](https://github.com / macrozheng/mall/blob/master/LICENSE) 

Copyright (c) 2018-2022 매크로정
