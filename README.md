# 조사내용 READM파일로 저장하기


**vim 매크로 설정하는 방법**
1) 기본모드에서 q + (매크로로 사용하고 싶은 알파벳) => 매크로 기록 
2) --recording-- 이라고 뜨면 매크로로 저장하고 싶었던 코드나 문장을 작성한다.
3) 기록이 끝났다면 기본모드에서 q를 다시 입력한다.

**vim 설정한 매크로 작동하는 방법**
1) 기본모드에서 @ + (매크로로 지정한 알파벳) =>매크로 실행
2) @ + @는 가장 최근에 실행한 매크로가 실행됨.

ex)

![recording qh](https://user-images.githubusercontent.com/97209803/169718743-30419a34-d552-409c-b898-818dc101bc68.PNG)

1) **Q + h를 매크로로 지정한다.**
```py
print("hello wolrd")
```
2) **--recording-- 중 위의 코드를 매크로로 입력한 후 기본 모드에서 q를 입력한다.
3) **기본모드에서 @ + h를 눌러본다.**
4) **@ + h를 누른 이후 @ + @를 눌러본다.

![macro](https://user-images.githubusercontent.com/97209803/169718933-b5bf9dd8-f3a4-42ad-ada8-88d0918b2cf7.PNG)
