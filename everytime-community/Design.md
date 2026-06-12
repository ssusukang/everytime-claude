# Design System

Figma 라이브러리(파일 키: `yIDeYV7ypKp9tZsVnsiRAf`)에서 추출한 디자인 스펙입니다.
대학 커뮤니티 모바일 앱(iOS / Android)의 Foundation + Component 시스템입니다.

---

## 1. Color

### System

| 토큰 | 값 | 비고 |
|---|---|---|
| `System/White` | `#ffffff` | |
| `System/Black` | `#000000` | |

### Gray Scale

| 토큰 | 값 |
|---|---|
| `Gray/Gray0` | `#ffffff` |
| `Gray/Gray100` | `#f9f9f9` |
| `Gray/Gray200` | `#f2f2f2` |
| `Gray/Gray300` | `#ededed` |
| `Gray/Gray400` | `#d6d6d6` |
| `Gray/Gray500` | `#a6a6a6` |
| `Gray/Gray600` | `#737373` |
| `Gray/Gray700` | `#444444` |
| `Gray/Gray800` | `#292929` |

### Red

| 토큰 | 값 | 용도 |
|---|---|---|
| `Red/Red100` | `#fff3f3` | |
| `Red/Red200` | `#ffe6e6` | HOT·BEST 뱃지 배경 |
| `Red/Red600` | `#f94848` | BEST 뱃지 텍스트 |
| `Red/Red700` | `#f91f15` | HOT 텍스트, 주요 강조색 |

### Semantic Colors

| 토큰 | 값 | 용도 |
|---|---|---|
| `Cyan/Cyan100` | `#edfffe` | |
| `Cyan/Cyan700` | `#05bcbc` | |
| `Yellow/Yellow100` | `#fffbeb` | |
| `Yellow/Yellow700` | `#ffc900` | |
| `Orange/Orange700` | `#ff8f0b` | |
| `Green/Green700` | `#2bcf0e` | |
| `Blue/Blue700` | `#0397ea` | |
| `Blue/Blue900` | `#056ab5` | |

### Timetable Colors

| 토큰 | 값 |
|---|---|
| `Timetable/Timetable 1` | `#fd806d` |
| `Timetable/Timetable 2` | `#facd69` |
| `Timetable/Timetable 3` | `#afd276` |
| `Timetable/Timetable 4` | `#8ad6d7` |
| `Timetable/Timetable 5` | `#76a8f6` |
| `Timetable/Timetable 6` | `#fbaa68` |
| `Timetable/Timetable 7` | `#a588f5` |
| `Timetable/Timetable 8` | `#89dd9a` |
| `Timetable/Timetable 9` | `#8886e1` |

### Exception (Semantic Surface)

| 토큰 | 값 | 용도 |
|---|---|---|
| `Exception/BG_Page` | `#f6f6f6` | 페이지 배경 |
| `Exception/BG_Page_Card` | `#ffffff` | 페이지 카드 배경 |
| `Exception/BG_Sheet` | `#ffffff` | 바텀시트 배경 |
| `Exception/BG_Sheet_Card` | `#f9f9f9` | 바텀시트 카드 배경 |
| `Exception/BG_Menu` | `#ffffff` | 메뉴 배경 |
| `Exception/BG_Border` | `#f1f1f1` | 보더 컬러 |
| `Exception/Image Stroke` | `rgba(214, 214, 214, 0.2)` | 이미지/아바타 테두리 |
| `Exception/Dim` | `rgba(0, 0, 0, 0.2)` | 딤 오버레이 |

---

## 2. Typography

폰트 정책: **시스템 폰트 Sans-serif 우선** (Figma 내 "Apple SD Gothic Neo"는 플레이스홀더)

| 플랫폼 | 프로덕션 폰트 | Figma 폰트 |
|---|---|---|
| iOS | SF Pro | Apple SD Gothic Neo |
| Android | Roboto | Apple SD Gothic Neo |
| Web | SF Pro (macOS) / System | Apple SD Gothic Neo |

> Letter Spacing: 모든 스타일 `0` / Font Variation (SF Pro): `"wdth" 100`

### iOS 타입 스케일

| 토큰 | Size | Line Height | Bold | Regular | 용도 예시 |
|---|---|---|---|---|---|
| `Headline large` | 22px | 30px | ✓ | — | 페이지 대제목 |
| `Headline small` | 20px | 28px | ✓ | — | 섹션 헤딩 |
| `Body large` | 17px | 24px | ✓ | ✓ | 강조 본문 / 본문 |
| `Body small` | 15px | 20px | ✓ | ✓ | 닉네임, 소제목 / 댓글 본문 |
| `Caption large` | 13px | 18px | ✓ | ✓ | 시간, 메타 정보 |
| `Caption small` | 11px | 15px | ✓ | ✓ | 뱃지 텍스트 |

### Android 타입 스케일

| 토큰 | Size | Line Height | Bold | Regular |
|---|---|---|---|---|
| `Headline large` | 22px | 32px | ✓ | — |
| `Headline small` | 18px | 26px | ✓ | — |
| `Body large` | 16px | 23px | ✓ | ✓ |
| `Body small` | 14px | 20px | ✓ | ✓ |
| `Caption large` | 12px | 17px | ✓ | ✓ |
| `Caption small` | 10px | 15px | ✓ | ✓ |

### Web 타입 스케일

| 토큰 | Size | Line Height | Bold | Regular |
|---|---|---|---|---|
| `Headline large` | 22px | 30px | ✓ | — |
| `Headline small` | 18px | 26px | ✓ | — |
| `Body large` | 16px | 24px | ✓ | ✓ |
| `Body small` | 14px | 20px | ✓ | ✓ |
| `Caption large` | 12px | 18px | ✓ | ✓ |
| `Caption small` | 10px | 15px | ✓ | ✓ |

---

## 3. Spacing

> Figma 페이지: `6510:2671 (ㄴ Spacing)`  
> Gap 토큰은 `--gap/<value>` 형태의 CSS 변수로 사용됩니다.

### Spacing Scale (15단계)

| 토큰 | 값 | 주요 사용처 |
|---|---|---|
| `Gap/2` | 2px | 아이콘–라벨 사이, 뱃지 내부 |
| `Gap/4` | 4px | 태그 내부 패딩, 인라인 간격 |
| `Gap/6` | 6px | 버튼 내부 padding |
| `Gap/8` | 8px | 프로필–텍스트, 리스트 아이템 간격 |
| `Gap/12` | 12px | 버튼·칩 y축 패딩 |
| `Gap/16` | 16px | 카드 패딩, 섹션 내 수직 간격 |
| `Gap/20` | 20px | 리스트 left padding |
| `Gap/24` | 24px | 카드·댓글 padding (x/y) |
| `Gap/32` | 32px | 섹션 간 여백 |
| `Gap/40` | 40px | 큰 섹션 구분 |
| `Gap/48` | 48px | 페이지 상단 여백 |
| `Gap/56` | 56px | 탭바 높이 기준 |
| `Gap/64` | 64px | 대댓글 들여쓰기, 대형 섹션 여백 |
| `Gap/96` | 96px | 빈 상태(empty state) 상단 여백 |
| `Gap/120` | 120px | 스플래시·온보딩 최대 여백 |

### Radius Tokens

| 토큰 | 값 | 주요 사용처 |
|---|---|---|
| `Radius/4` | 4px | 카테고리 태그 |
| `Radius/8` | 8px | 일반 카드, 버튼 |
| `Radius/16` | 16px | 이미지 썸네일 |
| `Radius/24` | 24px | 입력 박스, 바텀시트 |
| `Radius/99` | 99px | 아바타, 칩, 뱃지 |
| `Radius/100` | 100px | 홈 인디케이터 바 |

### Layout

| 항목 | 값 |
|---|---|
| 기준 디바이스 폭 | 390px (iPhone 15) |
| Status Bar 높이 | 44px |
| Navigation Bar 높이 | 44px |
| Tab Bar 높이 | 49px + Safe Area |
| Safe Area bottom | 34px |

---

## 4. Shadow

> Figma 페이지: `6510:2670 (ㄴ Shadow)`  
> Figma의 shadow radius는 CSS blur의 2배로 정의됩니다 (radius 20 → CSS blur 10px).

### iOS

| 토큰 | offset | blur | spread | color | 추가 효과 | 용도 |
|---|---|---|---|---|---|---|
| `iOS/Sheet` | `0, -5px` | `10px` | `0` | `rgba(0,0,0,0.05)` | — | 바텀시트 상단 그림자 |
| `iOS/Popup Menu` | `0, 10px` | `30px` | `0` | `rgba(0,0,0,0.10)` | `backdrop-blur: 60px` | 팝업 메뉴, 컨텍스트 메뉴 |
| `iOS/Floating Button` | `0, 5px` | `7.5px` | `0` | `rgba(0,0,0,0.15)` | — | 플로팅 액션 버튼 |

```css
/* iOS/Sheet */
box-shadow: 0px -5px 10px rgba(0, 0, 0, 0.05);

/* iOS/Popup Menu */
box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.10);
backdrop-filter: blur(60px);

/* iOS/Floating Button */
box-shadow: 0px 5px 7.5px rgba(0, 0, 0, 0.15);
```

### Android

Android Sheet은 Material Design 방식으로 레이어 3개를 조합합니다.

| 토큰 | 레이어 | offset | blur | spread | color |
|---|---|---|---|---|---|
| `Android/Sheet` | 1 | `0, 8px` | `10px` | `0` | `rgba(0,0,0,0.20)` |
| | 2 | `0, 6px` | `30px` | `0` | `rgba(0,0,0,0.12)` |
| | 3 | `0, 16px` | `24px` | `0` | `rgba(0,0,0,0.14)` |
| `Android/Popup Menu` | 1 | `0, 4px` | `5px` | `4px` | `rgba(0,0,0,0.20)` |
| `Android/Floating Button` | 1 | `0, 0` | `8px` | `0` | `rgba(0,0,0,0.04)` |
| | 2 | `0, 0` | `2px` | `1px` | `rgba(0,0,0,0.04)` |
| | 3 | `0, 3px` | `4px` | `0` | `rgba(0,0,0,0.07)` |

```css
/* Android/Sheet */
box-shadow:
  0px 8px 10px rgba(0, 0, 0, 0.20),
  0px 6px 30px rgba(0, 0, 0, 0.12),
  0px 16px 24px rgba(0, 0, 0, 0.14);

/* Android/Popup Menu */
box-shadow: 0px 4px 5px 4px rgba(0, 0, 0, 0.20);

/* Android/Floating Button */
box-shadow:
  0px 0px 8px rgba(0, 0, 0, 0.04),
  0px 0px 2px 1px rgba(0, 0, 0, 0.04),
  0px 3px 4px rgba(0, 0, 0, 0.07);
```

### Web

| 토큰 | offset | blur | spread | color |
|---|---|---|---|---|
| `Web/Popup Menu` | `0, 10px` | `30px` | `0` | `rgba(0,0,0,0.10)` |

```css
/* Web/Popup Menu */
box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.10);
```

### CTA Button 스크롤 트랜지션

스크롤 시 CTA Button의 그림자가 나타나는 애니메이션입니다.

```css
transition: box-shadow 0.5s ease;
transition-delay: 400ms;
```

---

## 5. Components

컴포넌트는 세 Figma 페이지에 분산 정의됩니다.

| 페이지 | 역할 |
|---|---|
| `6510:2654 (ㄴ OS)` | iOS / Android 플랫폼 전용 네이티브 UI 패턴 |
| `4:2661 (ㄴ Element)` | 앱 전역에서 재사용되는 기본 UI 컴포넌트 |
| `4:2662 (ㄴ Featured)` | 피처별 화면 수준 도메인 컴포넌트 |

---

### OS 컴포넌트 (`6510:2654`)

플랫폼 고유 UI 패턴. `OS=iOS` / `OS=Android` 프로퍼티로 분기됩니다.

| 컴포넌트 | 설명 |
|---|---|
| `Action Sheet` | iOS Action Sheet / Android 하단 액션 목록 |
| `Action Buttons` | 액션 버튼 그룹 |
| `Badge` · `Android Badge` · `iOS Badge` | 알림 배지 (OS별 스타일) |
| `Calendar` · `Calendar Picker` · `Calender Modal` | 날짜 선택 달력 (Android Modal 포함) |
| `Date Picker` | 날짜 피커 |
| `Dialog` · `Input Text Dialog` | 플랫폼 기본 다이얼로그 |
| `Keyboard` · `iOS Keyboard` | 소프트 키보드 레이아웃 |
| `Loading` | 플랫폼 기본 로딩 인디케이터 |
| `Menu` · `DefaultMenu` · `DefaultMenuItem` | 컨텍스트 메뉴 |
| `GroupMenu` · `Group-SubMenuItem` · `Submenu` | 그룹·서브 메뉴 계층 |
| `Navigation Bar (Element)` | OS 기본 네비게이션 바 |
| `Picker` | OS 기본 휠 피커 |
| `Radio Buttons` | OS 기본 라디오 버튼 |
| `Safe Area` | Safe Area Inset 참조 프레임 |
| `Share Controller` | OS 공유 시트 |
| `Status Bar` · `StatusBar` | 상태 바 레이아웃 |
| `Text Field` | OS 기본 텍스트 입력 |
| `Time Picker` | 시간 피커 |
| `Toast` | OS 토스트 알림 |
| `Toggle` | OS 기본 토글 스위치 |
| `iOS` · `Android` | OS 별 디바이스 프레임 참조 |

---

### Element 컴포넌트 (`4:2661`)

앱 전역에서 재사용되는 원자·분자 수준 컴포넌트입니다.

#### Controls

| 컴포넌트 | 설명 |
|---|---|
| `Icon` · `Icon Toggle` | 아이콘 (S/M/mcr/ETC) 및 토글 상태 아이콘 |
| `Chip` · `Chips` | 필터·선택용 칩 |
| `Check Box` | 체크박스 |
| `Radio` | 라디오 버튼 |
| `Toggle` | 스위치 토글 |
| `Divider` | 구분선 (1px / 8px thick) |
| `Tooltip` | 툴팁 말풍선 |
| `badge` | 인라인 뱃지 |

#### Input

| 컴포넌트 | 설명 |
|---|---|
| `Input Field` · `TextField` | 단행 텍스트 입력 |
| `Text Field` · `Text Area` | 멀티라인 텍스트 입력 |
| `Search Bar` | 검색 입력창 |

#### Navigation

| 컴포넌트 | 설명 |
|---|---|
| `Navigation Bar` · `NavBar` · `Navbar` | 상단 네비게이션 바 (타이틀, 뒤로가기, 액션) |
| `Header` | 섹션 헤더 |
| `Bottom Tab` · `BottomTab` | 하단 탭 바 아이템 |
| `Tab` · `Tab Group` | 수평 탭 (필터용) |
| `StatusBar` | 상태 바 |
| `Handlebar` | 바텀시트 핸들바 |

#### Actions

| 컴포넌트 | 설명 |
|---|---|
| `Button` · `Btn` | 일반 버튼 (Primary / Secondary 등) |
| `Box Button` | 박스형 버튼 |
| `CTA Button` · `CTA Button Set` | 전체폭 주요 액션 버튼 |
| `Text Button` | 텍스트 전용 버튼 |
| `Close` | 닫기 버튼 |

#### Overlay & Feedback

| 컴포넌트 | 설명 |
|---|---|
| `Bottom Sheet` · `bottom sheet` | 바텀시트 컨테이너 |
| `PopupSheet` | 팝업 다이얼로그 |
| `Modal Dialog` · `Modal Container` | 모달 레이아웃 |
| `Popup_SetNicknameProfile` | 닉네임·프로필 설정 팝업 |
| `Empty State` | 빈 상태 화면 |

#### List & Cards

| 컴포넌트 | 설명 |
|---|---|
| `List` · `List Item` | 범용 리스트 아이템 |
| `Article List` | 게시글 목록 카드 |
| `horizontal cardset` · `vertical cardset` | 카드셋 레이아웃 |

---

### Featured 컴포넌트 (`4:2662`)

피처별 화면 수준 컴포넌트. 도메인 단위로 그룹화됩니다.

#### 시간표 — 메인탭

| 컴포넌트 | 설명 |
|---|---|
| `Timetable/Navbar` | 시간표 전용 네비게이션 바 (Weekly / Daily) |
| `Timetable/Week` · `Timetable/Day` | 주간 / 일간 시간표 뷰 |
| `Timetable/TimeBlock` | 시간표 수업 블록 (Large/Medium/Small × Default/Preview Others) |
| `Timetable/TimeGuide` | 시간 가이드 라인 |
| `Timetable/All day` · `Timetable/Timblock List` | 종일 이벤트 / 블록 리스트 |
| `Timetable/Indicator` | 현재 시간 인디케이터 |
| `Timetable/Today` | 오늘 날짜 표시 |
| `Timetable/Semester Picker` | 학기 선택기 |
| `Timetable/Bottomsheet Grabber` | 바텀시트 그랩바 |
| `Timetable/FloatingButton` | FAB (iOS/Android × New Event/Class/Schedule) |

#### 시간표 — 수업 탐색

| 컴포넌트 | 설명 |
|---|---|
| `Subject List` | 수업 목록 |
| `Subject List/Semester` | 학기 선택 |
| `Subject List/Filter` · `Subject List/FilterChip` | 필터 바 / 필터 칩 |
| `Subject List/Toggle` | 탐색 토글 |
| `Subject List/Picker` | 피커 (Default/Focused/Filled × Small/Large) |
| `Subject List/Time Filter` · `Subject List/Time Filter/Time` | 시간대 필터 |
| `Subject List/Search/Radio` · `Subject List/Search/Search history` | 검색 라디오 / 검색 기록 |
| `Subject List/Professor` · `Subject List/Location` · `Subject List/Time` | 교수·장소·시간 정보 |
| `Subject Detail/Detail Info/Item` | 수업 상세 정보 아이템 |
| `Subject Detail/Review` | 강의 리뷰 요약 |
| `Subject Detail/Time&Professor&Place` · `Subject Detail/Schedule Data` | 수업 상세 메타 |

#### 시간표 — 개인 일정 추가

| 컴포넌트 | 설명 |
|---|---|
| `Add Event/Title` | 일정 제목 입력 |
| `Add Event/Time` · `Add Event/Time/All day` | 시간 설정 / 종일 옵션 |
| `Add Event/Time setting` | 시간 세부 설정 |
| `Add Event/Repeat` | 반복 설정 |
| `Add Event/Location` | 장소 입력 |

#### 시간표 — 수업 추가 및 수정

| 컴포넌트 | 설명 |
|---|---|
| `Add Class/Class name` | 수업명 입력 |
| `Add Class/Semester` | 학기 선택 |
| `Add Class/Professor name` | 교수명 입력 |
| `Add Class/Location` | 강의실 입력 |
| `Add Class/Time` · `Add Class/Time Picker` | 시간 설정 / 시간 피커 |
| `Add Class/Seperate by time` | 시간별 분리 |
| `Add Class/Repeat Setting` | 반복 설정 |
| `Add Class/Select Color` | 시간표 색상 선택 (Timetable 9색) |
| `Add Class/Notification Setting` | 알림 설정 |

#### 시간표 — 개별 이벤트

| 컴포넌트 | 설명 |
|---|---|
| `Timetable/Event Info` | 이벤트 상세 정보 (Class / Event 타입) |
| `Class Event/Review` | 수업 이벤트 내 리뷰 |

#### 강의평가 — 홈

| 컴포넌트 | 설명 |
|---|---|
| `Course Review/Class List` | 강의 목록 |
| `Course Review/Navbar` | 강의평 네비게이션 바 |
| `Course Review/My Review` | 내 리뷰 (Review=on/off) |
| `Course Review/My Review/Course block` | 내 리뷰 수업 블록 |
| `Course Review/List` | 강의평 리스트 아이템 (Default / Open) |

#### 강의평가 — 강의 검색

| 컴포넌트 | 설명 |
|---|---|
| `Search Review/List` | 강의 검색 결과 아이템 |

#### 강의평가 — 특정 강의

| 컴포넌트 | 설명 |
|---|---|
| `Review Page/Nav` | 강의 상세 네비게이션 |
| `Review Page/Filter` · `Review Page/Filter/Sort by` | 리뷰 필터 / 정렬 |
| `Review Page/List` | 리뷰 목록 아이템 |
| `Review Page/List/Professor` · `Review Page/List/Subject name` | 교수별 / 강의명별 리뷰 |

#### 강의평가 — 강의평 작성

| 컴포넌트 | 설명 |
|---|---|
| `Write Review/Course Info` | 강의 정보 섹션 |
| `Write Review/Text` | 리뷰 텍스트 입력 |
| `Write Review/Done Status` | 작성 완료 상태 |
| `Write Review/Autofill/List` | 자동완성 목록 |

#### 커뮤니티 — 홈

| 컴포넌트 | 설명 |
|---|---|
| `Community/NavBar` | 커뮤니티 네비게이션 바 |
| `Community/Category` · `Community/CategoryChip` | 게시판 카테고리 / 칩 |
| `Community/Article List` | 게시글 목록 카드 |
| `Community/Image` · `Community/ImageType` | 이미지 첨부 미리보기 |
| `Community/PlayTime` | 동영상 재생 시간 표시 |
| `Community/Profile` | 프로필 (아바타 + 닉네임 + 시간) |
| `Community/ProfileIcon` | 원형 프로필 아이콘 (11 variant) |
| `Community/Posvote` | 좋아요 버튼 (아이콘 + 카운트) |
| `Community/Comment` | 댓글 카운트 표시 |
| `Community/Scrap` | 스크랩 버튼 |
| `Community/FloatingButton` | 글쓰기 FAB |
| `Community/Answer` | 답변 표시 |
| `Community/Article/Question` · `Community/Article/Mention` | 질문글 / 멘션 |

#### 커뮤니티 — 글 보기

| 컴포넌트 | 설명 |
|---|---|
| `Community/Article` | 게시글 본문 영역 |
| `Community/Comment` | 댓글 아이템 (Default / Writing / Best / Blind / Deleted / Blocked / Recomment) |
| `Community/Comment/Recomment` | 대댓글 아이템 |
| `Community/Comment/Posvote` | 댓글 좋아요 |
| `Community/WriteComment` | 댓글 입력 바 (4 variant) |

#### 커뮤니티 — 글쓰기

| 컴포넌트 | 설명 |
|---|---|
| `Write Article/Image Upload` | 이미지 업로드 영역 |
| `Write Article/Attach` | 첨부 파일 |
| `Write Article/Mention` | 멘션 입력 |

#### 알림

| 컴포넌트 | 설명 |
|---|---|
| `Notification/Alert` | 알림 아이템 (Unread / On read) |
| `Notification/Alert Box Button` | 알림 박스 액션 버튼 (Primary / Secondary) |

#### 로그인 / 회원가입

| 컴포넌트 | 설명 |
|---|---|
| `Custom Content` | 커스텀 콘텐츠 슬롯 (Blank / 학교 인증 / 약관 동의) |
| `Univ Select` | 학교 선택 |
| `Code Verification` | 인증 코드 입력 (Empty / Filled) |

#### 학교 인증 / 모바일 학생증

| 컴포넌트 | 설명 |
|---|---|
| `ID Card` | 모바일 학생증 (Type=0~4 × Back=On/Off → 10 variant) |
| `ID Card/Buttons` | 학생증 하단 버튼 (OS=iOS / OS=Android) |

#### 마이페이지

| 컴포넌트 | 설명 |
|---|---|
| `My Page/Navbar` | 마이페이지 네비게이션 바 |
| `My Page/List` | 마이페이지 목록 아이템 (Title / Item) |
| `My Page/학적 처리 내역` | 학적 처리 내역 아이템 |

#### Web (랜딩 페이지)

| 컴포넌트 | 설명 |
|---|---|
| `PC GNB` | PC 글로벌 네비게이션 바 |
| `Footer/PC` · `Footer/mobile` | PC / 모바일 푸터 |
| `description/introduction/text` | 소개 텍스트 블록 (card / whitebg / graybg 변형) |
| `input/inquiry` | 문의 입력 폼 |

#### Web — 페이지 템플릿

| 템플릿 | 설명 |
|---|---|
| `Intro` | 서비스 소개 페이지 |
| `Community` | 커뮤니티 소개 페이지 |
| `Timetable` | 시간표 소개 페이지 |
| `LectureReview` | 강의평가 소개 페이지 |
| `Download` | 앱 다운로드 페이지 |

---

## 5. Image Assets

> Figma 페이지: `70:1395 (ㄴ Image)`  
> 모든 에셋 컴포넌트명은 `global_Img_` 접두사로 시작합니다.  
> Props 컨벤션: `type=<Type>  name=<Name>  [theme=Light|Dark]`

---

### 커뮤니티

#### Placeholder `global_Img_Placeholder`

콘텐츠 로딩 중 빈 영역에 사용되는 플레이스홀더입니다.

| 변형 | Props |
|---|---|
| 밝은 배경 | `type=Placeholder  name=Placeholder  theme=Light` |
| 어두운 배경 | `type=Placeholder  name=Placeholder  theme=Dark` |

#### VideoLoading `global_Img_VideoLoading`

동영상 로딩 상태 이미지입니다.

| 변형 | Props |
|---|---|
| 밝은 배경 | `type=VideoLoading  name=VideoLoading  theme=Light` |
| 어두운 배경 | `type=VideoLoading  name=VideoLoading  theme=Dark` |

#### Community Profile `global_Img_ProfileImage` / `CommunityProfile`

**사이즈: 96 × 96px**

익명 프로필과 실명 프로필 두 종류가 있습니다.

| 컴포넌트 | 변형 | 설명 |
|---|---|---|
| `CommunityProfile` | `name=0` ~ `name=9` | 익명 커뮤니티 프로필 10종 |
| `ProfileImage` | `name=0/light`, `name=0/dark` | 기본 프로필 (라이트/다크 테마) |
| `ProfileImage` | `name=1` ~ `name=9` | 실명 프로필 이미지 9종 |

#### Category `global_Img_Category`

**사이즈: 96 × 96px**  
게시판 카테고리 아이콘 8종입니다.

| name | 설명 |
|---|---|
| `Blank` | 기본 빈 카테고리 |
| `HOT` | 인기 게시판 |
| `Common` | 일반 게시판 |
| `School` | 학교 관련 |
| `Sale` | 중고거래 |
| `Recruit` | 모집/구인 |
| `Career` | 취업/진로 |
| `Missing` | 분실물 |

#### ID Card Sample `global_Img_IDCardSample`

`type=IDCardSample  name=idCardSample` — 학생증 샘플 예시 이미지 1종

---

### 학교 인증 / 모바일 학생증

#### IDCard Profile `global_Img_IDCardProfile`

**사이즈: 480 × 480px**  
학생증용 프로필 사진 유형 5종 (`name=0` ~ `name=4`)

#### IDCard Illust `global_Img_IDCardIllust`

**사이즈: 894 × 540px**  
`type=IDCardIllust  name=idCardIllust` — 학생증 발급 안내 일러스트 1종

#### IDCard UnivLogo `global_Img_IDCardUnivLogo`

**사이즈: 600 × 600px**  
학생증 내 대학 로고 21종

| 코드 | 대학 |
|---|---|
| `AJC` `DTU` `FTU` `HANU` `HCMUNRE` | — |
| `HNUE` `HUST` `NEU` `PTIT` `SGU` | — |
| `TMU` `UD DUE` `UD DUT` `UD UTE` `UD VKU` | — |
| `UEH` `VNU_HUS` `VNU UEB` `VNU UET` `VNU USSH` | — |
| `VNUHCM UIT` | — |

---

### Common

#### Banner `global_Img_Banner`

**사이즈: 144 × 144px**  
4가지 배너 유형 × Light/Dark = **8 변형**

| name | Light | Dark | 용도 |
|---|---|---|---|
| `Blank` | ✓ | ✓ | 빈 배너 |
| `ID Card` | ✓ | ✓ | 학생증 안내 |
| `Lecture` | ✓ | ✓ | 강의평가 안내 |
| `Warning` | ✓ | ✓ | 경고/주의 |

---

### 회원가입 / 온보딩

#### UnivLogo `global_Img_UnivLogo`

**사이즈: 120 × 120px**  
회원가입 화면용 대학 로고 21종 (IDCardUnivLogo와 동일 대학, 소형 버전)

#### Onboarding `global_img_onboarding`

**사이즈: 840 × 840px**  
온보딩 슬라이드 일러스트 5종

| Type | 설명 |
|---|---|
| `Community` | 커뮤니티 소개 |
| `Course Review` | 강의평가 소개 |
| `Timetable` | 시간표 소개 |
| `Progress` | 진행 상태 |
| `Lock` | 잠금/인증 안내 |

---

### 에셋 전체 목록

| 컴포넌트명 | 섹션 | 사이즈 | 변형 수 |
|---|---|---|---|
| `global_Img_Placeholder` | 커뮤니티 | — | 2 (Light/Dark) |
| `global_Img_VideoLoading` | 커뮤니티 | — | 2 (Light/Dark) |
| `CommunityProfile` | 커뮤니티 | 96×96px | 10종 |
| `global_Img_ProfileImage` | 커뮤니티 | 96×96px | 11종 |
| `global_Img_Category` | 커뮤니티 | 96×96px | 8종 |
| `global_Img_IDCardSample` | 커뮤니티 | — | 1종 |
| `global_Img_IDCardProfile` | 학교 인증 | 480×480px | 5종 |
| `global_Img_IDCardIllust` | 학교 인증 | 894×540px | 1종 |
| `global_Img_IDCardUnivLogo` | 학교 인증 | 600×600px | 21종 |
| `global_Img_Banner` | Common | 144×144px | 8종 (4×Light/Dark) |
| `global_Img_UnivLogo` | 회원가입 | 120×120px | 21종 |
| `global_img_onboarding` | 회원가입 | 840×840px | 5종 |

---

## 6. Icon System

> Figma 페이지: `3:2 (ㄴ Icon)`  
> 아이콘 제작 후 기능별 그룹(communication, account 등)에 우선 배치. 탭별 그룹핑 불가 시 기능별 그룹에 위치.

### 사이즈 시스템

| 사이즈 | 용도 |
|---|---|
| 24px | 표준 아이콘 (기본) |
| 20px | 중형 아이콘 |
| 16px | 소형 아이콘 |
| 14px | ETC/micro 아이콘 |
| 11px | 최소 아이콘 |
| 32px | 큰 아이콘 (프로필 영역 등) |
| 48px | 일러스트형 아이콘 |
| 80px | 대형 빈 상태(empty state) 등 |

### 파일 포맷 규칙

| 포맷 | 기준 |
|---|---|
| **SVG** | 단색 단순 형태 (기본값) |
| **PNG (light + dark 2벌)** | 2가지 이상 컬러 / 복잡한 형태 / 상태 변화(닷배지 등)가 있는 아이콘 |

> PNG 아이콘은 반드시 `light` / `dark` 테마 2벌 제공. 상태변화가 있는 아이콘(예: notice_new, join_new)은 모두 ETC(png)로 분류.

### 프로퍼티 네이밍 컨벤션

```
Property 1 = <icon_name>
Property 2 = filled | outlined
Property 3 = on | off          (토글 상태가 있는 아이콘만)
```

---

### 그룹별 아이콘 목록

#### Navigation / Tab

| 이름 | 변형 |
|---|---|
| `home` | — |
| `search` | default |
| `search_failed` | — |

#### Communication (25종)

| 이름 | 변형 |
|---|---|
| `article` | filled |
| `file` | outlined |
| `community` | outlined |
| `scrap` | filled / outlined |
| `like` | filled / outlined |
| `send` | filled / outlined |
| `comment_chat` | filled |
| `board` | filled |
| `comment` | filled / outlined |
| `chat` | filled / outlined |
| `add_chat` | outlined |
| `reply` | outlined |
| `notice` | filled / outlined |
| `edit` | outlined |
| `poll` | outlined |
| `hashtag` | outlined |
| `hot` | filled |
| `question` | filled |
| `classroom` | filled |
| `pin` | filled / outlined |
| `poke` | on / off |

#### Timetable (10종)

| 이름 | 변형 |
|---|---|
| `timetable` | filled / outlined |
| `week` | outlined |
| `today` | outlined |
| `qr` | outlined |
| `email` | outlined |
| `style` | outlined |
| `widget` | outlined |
| `score` | outlined |

#### Arrow (6종)

| 이름 | 변형 |
|---|---|
| `left` | — |
| `right` | — |
| `up` | — |
| `down` | — |
| `back` | — |
| `top` | — |

#### Account (10종)

| 이름 | 변형 |
|---|---|
| `user` | filled / outlined |
| `user_chat` | filled |
| `user_certificated` | filled |
| `friend` | outlined |
| `add_friend` | outlined |
| `setting` | filled / outlined |
| `lock` | filled / outlined |

#### Photography (6종)

| 이름 | 변형 |
|---|---|
| `camera` | filled / outlined |
| `image` | filled / outlined |
| `add_image` | outlined |
| `play` | filled |

#### Lecture (4종)

| 이름 | 변형 |
|---|---|
| `review` | outlined |
| `write_review` | filled |
| `star` | filled / outlined |

#### Toggle (12종)

| 이름 | 변형 |
|---|---|
| `notification` | outlined·on / outlined·off / filled·on / filled·off |
| `radiobutton` | outlined·on / outlined·off |
| `check_circle` | outlined·off / filled·on |
| `sound` | filled·on / filled·off |
| `show` | outlined·on / outlined·off |

#### Calendar (9종)

| 이름 | 변형 |
|---|---|
| `appointment` | outlined |
| `time` | filled / outlined |
| `calendar` | outlined |
| `swap_calendar` | outlined |
| `swap_timetable` | outlined |
| `location` | filled / outlined |
| `until` | outlined |

#### Commerce (2종)

| 이름 | 변형 |
|---|---|
| `benefit` | — |
| `point` | — |

#### Control (26종)

| 이름 | 이름 | 이름 |
|---|---|---|
| `add` | `minus` | `close` |
| `close_circle` | `delete` | `block` |
| `check` | `exit` | `upload` |
| `download` | `share` | `sorting` |
| `copy` | `more` | `flip` |
| `retry` | `resend` | `recall` |
| `ask` | `warning` | `information` |
| `exclude` | `check_circle` | `report` |
| `list` | `link` | — |

#### Brand (1종)

| 이름 | 설명 |
|---|---|
| `campuspick` | 앱 브랜드 로고 아이콘 |

---

### ETC Icons (SVG, 소형 ~14px)

폼 컨트롤·인디케이터 전용 micro 아이콘입니다.

| 이름 | 크기 | 설명 |
|---|---|---|
| `check_mini_on` / `check_mini_off` | 14px | 체크박스 체크 상태 |
| `check_line` | 14px | 선형 체크 |
| `checkmark` | 11×8px | 체크 마크 |
| `radio_mini_on` / `radio_mini_off` | 12px | 라디오버튼 |
| `delete` | 16px | 삭제 |
| `done` | 16px | 완료 |
| `toggle_on` / `toggle_off` | 32×20px | 토글 스위치 |
| `toggle_mini_on` / `toggle_mini_off` | 20×12px | 미니 토글 |
| `rating_star` | 10px | 별점 (전체) |
| `rating_star_left` / `rating_star_right` | 5×10px | 별점 반쪽 |
| `dot_small` | 4px | 소형 닷 인디케이터 |
| `dot_large` | 6px | 대형 닷 인디케이터 |
| `new` | 12px | NEW 뱃지 |

### ETC Icons (PNG, 컬러·복합, light/dark 2벌)

| 이름 | 크기 | 설명 |
|---|---|---|
| `anonym_on` / `anonym_off` / `anonym_disabled` | 48px | 익명 프로필 (활성/비활성/불가) |
| `question_on` / `question_off` | 48px | 질문 프로필 |
| `manager` / `me` | 16px | 채팅방 역할 배지 |
| `notice` / `notice_new` | 24px | 공지 아이콘 (NEW 상태 포함) |
| `reply` | 24px | 답글 |
| `menu` / `menu_new` | 24px | 메뉴 (NEW 상태 포함) |
| `join` / `join_new` | 16px | 참여 (NEW 상태 포함) |
| `rating_star_yellow700` | 10px | 채워진 별 (Yellow700) |
| `rating_star_gray400` | 10px | 빈 별 (Gray400) |
| `rating_star_left_yellow700` | 5×10px | 반쪽 별 (좌) |
| `rating_star_right_gray400` | 5×10px | 반쪽 별 (우) |
| `myarticle` / `mycomment` / `bestarticle` | 24px | 마이페이지 활동 |
| `haksik` / `classroom` / `bookstore` / `study` | 24px | 캠퍼스 서비스 |

---

## 6. Logo

> Figma 페이지: `906:207 (ㄴ Logo)`  
> 서비스명: **EVERYTIME** — 대학 커뮤니티 앱 브랜드

### 로고 변형 체계

| 변형 | 컴포넌트명 | 크기 | 용도 |
|---|---|---|---|
| Full Logo · Lightmode | `Img_Global_Full` | 840 × 118px | 스플래시, 마케팅, 밝은 배경 |
| Full Logo · Darkmode | `Img_Global_Full` | 840 × 118px | 어두운 배경 위 |
| Mini Logo | `Img_Global_Mini` | 258 × 36px | 네비게이션 바, 컴팩트 헤더 |
| Icon Mark · Default | `Img_Logo` | 768 × 768px (max) | 앱 아이콘, 스플래시, 단독 브랜드 노출 |
| Icon Mark · Disabled | `Img_Logo` | 768 × 768px (max) | 비활성·배경 처리 용도 |

### 컴포넌트 Props

```
// Full Logo
type = "Full"
name = "Logo"
theme = "Lightmode" | "Darkmode"

// Mini Logo
type = "Mini"
name = "Logo"

// Icon Mark
(theme props 없음 — 별도 인스턴스로 분리)
```

### 아이콘 마크 구조

로고 심볼은 **3개의 독립 SVG 레이어**로 구성됩니다.

```
Img_Logo (768×768px)
├── eye    (우상단 원형 점)
├── nose   (중앙 빨간 위치핀 — 두 테마 공통 동일 에셋)
└── mouth  (하단 U자형 아크)
```

| 파트 | Default 색상 | Disabled 색상 |
|---|---|---|
| `eye` (원형 점) | `#292929` (Gray800) | `#e0e0e0` (Gray300 계열) |
| `nose` (위치핀) | `#f91f15` (Red700) | `#f91f15` (Red700, 동일) |
| `mouth` (U 아크) | `#292929` (Gray800) | `#e0e0e0` (Gray300 계열) |

> nose(빨간 핀)는 Default/Disabled 공통으로 동일 에셋 사용 — 항상 Red700 유지.

### 색상 사용 규칙

| 상황 | Wordmark | Symbol (eye+mouth) | Accent (nose) |
|---|---|---|---|
| 밝은 배경 (Lightmode) | `#292929` | `#292929` | `#f91f15` |
| 어두운 배경 (Darkmode) | `#ffffff` | `#ffffff` | `#f91f15` |
| 비활성·배경 노출 | `#e0e0e0` | `#e0e0e0` | `#f91f15` |

### 파일 포맷

| 에셋 | 포맷 | 비고 |
|---|---|---|
| Full Logo | SVG | Lightmode / Darkmode 각 1파일 |
| Mini Logo | SVG | 단일 파일 |
| Icon Mark | SVG × 3 파트 | eye, nose, mouth 분리 — 조합하여 사용 |

---

## 7. Figma File Structure

| 페이지 ID | 페이지명 | 내용 |
|---|---|---|
| `4:2660` | Foundation | 하위 페이지 그룹 |
| `906:207` | ㄴ Logo | 로고 |
| `6501:658` | ㄴ Typography | 타입 스케일 (iOS / Android) |
| `3:2` | ㄴ Icon | 아이콘 세트 |
| `3468:120` | ㄴ Color | 컬러 팔레트 (Light/Dark) |
| `70:1395` | ㄴ Image | 이미지 에셋 |
| `6510:2670` | ㄴ Shadow | 그림자 스타일 |
| `6510:2671` | ㄴ Spacing | 스페이싱 시스템 |
| `6510:2674` | ㄴ Ratio | 비율 시스템 |
| `0:1` | Component | 컴포넌트 최상위 |
| `6510:2654` | ㄴ OS | OS 전용 컴포넌트 |
| `4:2661` | ㄴ Element | 핵심 UI 컴포넌트 (459종) |
| `4:2662` | ㄴ Featured | 피처 전용 컴포넌트 |
| `1:963` | Cover | 파일 커버 |
