#  CodeEdu - 온라인 학습 관리 시스템

<div align="center">

![CodeEdu Logo](https://img.shields.io/badge/CodeEdu-LMS-orange?style=for-the-badge&logo=graduation-cap)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-brightgreen?style=for-the-badge&logo=spring)
![Java](https://img.shields.io/badge/Java-17-red?style=for-the-badge&logo=openjdk)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**"학습의 혁신, CodeEdu와 함께하세요!"** 

*Made with  by 와플곰 & CodeEdu Team*

</div>

##  프로젝트 소개

CodeEdu는 **학생**, **강사**, **관리자**를 위한 통합 온라인 학습 플랫폼입니다.
현대적인 웹 기술을 활용하여 효율적이고 즐거운 학습 경험을 제공합니다.

###  프로젝트 목표
-  **효율적인 학습**: 체계적인 강의 관리와 진도 추적
-  **원활한 소통**: 실시간 토론과 피드백 시스템  
-  **데이터 기반 관리**: 학습 통계와 성과 분석
-  **안전한 환경**: 사용자 데이터 보호와 접근 제어

##  주요 기능

###  학생 기능
-  **강의 수강**: 동영상, 텍스트, 퀴즈 등 다양한 콘텐츠
-  **과제 관리**: 과제 제출, 피드백 확인, 성적 조회
-  **토론 참여**: 강의별 토론 게시판과 Q&A
-  **학습 추적**: 진도율, 성취도, 학습 통계

###  강사 기능  
-  **강의 생성**: 커리큘럼 설계, 콘텐츠 업로드
-  **과제 관리**: 과제 출제, 채점, 피드백 제공
-  **학생 관리**: 수강생 현황, 성적 관리
- **분석 도구**: 학습 통계, 참여도 분석

###  관리자 기능
-  **시스템 관리**: 사용자 관리, 권한 설정
-  **통계 대시보드**: 전체 이용 현황, 성과 지표
-  **설정 관리**: 시스템 설정, 공지사항 관리
-  **보안 관리**: 데이터 백업, 접근 로그 관리

## 🛠 기술 스택

### Backend
- **Framework**: Spring Boot 3.2.0
- **Language**: Java 17
- **Database**: MySQL 8.0 (Production), H2 (Development)  
- **ORM**: Spring Data JPA + Hibernate
- **Security**: Spring Security + JWT
- **Build Tool**: Gradle

### Frontend  
- **Template Engine**: Thymeleaf
- **CSS Framework**: Bootstrap 5
- **JavaScript**: Vanilla JS + Chart.js
- **Icons**: Font Awesome

### DevOps & Tools
- **Version Control**: Git + GitHub
- **IDE**: IntelliJ IDEA / Eclipse STS
- **Testing**: JUnit 5, Mockito
- **Documentation**: Swagger/OpenAPI 3

##  빠른 시작

### 요구 사항
-  **Java 17** 이상
-  **MySQL 8.0** (선택사항, H2로 대체 가능)
-  **Gradle 7.0** 이상

### 설치 및 실행

1️⃣ **저장소 클론**
저장소 주소 쓰기


4️⃣ **접속 확인**
-  **메인 페이지**: http://localhost:8080
-  **Health Check**: http://localhost:8080/health
-  **H2 Console**: http://localhost:8080/h2-console

##  개발팀 소개

<table>
<tr>
<td align="center">
<img src="https://avatars.githubusercontent.com/u/your-id?v=4" width="100px;"/><br>
<b>CodeEdu CTO</b><br>
<sub>프로젝트 총괄</sub>
</td>
<td align="center">
<img src="https://github.com/identicons/kimdev.png" width="100px;"/><br>
<b>바쁘개</b><br>
<sub>Backend Developer</sub>
</td>
<td align="center">
<img src="https://github.com/identicons/parkfront.png" width="100px;"/><br>
<b>급하냥</b><br>
<sub>Frontend Developer</sub>
</td>
<td align="center">
<img src="https://github.com/identicons/leetest.png" width="100px;"/><br>
<b>카피바라</b><br>
<sub>QA Engineer</sub>
</td>
</tr>
</table>

### 역할 분담
| 팀원 | 역할 | 담당 업무 | GitHub |
|------|------|----------|---------|
|  **CTO** | Project Leader | 전체 아키텍처, 기술 선택 | [@your-username](https://github.com/your-username) |
|  **바쁘개** | Backend Developer | API 개발, 데이터베이스 설계 | [@kimdev](https://github.com/kimdev) |
|  **급하냥** | Frontend Developer | UI/UX, 사용자 인터페이스 | [@parkfront](https://github.com/parkfront) |
|  **카피바라** | QA Engineer | 테스트 자동화, 품질 관리 | [@leetest](https://github.com/leetest) |
|  **누렁이** | Junior Developer | 간단한 기능, 학습 지원 | [@choinew](https://github.com/choinew) |

##  기여하기 (Contributing)

CodeEdu 프로젝트에 기여해주셔서 감사합니다! 

### 기여 방법

1️⃣ **Fork** 이 저장소를 본인 계정으로 Fork합니다
2️⃣ **Clone** Fork한 저장소를 로컬에 복제합니다
3️⃣ **Branch** 새로운 기능 브랜치를 생성합니다
git checkout -b feature/amazing-feature

text
4️ ⃣ **Commit** 변경사항을 커밋합니다
git commit -m "feat: Add some AmazingFeature"

text
5️⃣ **Push** 브랜치에 푸시합니다
git push origin feature/amazing-feature

text
6️⃣ **Pull Request** GitHub에서 PR을 생성합니다

### 개발 가이드라인
-  **이슈 먼저**: 새로운 기능은 이슈로 먼저 논의
-  **코드 리뷰**: 모든 PR은 최소 1명의 리뷰 필수
-  **테스트**: 새로운 기능에는 테스트 코드 포함
-  **문서화**: API 변경 시 문서 업데이트

## 📄 라이선스

이 프로젝트는 [MIT License](LICENSE) 하에 배포됩니다.

##  문의 및 지원

-  **Email**: support@codeedu.com
-  **버그 리포트**: [Issues](https://github.com/your-username/codeedu-lms/issues)
-  **기능 제안**: [Discussions](https://github.com/your-username/codeedu-lms/discussions)
-  **문서**: [Wiki](https://github.com/your-username/codeedu-lms/wiki)

##  감사인사

-  **와플곰**: 달콤한 협업 환경 구축
-  **탱고**: Git의 철학적 가이드  
-  **오구**: 빠른 개발 프로세스 구축
-  **모든 기여자들**: 함께 만들어가는 CodeEdu

---

<div align="center">

**⭐ 이 프로젝트가 도움이 되셨다면 Star를 눌러주세요! ⭐**

*"좋은 코드는 혼자 만드는 것이 아니라 함께 만드는 것입니다"* - 와플곰

</div>
EOF
