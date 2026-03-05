# GC Weekly Health Pulse

GC 헬스데이터 연구소 주간 건강 동향 리포트

## 파일 구조

```
gc-health-pulse/
├── index.html        ← 디자인 엔진 (건드리지 마세요)
└── data/
    └── latest.json   ← ★ 매주 이 파일만 수정하세요 ★
```

## 최초 세팅 (한 번만)

1. GitHub 저장소 생성 후 push
2. Vercel → New Project → 저장소 선택 → Deploy
3. 완료. URL 생성됨.

## 매주 업데이트 (3줄)

```bash
# 1. data/latest.json 수정
# 2. push
git add data/latest.json
git commit -m "week 10: 3월 2주차"
git push
# → Vercel 자동 배포, 1분 내 반영
```
