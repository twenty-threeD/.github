<div align="center">

<img src="https://raw.githubusercontent.com/twenty-threeD/23D-Web/main/public/banner.png" alt="블록체인으로 보호받는 잇다에서 거래해요" width="100%" />

<br />
<br />

# 잇다 · ITDA

**프리랜서 거래를 막는 것은 실력이 아니라 불신입니다.**<br />
잇다는 블록체인에 영구 저장되는 계약서와 에스크로 결제로<br />
의뢰인과 프리랜서가 처음부터 서로를 믿고 시작할 수 있게 만듭니다.

<br />

<img src="https://img.shields.io/badge/Team-23D-FE6A4C?style=for-the-badge&labelColor=1A2747" />
<img src="https://img.shields.io/badge/DGSW-나르샤_프로젝트-FE6A4C?style=for-the-badge&labelColor=1A2747" />
<img src="https://img.shields.io/badge/2026.03-진행_중-FE6A4C?style=for-the-badge&labelColor=1A2747" />

</div>

<br />

## 🧩 Problem

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>💸 대금 미지급</h3>
      작업을 마쳐도 대금이 들어오지 않고,<br />받아야 한다는 걸 증명할 수단도 마땅치 않습니다.
    </td>
    <td width="33%" valign="top">
      <h3>📄 계약서 분쟁</h3>
      구두 합의와 수정된 문서가 섞이면서<br />무엇이 원본인지 아무도 확인할 수 없습니다.
    </td>
    <td width="33%" valign="top">
      <h3>❓ 검증 안 된 상대</h3>
      이력도 평판도 확인하기 어려워<br />매번 처음부터 상대를 믿어야 합니다.
    </td>
  </tr>
</table>

<br />

## 💡 Solution

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <h3>🔗 블록체인 계약서</h3>
      한 번 기록된 계약서는<br />누구도 바꿀 수 없습니다
    </td>
    <td width="33%" align="center" valign="top">
      <h3>🔒 에스크로 결제</h3>
      대금을 먼저 예치하고<br />작업이 끝나면 정산합니다
    </td>
    <td width="33%" align="center" valign="top">
      <h3>💬 실시간 협업</h3>
      채팅과 작업 공유로<br />거래의 모든 과정을 한곳에서
    </td>
  </tr>
</table>

### 계약서가 위변조되지 않는 원리

```mermaid
flowchart LR
    A["📝 계약 조건 합의<br/>금액 · 기간 · 산출물"] --> B["#️⃣ 해시 생성<br/>문서의 고유 지문값"]
    B --> C["⛓️ 블록에 기록<br/>순서 확정"]
    C --> D["✅ 위변조 불가<br/>한 글자만 바뀌어도 검증 실패"]

    style A fill:#FFF1EE,stroke:#FE6A4C,color:#1A2747
    style B fill:#FFF1EE,stroke:#FE6A4C,color:#1A2747
    style C fill:#FFF1EE,stroke:#FE6A4C,color:#1A2747
    style D fill:#FE6A4C,stroke:#FE6A4C,color:#FFFFFF
```

<br />

## ✨ Features

| | 기능 | 설명 |
|:-:|---|---|
| 🔐 | **인증** | 이메일 및 카카오 · 구글 · 네이버 소셜 로그인 |
| 🔍 | **탐색** | 카테고리별 외주 글과 프리랜서 탐색, 검색 |
| 📑 | **계약 · 견적** | 견적서 작성, 전자 서명 계약서, 블록체인 기록 |
| 💳 | **결제** | Toss Payments 기반 에스크로 결제 |
| 💬 | **채팅** | 실시간 채팅과 거래 카드 |
| ⭐ | **리뷰 · 프로필** | 거래 완료 후 리뷰, 포트폴리오와 커리어 관리 |
| 📝 | **커뮤니티** | 마크다운 기반 게시글과 댓글 |

<br />

## 🛠 Tech Stack

<div align="center">

**Frontend**

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black" />

**Backend**

<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
<img src="https://img.shields.io/badge/STOMP_·_WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white" />

**Service**

<img src="https://img.shields.io/badge/Toss_Payments-0064FF?style=flat-square&logo=toss&logoColor=white" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />

**Collaboration**

<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" />

</div>

<br />

## 📦 Repositories

| Repository | 설명 |
|---|---|
| [**23D-Web**](https://github.com/twenty-threeD/23D-Web) | 잇다 웹 클라이언트 · Next.js |

<br />

## 👥 Contributors

<div align="center">

<a href="https://github.com/twenty-threeD/23D-Web/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=twenty-threeD/23D-Web" />
</a>

<br />
<br />

<sub>대구소프트웨어마이스터고등학교 · Team 23D</sub>

<br />

<a href="https://www.instagram.com/idta.blockchain/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" />
</a>

</div>
