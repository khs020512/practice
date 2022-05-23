# 조사내용 READM파일로 저장하기

## 리눅스 명렁어 정리
|제목|내용|설명|
|----|---|---|
|top|작업 표시|top 명령어는 현재 OS의 상태를 나타내주는 CLI 어플리케이션이다. 메모리 사용량, CPU 사용량 등을 나타낸다.|
|ps|현재 공정의 개요 보고|테스트3|
|jobs|작업의 상태 표시|테스트3|
|kill|프로세스 종료 명령|테스트3|
## top 명령어
> top 명령어는 현재 OS의 상태를 나타내주는 CLI 어플리케이션이다. 메모리 사용량,CPU 사용량 등을 나타내며 top를 실행하는 동안에는 주기적인 업데이트로 실시간에 근접한 내용을 보여준다.

![Top](https://user-images.githubusercontent.com/97209803/169724260-36fea52a-3f68-438b-93f9-f5ae6464e542.PNG)
# top - 시스템 현재 시간, OS가 살아있는 시간, 유저 세션수(System time, uptime and user sessions)
> top - 09:49:02 : 현재 시간을 나타냄.
 
> up 0 min : OS가 살아있는 시간을 나타냄.

> 0 users : 유저 세션수를 나타냄.

# load average
> CPU Load의 이동 평균을 표시한다.

> 앞에서 부터 1분, 5분, 15분에 대한 평균값을 나타냄.

> CPU Load는 CPU가 수행하는 작업의 양을 나타낸다.

> 코어수 * 1.0이 CPU의 한계치를 나타낸다.

> 만약 100%가 넘어간다면 CPU에서 처리하지 못하고 대기중인 프로세스가 있는것이다.

# Tasks
> Tasks는 현재 ㅡ로세스들의 상태를 나타내는 영역이다.

> running : 실행중인 프로세스

> sleeping : 대기중인 프로세스

> stopped : 종료된 프로세스

> zombies : 좀비상태인 프로세스


## vim 매크로 설정하는 방법
1) 기본모드에서 q + (매크로로 사용하고 싶은 알파벳) => 매크로 기록 
2) --recording-- 이라고 뜨면 매크로로 저장하고 싶었던 코드나 문장을 작성한다.
3) 기록이 끝났다면 기본모드에서 q를 다시 입력한다.

## vim 설정한 매크로 작동하는 방법
1) 기본모드에서 @ + (매크로로 지정한 알파벳) =>매크로 실행
2) @ + @는 가장 최근에 실행한 매크로가 실행됨.

## 예시
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


