# 온서산 일일 소식 데이터

서산시 공식 채널에서 매일 오전 8시에 자동 수집되는 소식 데이터입니다.

## 파일 구조
- `news/latest.json` — 항상 가장 최신 데이터 (앱이 이 URL을 fetch)
- `news/news_YYYY-MM-DD.json` — 날짜별 보관본
- `news/news_YYYY-MM-DD.md` — 사람이 읽기 좋은 요약

## 앱 fetch URL
```
https://raw.githubusercontent.com/cheon-sea/onseosan-data/main/news/latest.json
```

## 카테고리
- `city_notice` — 시정 공지
- `culture_event` — 문화·행사
- `lifelong_learning` — 평생학습
- `welfare` — 복지
- `social_media` — SNS·블로그

자동 생성: Claude 스케줄 작업 `onseosan-daily-news`
