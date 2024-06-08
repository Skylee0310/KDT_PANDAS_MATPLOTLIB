# KDT Pandas, Matplotlib 수업 과정 미니프로젝트

### 📝 주제 - 사이버 폭력

| 📄 개인 주제 | 사이버 폭력의 성인 및 학생 가해자 유형 분석 |
| --- | --- |
| 🙍🏻‍♂️ 팀원  | 임소영, 이화은, 임소영, 전진우 |
| 📊 PPT | [링크](https://buly.kr/87z6wbF) |

✏  **가설 -** 어떤 경우에 사이버 폭력 가해자가 될 가능성이 높은가?

- 학생 가해자
    - 가정 형편이 어렵거나 학업 성적이 좋지 못한 경우
- 성인 가해자
    - 소득이 적거나 무직인 경우

✏  **데이터**

- **국가 통계 포털**
    - 사이버폭력 가해경험
    - 사이버폭력 가해 동기
    - 사이버폭력 가해 대상
    - 가해 후 심리 상태
    

✏  **자료 분석**

- **성인 가해자 :**
    - **가해경험률 최고치 기록 집단**

        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/d062a9fb-f49c-44d3-8324-21a3c2fed4c4)

        - 직업군 : 1) 사무직 2) 무직
        - 소득별 : 1) 월평균 가구 소득 400만원 이상 ~ 500만원 미만 구간 2)500만원 이상 600만원 미만 구간
        - **가해 동기** :
      
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/282ae048-6571-40f0-94ca-c1bcfc552592)      
          - 재미나 장난으로 스트레스 해소를 위해 (100 만원 이상~200만원 미만 구간)
          - 상대방이 먼저 그런 행동을 해서 보복하기 위해 (700만원 이상 구간 → 100만원 이상 200만원 미만 구간)
      
    - 가해 대상 :
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/16a88b84-a97d-450d-9652-0482f6f2ee7f)
          - 전혀 모르는 사람 비율 압도적
    
    - 가해 후 심리 상태 :
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/44a26158-83e2-46ad-b305-6ab382968d91)
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/3c263aa6-b227-411e-8c0a-58fb91f46fd1)
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/cecfd637-01e5-422d-a707-e50106c8b5a3)

        - 정당하다
            - 주부 집단 →  무직/기타 집단
            - 700만원 이상 → 100만원 미만
        - 문제가 생길 것 같아 걱정이 되었다
            - 주부 집단
            - 700만원 이상 → 100만원 미만
        - 흥미롭고 재미있다
            - 주부 집단
            - 200만원 미만
        - 상대방에게 미안하고 후회스러웠음
            - 학생 집단
    
- **학생 가해자 :**
- 가해경험율
    ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/d835dba7-ccc5-4554-bdb1-8e6791eefaea)

    - 학업 성적별
        
        ⇒ 성적이 낮을 수록 비율 상승, 그러나 큰 차이는 없음.
      
    - 가정 형편별
    
        ⇒ 중위층 집단 가장 높음. 큰 차이는 없음.
        
    - 가해 동기
      ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/0f6e5bba-c7bc-472c-875a-99ae1175db40)

        - 보복 → 성적이 중위권인 경우, 가정 형편이 상위권인 경우의 비율 高
        - 특별한 이유 없음 → 성적이 하위권인 경우, 가정 형편이 하위권인 경우 비율 高


      - 가해 후 심리 상태
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/4eea7d8c-c91d-42f2-9687-a20f71add387)
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/f4e6ad29-ddbe-4c1f-9c9c-e4ead94dbfb8)
        ![image](https://github.com/Skylee0310/KDT_PANDAS_MATPLOTLIB/assets/155412049/d890d163-5121-4789-bee0-939941dd0919)
        ※ 성인에 비해 ‘정당하지 않다’ 비율 高
        
        - 문제가 생길 것 같아 걱정이 되었다
            - 성적 중위권 학생 집단
        - 흥미롭고 재미있다
            - 대개 그렇지 않다 선택.
        - 상대방에게 미안하고 후회스러웠음
            - 성적 중위권 학생 집단
            - 소득수준 중위층이 가장 높았음.
         
✏ 결론

⇒ 성인 무직 집단의 가해 경험율이 사무직에 이어 두 번째로 높았지만, 월 평균 가구 소득이 중산층인 집단의 사이버 폭력 가해 경험율이 더 높은 점을 보아 소득과 직업군 사이의 사이버 폭력 가해와의 상관관계는 높지 않다는 것을 알 수 있다.

⇒ 학생 집단의 경우 성적과 가정 형편이 사이버 폭력 가해와의 상관 관계가 높지 않으며, 오히려 가해 후 심리 상태 자료를 보면 성인 가해자에 비해 대체로 자신의 잘못을 인식하고 있는 것을 알 수 있다.



