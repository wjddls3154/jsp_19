# jsp_19 : jquery 이용 3 (Atom에서만 됬음)

![image](https://user-images.githubusercontent.com/37132897/158186399-25391e5d-5eca-47ee-ab35-7a2cbf2e8090.png)
- 버튼 누르기 전

![image](https://user-images.githubusercontent.com/37132897/158186470-0d4d1998-94c8-43b3-8a8c-db20ef532821.png)
- 처음 버튼 눌렀을 때, html은 mark가 적용되어 나오고, text는 mark도 text로 나온다. 그리고, mark 된 내용이 사라지기 전 모습

![image](https://user-images.githubusercontent.com/37132897/158186743-64a5ed0b-8174-4498-a7f7-03a2810bd967.png)
- 처음엔 mark된 내용이 보이다가, fadeout으로 점차 사라지다 fadein으로 다시 보이다가 2번 반복하고 끝남.

      $('#two').click(

        function f() {

          $('h1:first').html('<mark>반갑습니다~!!!!</mark>').fadeOut(3000).fadeIn(3000).fadeOut(3000).fadeIn(3000); // jquery 사용 4

          $('h1:last').text('<mark>반갑습니다~!!!!</mark>'); // jquery 사용 5

        }

      );


      // 메소드 (속성 값 변경, DOM 탐색, css, 이벤트, 효과, etc)

      // .text

      // .html

      // .val

      // .hide

      // .show

      // .fadeout : 점차 사라지는 기능

      // .fadein : 점차 나타나는 기능
