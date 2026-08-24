<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=220&text=Hello%20!%20I'm%20Joshua%20💻&animation=fadeIn&fontColor=ffffff&fontSize=50" />
</div>

<div align="center">
  <h3>🤖 Backend & DevOps Engineer</h3>
  <p><i>꾸준히, 성실히 그리고 탁월하게.</i></p>
</div>

<br>

## 💎 BSTPG — 보석팀평가

<div align="center">
  <a href="https://bstpg.com/" target="_blank">
    <img src="https://img.shields.io/badge/🌐_bstpg.com-764ba2?style=for-the-badge&logoColor=white" alt="BSTPG Website"/>
  </a>
  <br><br>
  <b>FC Online 스쿼드 빌더 & 팀 평가 커뮤니티 플랫폼</b>
  <br>
  <sub>인플루언서 <b>주간신보석</b>과 함께 운영하는 라이브 서비스입니다.</sub>
</div>

<br>

<table width="100%" align="center">
  <tr>
    <td width="50%" valign="top">
      <sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</sub>
      <h4>🧩 스쿼드 빌더</h4>
      <ul>
        <li>포메이션 배치 & <b>OVR 자동 계산</b></li>
        <li>팀컬러 효과 · 강화 등급 반영</li>
        <li>완성한 스쿼드를 게시판에 공유</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</sub>
      <h4>💎 팀 평가</h4>
      <ul>
        <li>나의 팀을 평가받고 <b>전문 피드백</b> 받기</li>
        <li>다른 유저들의 팀에 대해 자유롭게 토론</li>
        <li>Toss Payments 기반 이용권 결제</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔍 선수 검색 & 리뷰</h4>
      <ul>
        <li>이름 검색 · 시즌 필터 · 능력치 상세</li>
        <li>포지션별 OVR 확인</li>
        <li>별점 리뷰 & 댓글로 선수 평가 공유</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>🏆 커뮤니티 & 랭킹</h4>
      <ul>
        <li>스쿼드 게시판 · 자유게시판 (추천 & 댓글)</li>
        <li>포인트 기반 등급 & 랭킹 시스템</li>
        <li>Nexon Open API 기반 <b>FC 닉네임 인증</b></li>
      </ul>
    </td>
  </tr>
</table>

### 🏗️ Tech Stack & Architecture

<table width="100%" align="center">
  <tr>
    <th width="18%">구분</th>
    <th>스택</th>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td>Kotlin · Spring Boot 3.4 (JDK 21) · JPA · Flyway</td>
  </tr>
  <tr>
    <td align="center"><b>Frontend</b></td>
    <td>React 19 · TypeScript · Vite · Tailwind CSS 4 · shadcn/ui</td>
  </tr>
  <tr>
    <td align="center"><b>Database</b></td>
    <td>PostgreSQL 16 · Redis 7</td>
  </tr>
  <tr>
    <td align="center"><b>Infra</b></td>
    <td>AWS ECS Fargate · RDS · ElastiCache · S3 · CloudFront</td>
  </tr>
  <tr>
    <td align="center"><b>CI/CD</b></td>
    <td>GitHub Actions · Docker (GHCR) · Nginx</td>
  </tr>
</table>

- **Clean Architecture** — `Domain → Application(Port) → Adapter`, 백엔드와 프론트엔드 모두 동일한 구조로 설계
- **무중단 운영** — 태그 기반 버전 배포 & 즉시 롤백, 점검 모드 자동 전환
- **외부 연동** — Nexon Open API (선수 데이터 · 닉네임 인증) · Toss Payments (결제)

> 📌 **Private Repository**로 운영되고 있으며, [bstpg.com](https://bstpg.com/)에서 실제 서비스를 확인하실 수 있습니다.

<br>

## 🛠️ Tech Stacks

<div align="center">
  <img src="https://img.shields.io/badge/Kotlin-8A2BE2?style=for-the-badge&logo=Kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=white"/>
  <br>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
  <br>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonWebServices&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=GitHubActions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=Nginx&logoColor=white"/>
</div>

<br>

## 🧑‍💻 Contact

<div align="center">
  <a href="https://velog.io/@joshuara7235">
    <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white"/>
  </a>
  <a href="mailto:joshuara7235@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white"/>
  </a>
</div>

<br>

## ✒️ Velog

<div align="center">

velog 👉 <a href="https://velog.io/@joshuara7235">Personal Web Pages 🌱</a>

[![Velog's GitHub stats](https://velog-readme-stats.vercel.app/api?name=joshuara7235&color=dark)](https://velog.io/@joshuara7235)

</div>

<br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=120&section=footer" />
</div>
