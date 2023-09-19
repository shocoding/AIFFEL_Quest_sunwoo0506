# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 오선우
- 리뷰어 : 이혁희


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제를 해결하는 코드가 제출 되었습니다.
    - 단어를 입력 받는다.
    ```
    text = input("입력값: ")

    a = text.replace(" ","")   #입력문장 공백제거, 문장일 경우 띄어쓰기를 제거하기 위해 replace() 사용
    ```
    - 단어를 뒤집어서 출력한다.
    ```
    cotext = a[::-1]

    print("뒤집힌 단어는", str(cotext), "입니다.")
    ```
    - 뒤집은 단어가 원래의 단어와 같은지 여부를 출력한다.
    ```
    if a == cotext :
      print("회문입니다")
    else:
      print("회문 아닙니다")
    ```
    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 잘 이해 되었습니다.
    - 단어를 뒤집는 코드에 주석이 있으면 좋겠습니다.
    ```
    # 단어를 뒤집는다.
    cotext = a[::-1]
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 “해결한 기록을 남겼거나” 
”새로운 시도 또는 추가 실험을 수행”해봤나요?**
    - 간단한 코드라 문제해결 과정이 필요 없었을 것 같습니다.
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 회고가 작성되어 있지 않습니다.
    
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드가 간결하게 잘 작성되었습니다.
    - 코드가 간결하여 함수화 할 만한 부분이 보이지 않습니다.
    - 단어를 뒤집는 코드가 너무나도 완벽하고 간결하게 작성되었습니다. 같은 기능을 만드는데 너무 길고 복잡한 과정을 거쳐서 만든 제가 부끄럽고 많은 자극을 받았습니다. 감사합니다.
    ```
    cotext = a[::-1]
    ```

# 참고 링크 및 코드 개선