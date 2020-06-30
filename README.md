# runningman_app
 TV프로그램 [런닝맨]을 모티브로 만든 어플입니다. <br>
 제한 시간 4분 동안 캐릭터(이름표)/점령지를 카메라로 촬영하여 캐릭터의 체력을 감소시키기나 점령지를 많이 차지하여 승리하는 게임 어플입니다. <br>
 저는 해당 프로젝트에서 안드로이드 Camera2APIs를 이용하여 게임방 내 카메라 제어를 하였고, <br>
 찍은 사진을 서버로 전송한 후 서버에서 학습된 이미지와 관련된 응답값을 주는 기능을 개발하였습니다.


기능
----
1. 회원가입, 로그인
2. 게임방 생성, 게임방 입장
3. 카메라 촬영(학습된 이미지 : 점령지 4개, 캐릭터 4개)
4. 제한시간(4분) 후 우승자 결정


나의 구현기능
-------------
1. 게임방 카메라 제어
2. 학습된 이미지 처리(카메라로 찍은 사진을 서버로 보내, 학습된 이미지가 맞는지 응답값)


사용기술
--------
● 서버: AWS

● 웹 서버: Apache, Flask

● 데이터베이스: Mysql

● 언어: Java, Python, PHP

● 라이브러리/API : TensorFlow, Camera2 APIs


스크린샷
---------
<div>
<img src="https://user-images.githubusercontent.com/67361330/85956232-8c2ef080-b9bf-11ea-9927-07d2694a669a.png" width="100%"></img>
<img src="https://user-images.githubusercontent.com/67361330/85956236-8fc27780-b9bf-11ea-8fb3-ffcbad177c9e.png" width="100%"></img>
<img src="https://user-images.githubusercontent.com/67361330/85956239-9224d180-b9bf-11ea-9a0e-52eecca3e971.png" width="100%"></img>
</div>


영상링크
--------
https://youtu.be/sxNRwtNzhOw


라이센스
--------
MIT License

Copyright (c) 2020 seulgikim2019

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
