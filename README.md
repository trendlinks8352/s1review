# ReadBrain — 영어 독해 오답노트

## 배포 방법 (Netlify Drop)

1. 이 폴더 통째로 Netlify Drop에 드래그하면 됩니다.
2. `index.html` — 메인 앱
3. `data.txt` — 빈칸 단어 문장 (선택)

## data.txt 형식
```
한 줄에 한 문장, 외울 단어는 [[단어]] 로 감싸기
The policy was [[controversial]] among experts.
```

## 기능
- 4가지 오류 유형 퀴즈 자동 생성 (인덱싱/타겟팅/패러프레이징/논리)
- 망각곡선 기반 복습 (1일 → 3일 → 7일)
- 틀린 퀴즈는 1일로 초기화
- 연속 정답 스트릭 트래킹
- 모바일 최적화 플래시카드 UI
