vim 매크로 설정하는 방법
기본모드에서 q + (매크로로 사용하고 싶은 알파벳) => 매크로 기록
ex) q + a 를 기본모드에서 실행한다. 
-> --recording-- 이라고 뜨면 매크로로 저장하고 싶었던 코드나 문장을 작성한다.
-> 기록이 끝났다면 기본모드에서 q를 다시 입력한다.
vim 설정한 매크로 작동하는 방법
기본모드에서 @ + (매크로로 지정한 알파벳) =>매크로 실행
ex) q+ a=>abcdefghijklmnopqrstuvwxyz
-> @ + a => abcdefghijklmnopqrstuvwxyz 출력
@ + @는 가장 최근에 실행한 매크로가 실행됨.
ex) q + a를 가장 최근에 실행했다면 -> @@를 누르면 @ + a가 실행됨.
