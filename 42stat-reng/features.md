2024.04.01(월)

issue : blackhole 기간 체크
db 업데이트 주기: 1hr
‌

1. 명언?? - F ↔︎ S db api → String wise

‌

1. 현재 여행 현황 -
   1. 일간 평가 횟수 추이 X
   2. 일간 팀 제출 횟수 추이 X
   3. 월간 블랙홀 인원 추이 X
   4. 지금 사람들이 참여하는 과제 - A ↔︎ S 과제명, 참여인원
      1. F : struct (str : name, int : count)
   5. 여행 중인 유저 레벨 분포
      1. F : struct(int : lv, int : count)
   6. 평가 포인트 랭킹
      1. F : struct(string : URLImg, String : name, int : point)

‌

1. 이너서클-멤버 관련 통계
   1. 서클 별 평균 통과 기간 X
   2. 유저 비율 X
   3. 직전 회차 시험 통과율
      1. struct ex(date date(iso8601, string place, int count[])
      2. double count[2, 3, 4, 5, 6]; //percentage .2
   4. 언제 블랙홀에 많이 빠질까? X

‌

1. 역대 기록
   1. 역대 총 평가 횟수 X
   2. 평가 코멘트 글자 수 X
   3. 평균 피드백 글자수 X
   4. 여행 중인 유저 수 추이 X
   5. 보유 월렛 랭킹
      1. struct : (string : URLImg, String : name, int : point)

‌

1. 코알리숑 비교
   1. 코알리숑 스코어 변동 추이 X
   2. 코알리숑 우승 횟수  x
   3. 누적 코알리숑 스코어 X
   4. 월간 코알리숑 티그 횟수 X

‌

1. 랭킹 (깃수별, 코알리숑별), 주간 월간 누적
   1. server : struct Rank[](string : urlImg, string : name, int : lv, int : evCount, int : commentCount)
   2. 종합 평균
   3. 레벨
   4. 경험치 증가량 X
   5. 코알리숑 스코어 X
   6. 평가 횟수
   7. 코멘트 길이
   8. 프리즈 개수 X

‌

1. 평가 로그 검색기 X
   1. 누군가 → 누군가 / 모든 서브젝트 / 모든 플래그 / 최신 순

‌

1. 내정보 X
   1. ???

‌

1. 검색 기능 X
   1. 유저명 또는 프로젝트명 입력

‌

1. 설정
   1. 문의하기
      1. DB에 쌓기
   2. 로그아웃
   3. 회원탈퇴
      1. ‌

‌

추가 기능

1. 보너스 프리즈(휴가) 몇 일 받았는지
   1. 내 정보에 띄우기
2. 누가 코멘트를 제일 썼는지 X
3. 누가 평가를 제일 많이 다녔는지 X
4. 스터디룸