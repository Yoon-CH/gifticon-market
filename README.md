# 니콘 내콘 모바일 페이지 클론

## 프로젝트 소개

> 모바일 쿠폰 중고 거래 사이트이며, 앱 형태의 모습으로 웹에서 구현하였습니다.

## member

<table>
  <tr>
        </td>
      <td align="center">
      <a href="https://github.com/LEEHYUNHO2001"
        ><img
          src="https://avatars.githubusercontent.com/LEEHYUNHO2001"
          width="100px;"
          alt=""
        /><br /><sub><b>이현호</b></sub></a>
    <br />
    </td>
    <td align="center">
      <a href="https://github.com/hoonjoo-park"
        ><img
          src="https://avatars.githubusercontent.com/hoonjoo-park"
          width="100px;"
          alt=""
        /><br /><sub><b>박훈주</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/Yoon-CH"
        ><img
          src="https://avatars.githubusercontent.com/Yoon-CH"
          width="100px;"
          alt=""
        /><br /><sub><b>윤창현</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/devjoylee"
        ><img
          src="https://avatars.githubusercontent.com/devjoylee"
          width="100px;"
          alt=""
        /><br /><sub><b>이주영</b></sub></a
      ><br />
  </tr>
</table>

| 팀 구성 | 담당                                           |
| ------- | ---------------------------------------------- |
| 이현호  | 메뉴창 , 고객 센터 페이지                      |
| 박훈주  | 메인 홈 케러셀, 상품 상세 페이지               |
| 윤창현  | 메인 홈 카테고리 카드, 카테고리 페이지, footer |
| 이주영  | 상품 리스트 페이지, 땡처리 리스트, header      |

<br />

## 배포 주소

### [https://gifticon-market.vercel.app/](https://gifticon-market.vercel.app/)

<br />

## 실행 방법

### To Start

```bash
$ yarn dev
```

### E2E 테스트

```bash
$ yarn test
```

<br />

## 사용 기술 및 스택

- Stack
  - Next.js + React Hooks
  - TypeScript
  - styled-components
  - Deploy : Vercel
  - Other : Git / GitHub
  - Build Tool (Create Next App)
  - Code Quality Tool (Prettier)

<br />

## 과제 구현 목록

### 메인 홈 카테고리 카드, 카테고리 페이지, footer : 윤창현

- 메인 카테고리 카드
  - 메인 홈페이지에 `concard` 컴포넌트를 만들어 재사용이 가능하도록 구현.
  - `grid`를 사용하여 레이아웃을 구현하고 `useData`를 통해 데이터를 연동.
- 카테고리 페이지
  - `id 값`을 넘겨주어 카테고리 카드와 탭을 구현.
  - `id === category.id`일 경우 className 활용해 현재 카테고리 탭의 색상 변경
- footer
  - 회사 이름 옆에 위 / 아래 방향 아이콘을 활용해 세부 기업 정보를 show / hide 하는 기능을 구현.

<br />

## CRA 구조

```markdown
src
│
├─components
│ ├─carousel
│ ├─category
│ ├─common
│ ├─item
│ ├─itemList
│ ├─layout
│ ├─main
│ └─QnA
├─constants
├─hooks
├─images
├─pages
│ ├─api
│ ├─brands
│ ├─categories
│ └─items
├─styles
├─types
└─utils
```

<br />

## 커밋 컨벤션

깃모지를 사용하여 직관성을 높이고, 기능이나 UI 설계에 따른 메세지를 커밋 메세지에 담는것을 컨벤션으로 결정했습니다. 깃모지로 인해 상대방이 어떤 작업을 수행했는지 한 눈에 확인할 수 있고, 메세지를 보며 조금 더 상세한 상황을 파악할 수 있습니다.

| 깃모지 | 사용 예시               |
| ------ | ----------------------- |
| 🎉     | init                    |
| 🚚     | 디렉토리 또는 파일 이동 |
| ✨     | 기능 구현               |
| 💄     | CSS 스타일링            |
| ♻️     | 리팩토링                |
| 📝     | Readme 수정             |
| ➕     | 모듈 추가               |
| 🐛     | 버그 해결               |
| 🚑️    | 치명적인 오류 해결      |

<br />

## 과제 후기

### 윤창현 ✨

Next.js를 사용하기 전에 왜 사용하며, 어떠한 장점이 있는지를 알고 사용하게 되니 처음 경험하는 것이지만 동기분들의 설명을 듣고 더 빠르게 이해하고 습득 할 수 있었던 것 같고 문제를 마주하면 해결하기 위해 노력하는 습관이 자리잡아가는 것을 느낄 수 있었던 좋은 시간이었다.
