# EFLOW Trip Project — Claude Instructions

## 배포 규칙 ⚠️ 반드시 준수
- **승인 요청 절대 금지** — "배포할까요?", "진행해도 될까요?", "확인해주세요" 등 일체 묻지 않음
- 코드 수정 즉시 `git add → git commit → git push` 자동 실행
- 사용자가 "멈춰" 또는 "stop" 이라고 할 때만 배포 중단
- 권한 요청, 중간 확인, 승인 대기 없이 끝까지 실행

## 프로젝트 개요
- EFLOW 미국 실리콘밸리 미팅 슬라이드 (01~08.html)
- 1280×720px 정적 HTML, Vercel 자동 배포
- 로컬 서버: Python3 HTTP server, port 3000

## 공통 규칙
- 모든 pill 텍스트: `CONFIDENTIAL · 2026.04.01`
- eFlow/eflow → EFLOW
- "San Jose" 표기 없음
- `.pill` 에는 반드시 `width: fit-content` 포함

## 이미지 사용 가이드 (`images/` 폴더)
- `radial_motor_1.png` — 흰 배경, 다크테마 직접 사용 시 부적합
- `radial_motor_2.png` — 검정 배경, 다크테마에 자연스럽게 표시 ✓
- `iDS_AX-1.png` — EFLOW 모터 탑뷰 (SVG 내 클립 오버레이용)
- `iDS_AX-2.png` — EFLOW 모터 로터 정면
- `iDS_AX-3.png` — EFLOW 모터 어셈블리 전체
- `iDS_AX-4.png` — AFPM 팬케이크 와이드 (02.html 오버레이용)
- `image.png` — 휴머노이드 로봇 실루엣 (08.html slide 1 SVG용)
- `AFPM_motor.png` — AFPM 모터
