# ⚾ 기아타이거즈 — 나만의 퀴즈

기아 타이거즈 팬이라면 100점 받아야 하는 퀴즈

## 나만의 퀴즈

| | |
|---|---|
| 주제 | ⚾ 기아 타이거즈 홈런 |
| 내용 | 2023~2025년, 기아 타자 다섯 명의 홈런 |
| 출처 | [Kaggle · KBO Player Stats 1982-2025 (netsong)](https://www.kaggle.com/datasets/netsong/kbo-player-stats-19822025) |

## 주소

https://github.com/zzzkse19591/gam-test

## 내가 내린 판단

- 이유: 그냥 궁금하다
- 고른이유: 쉽게 받을 수 있고, 데이터가 다 있어서

## 돌려보기

```
python -m http.server 8000      # index.html 을 더블클릭하면 안 됩니다
```

## 데이터가 오는 길

```
   [내 노트북]                                   [인터넷]

   tools/fetch_all.py      공개 데이터 6곳에서 받기 (키·로그인 없음)
        ↓  data/raw/  약 19MB   ← git 에도 배포에도 올라가지 않습니다
   tools/build_topics.py   원본에서 문항 계산
        ↓
   topics/*.json  약 40KB  ← 이것만 올라갑니다
```

원본을 브라우저로 보내서 거기서 평균을 내는 게 아닙니다. **평균은 내 노트북에서 미리
내고, 그 결과만 싣습니다.** 그래서 폰에서 즉시 뜹니다.
