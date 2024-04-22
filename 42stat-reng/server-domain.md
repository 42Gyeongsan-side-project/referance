## User domian

---

- Long userId (pk) //db 자체 생성
- String intraId
- String URLIMG
- String token
- String refreshToken
- String code
- int level
- int evalPoint
- int walletPoint
- int freezCount;

## Subject domain

---

- Long subjectId (pk)
- String subjectName;
- int count;

## Exam domain

---

- Long  examID (pk)
- LocalDateTime dateTime
- String place
- double[] count