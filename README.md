## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Main Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)  |
| **Other Language** | ![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white) ![javascript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)|
| **Front-end/Back-end** | ![Node.js](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white) ![MYSQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)|
| **Design** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge)   ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white) |
| **Infrastructure** | ![AWS](https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white) ![Google Play Console](https://img.shields.io/badge/Google%20Play%20Console-414141?style=for-the-badge&logo=googleplay&logoColor=white)|
| **Tool/Collaboration** | ![Visual Studio](https://custom-icon-badges.demolab.com/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visualstudio&logoColor=white) ![Spyder](https://img.shields.io/badge/Spyder-8C0000?style=for-the-badge&logo=spyderide&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)  ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)|

## ⛰️ OREUM-IT Activity

[OREUM-IT](https://github.com/OREUM-IT)에서 제주 여행·등반 서비스 개발에 참여하고 있습니다.

- **[오름잇 Flutter 클라이언트](https://github.com/OREUM-IT/jeju-tour-flutter)**: Dart/Flutter 기반 웹·Android·iOS 프로젝트.
- **주요 구현**: 여행 일정·코스 빌더, 저장 일정, 지도·고도 기반 경로 편집, GPS·사진 인증 챌린지, 실시간 기상 화면과 기존 API 연동.
- **검증·배포 기반**: Flutter 분석·테스트·웹 빌드 CI와 Vercel 웹 배포 설정.

## 📊 GitHub Activity

<!--
통계·언어 카드 설정 (.github/workflows/grs.yml)
1. Settings > Secrets and variables > Actions에 METRICS_TOKEN secret을 등록합니다.
   통계 카드와 언어 분석에서 같은 토큰을 사용합니다. OREUM-IT의 두 저장소를 읽을 수 있어야 합니다.
   Metrics 문서의 개인 액세스 토큰 설정을 따릅니다. 조직 정보에는 read:org가 필요할 수 있으며,
   비공개 저장소를 포함할 경우에만 해당 저장소 접근 권한과 조직의 SSO 승인을 추가합니다.
   https://github.com/lowlighter/metrics/blob/master/.github/readme/partials/documentation/setup/action.md
2. Actions > Update README cards > Run workflow를 실행합니다.
   통계 카드는 30분 간격, 언어 기여 분석은 매일 09:17 KST에 예약 실행됩니다.
   README 또는 이 워크플로가 main에서 바뀌어도 전체 분석을 실행하며, GitHub 사정에 따라 지연될 수 있습니다.
3. 선택: METRICS_COMMIT_AUTHORS 변수에 본인 커밋의 작성자 이름/이메일을 쉼표로 구분해 넣습니다.
   기본 작성자 식별자는 mw48795472입니다.
4. 선택: LANGUAGE_REPOSITORIES 변수에 추가 분석할 공개/접근 가능한 저장소를 owner/repo 형식으로
   쉼표로 구분해 넣습니다. OREUM-IT의 두 저장소는 기본 분석 대상에 명시적으로 포함합니다.
   명시적으로 추가한 저장소는 제외 설정보다 우선합니다.
5. 분석 시간: 전체 언어 분석은 최대 60분, 카드 저장을 포함한 작업은 최대 90분입니다.
   plugin_languages_analysis_timeout_repositories: 0으로 저장소별 시간 제한을 해제했습니다.
   각 실행은 처음부터 다시 계산하며, 이전 실행에서 누락된 부분을 이어서 누적하지 않습니다.
   시간 제한 경고가 표시되면 해당 실행의 분석 로그를 확인합니다.
개인·협업·소속 조직 저장소에서 작성자가 일치하는 비병합 커밋 변경량을 분석합니다.
저장소 접근 권한, 작성자 식별 및 분석 시간 제한에 따라 일부 기여가 누락될 수 있습니다.
기존 Tour-Navigator-App 제외 설정과 언어 6개 표시 설정은 유지합니다.
토큰이 없으면 통계는 공개 접근 범위, 언어 카드는 개인 저장소 기준으로 갱신합니다.
통계 생성 실패 시 커밋을 중단하고, 언어 분석 실패 시 직전 언어 카드를 유지합니다.

검증 기록 (2026-10-15, 실행 #109): 13분 5초에 완료했습니다.
Halla-GeoData의 본인 커밋 9개를 모두 분석했고, 전체 189개 커밋 처리 및
시간 제한 경고가 없는 profile/top-langs.svg 저장을 확인했습니다.
https://github.com/mw48795472/mw48795472/actions/runs/38590259076
-->

### Overall Stats

![GitHub Stats](./profile/stats.svg)

개인·조직 저장소에서 GitHub가 계정에 귀속한 활동을 집계합니다. 커밋·기여 저장소는 최근 1년, PR·이슈는 누적이며, Stars는 개인 소유 저장소 기준입니다. 비공개 기여는 설정된 토큰의 접근 범위 내에서 반영됩니다.

### OREUM-IT Stats

[![OREUM-IT Contributions](./profile/oreum-it-stats.svg)](https://github.com/OREUM-IT)

`mw48795472`의 OREUM-IT 내 누적 커밋·작성 PR·리뷰한 PR·작성 이슈를 GitHub 검색 API로 집계합니다. 조직 전체 활동량이 아닌 본인 활동이며, 비공개 저장소의 세부 내용은 표시하지 않습니다. 전체 통계와 집계 기간·방식이 다르므로 두 카드를 더하지 않습니다.

### Language Activity

![Language activity](./profile/top-langs.svg)

개인·협업·소속 조직 저장소의 본인 비병합 커밋 변경량을 분석하며, OREUM-IT 프로젝트도 포함합니다.

![Pinned](./profile/pin-stats-organization-github-readme-stats.svg)
   
