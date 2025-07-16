# Erenfest - 개인 도서관 관리 시스템

개인 소장 도서 목록을 온라인에서 확인할 수 있는 디지털 도서관 관리 시스템입니다.

## 주요 기능

- 📚 소장 도서 목록 조회 및 검색
- 📱 바코드 스캔을 통한 ISBN 자동 인식
- 🏷️ 카테고리별 분류 및 필터링
- 📱 반응형 웹 디자인

## 기술 스택

- **Frontend**: Next.js, React, TypeScript
- **UI**: Tailwind CSS, Lucide React
- **Build Tool**: Turbo (모노레포)
- **Code Quality**: ESLint, Prettier

## 프로젝트 구조

```
erenfest/
├── apps/
│   └── library/          # 메인 라이브러리 애플리케이션
├── packages/
│   ├── ui/              # 공유 UI 컴포넌트
│   ├── eslint-config/   # ESLint 설정
│   └── typescript-config/ # TypeScript 설정
```

## 시작하기

### 필요 조건

- Node.js 24 이상
- Yarn 4.9.1

### 설치 및 실행

```bash
# 의존성 설치
yarn install

# 개발 서버 실행
yarn dev

# 빌드
yarn build
```

### 라이브러리 앱만 실행

```bash
# 라이브러리 앱 개발 서버
yarn dev --filter=library

# 라이브러리 앱 빌드
yarn build --filter=library
```

## 스크립트

- `yarn dev` - 개발 서버 실행
- `yarn build` - 프로덕션 빌드
- `yarn lint` - 코드 린팅
- `yarn format` - 코드 포맷팅
- `yarn check-types` - 타입 체크

## 추가 정보

프로젝트의 상세한 설계 및 요구사항은 [AGENTS.md](./AGENTS.md)를 참조하세요.
