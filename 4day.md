* echo [option] ... [string]
-> 문자열 출력 / ...는 여러개의 옵션이나 문자열을 줄 수 있다는 것.

* cp [option] ... Source Dest 
-> 복사 명령어 / cp ./aaa.txt /home/dir/new_aaa.txt
aaa.txt를 /home/dir에 새로운이름으로 복사해서 붙여놓아라

```
가상의 preheat 커맨드에 대한 가상의 매뉴얼 페이지에 따르면 :
NAME
  preheat - preheat the oven
SYNOPSIS
  preheat [-cef] [-t number] [-d number]
다음중 preheat 커맨드를 실행하는 잘못된 방법은??

1. preheat -c
2. preheat -t 275
3. preheat -ed
4. preheat -c -d 60

정답은 3.
```

* man -k ____
-> 단어로 메뉴얼 검색 / man -k printf (쉘 내장은 메뉴얼검색이 안됨..)
  
-> 대신 help로 검색이 됨 / help cd
  
* type _____
-> 타입을 알수있다. /type printf (shell명령어인지 , 폴더인지 , 파일인지..등)
  ![image](https://github.com/yeongji-kim/LCL/assets/75402057/5d08db8e-33b0-4593-93d6-18ca0f4eb8bf)


  
