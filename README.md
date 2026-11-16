# CoachC

코치씨 — 지역 기반 검증 골프 프로 매칭 서비스.

## public/index.html
프로 프로필 자료 제출 페이지. 제출 데이터는 Supabase(coachxai) `coachc.pro_submissions` 테이블과 `coachc-submissions` 스토리지 버킷에 저장됩니다.

## 페이지
- `/` 랜딩페이지·체험 신청
- `/pro/` 프로 자료 제출
- `/pay/` 결제 (토스페이먼츠)
- `/admin/` 운영자 (체험 신청·결제 관리)
