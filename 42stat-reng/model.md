2024\.04.01(월)

1. 명언?? -
   1. F ↔︎ S db api →
      1. ```
         string wise
         ```

‌

1. 현재 여행 현황
   1. 지금 사람들이 참여하는 과제 - A ↔︎ S 과제명, 참여인원
      1. ```c
         ‌struct IngSubject[] {
           str : name, //과제 명
           int : count //과제 참여 인원
         }
         ```
   2. 여행 중인 유저 레벨 분포
      1. ```
         int[] : lv //인덱스 lv, 값 유저수
         ```
   3. 평가 포인트 랭킹
      1. ```
         struct RankingEvalPoint[] {
           string : URLImg, //유저 사진 URL
           string : name, //유저 이름
           int : point //유저 포인트
         }
         ```

‌

1. 이너서클-멤버 관련 통계
   1. 직전 회차 시험 통과율
      1. ```
         struct ExamSuccessRate {
           LocalDateTime :  date, //iso8601
           string place, //시험 장소
           double count[] //합격 인원/전체인원(2~6 순서대로 인덱스), 소숫점 .2까지
         }
         ```

‌

1. 역대 기록
   1. 보유 월렛 랭킹
      1. ```
         struct RankingWallet[] {
           string : URLImg, //유저 사진 URL
           string : name, //유저 이름
           int : point //유저 월렛 달러
         }
         ```

‌

1. 랭킹 (깃수별, 코알리숑별), 주간 월간 누적
   1. ```
      struct Rank[] {
        string : urlImg, //유저 사진 URL
        string : name, //유저 이름
        int : lv, //유저 레벨
        int : evCount, //유저 평가 포인트
        int : commentCount //유저 평가 코멘트 개수
      }
      ```
   2. 종합 평균(추후)
   3. 레벨
   4. 평가 횟수
   5. 코멘트 길이

‌

1. 내정보
   1. 보너스 프리즈(휴가) 몇 일 받았는지
      1. ```
         int days
         ```

‌

추가 기능

1. 스터디룸