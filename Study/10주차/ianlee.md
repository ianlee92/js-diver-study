### ๐ 2021๋ 8์ 10์ผ ํ์์ผ
# ๐ 38์ฅ ๋ธ๋ผ์ฐ์ ์ ๋ ๋๋ง ๊ณผ์ 
> ๐ก ๋ธ๋ผ์ฐ์ ์ ๋ ๋๋ง

![https://blog.kakaocdn.net/dn/cBFVi9/btrbJcog0kh/u48oBgzm32AU8k7dqsM9xK/img.png](https://blog.kakaocdn.net/dn/cBFVi9/btrbJcog0kh/u48oBgzm32AU8k7dqsM9xK/img.png)

1. HTML, CSS, ์๋ฐ์คํฌ๋ฆฝํธ, ์ด๋ฏธ์ง, ํฐํธ ํ์ผ ๋ฑ ๋ ๋๋ง์ ํ์ํ ๋ฆฌ์์ค๋ฅผ ์์ฒญํ๊ณ  ์๋ฒ๋ก๋ถํฐ ์๋ต์ ๋ฐ์
2. ๋ ๋๋ง ์์ง์ ์๋ฒ๋ก๋ถํฐ ์๋ต๋ HTML, CSS๋ฅผ ํ์ฑํ์ฌ DOM๊ณผ CSSOM์ ์์ฑํ๊ณ  ์ด๋ค์ ๊ฒฐํฉํ์ฌ ๋ ๋ ํธ๋ฆฌ ์์ฑ

    ![https://blog.kakaocdn.net/dn/mpd2T/btrbCssOVcd/znj5dZXHnkhaTKKRNcHo3k/img.png](https://blog.kakaocdn.net/dn/mpd2T/btrbCssOVcd/znj5dZXHnkhaTKKRNcHo3k/img.png)

3. ์๋ฐ์คํฌ๋ฆฝํธ ์์ง์ ์๋ฒ๋ก๋ถํฐ ์๋ต๋ ์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ ํ์ฑํ์ฌ AST(Abstract Syntax Tree: ์ถ์ ๊ตฌ๋ฌธ ํธ๋ฆฌ)๋ฅผ ์์ฑํ๊ณ  ๋ฐ์ดํธ์ฝ๋๋ก ๋ณํํ์ฌ ์คํ (์ด๋ ์๋ฐ์คํฌ๋ฆฝํธ๋ DOM API๋ฅผ ํตํด DOM์ด๋ CSSOM์ ๋ณ๊ฒฝํ  ์ ์๊ณ  ๋ณ๊ฒฝ๋ DOM๊ณผ CSSOM์ ๋ค์ ๋ ๋ ํธ๋ฆฌ๋ก ๊ฒฐํฉ)

    ![https://blog.kakaocdn.net/dn/ch2zbM/btrbEOvn0M0/2gzOKI1y3B1KMDLiQPP5q0/img.png](https://blog.kakaocdn.net/dn/ch2zbM/btrbEOvn0M0/2gzOKI1y3B1KMDLiQPP5q0/img.png)

4. ๋ ๋ ํธ๋ฆฌ๋ฅผ ๊ธฐ๋ฐ์ผ๋ก HTML ์์์ ๋ ์ด์์(์์น์ ํฌ๊ธฐ)๋ฅผ ๊ณ์ฐํ๊ณ  ๋ธ๋ผ์ฐ์  ํ๋ฉด์ HTML ์์๋ฅผ ํ์ธํ
- ๋ ๋๋ง์ ํ์ํ ๋ฆฌ์์ค๋ ๋ชจ๋ ์๋ฒ์ ์กด์ฌํ๋ฏ๋ก ํ์ํ ๋ฆฌ์์ค๋ฅผ ์๋ฒ์ ์์ฒญํ๊ณ  ์๋ฒ๊ฐ ์๋ตํ ๋ฆฌ์์ค๋ฅผ ํ์ฑํ์ฌ ๋ ๋๋งํ๋ ๊ฒ์ด๋ค.
- ์๋ฒ๋ ๋ฃจํธ ์์ฒญ์ ๋ํด ์๋ฒ์ ๋ฃจํธ ํด๋์ ์กด์ฌํ๋ ์ ์  ํ์ผย [index.html์](http://index.xn--html-jy1s/)ย ํด๋ผ์ด์ธํธ๋ก ์๋ตํ๊ณ  ๋ค๋ฅธ ์ ์  ํ์ผ์ ์๋ฒ์ ์์ฒญํ๋ ค๋ฉด ์ ์  ํ์ผ์ ๊ฒฝ๋ก์ ํ์ผ ์ด๋ฆ์ URI์ ํธ์คํธ ๋ค์ ํจ์ค(path)์ ๊ธฐ์ ํ์ฌ ์๋ฒ์ ์์ฒญํ๋ค. (ex:ย โฆ/assets/data/data.json ์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ ํตํด ๋์ ์ผ๋ก ์๋ฒ์ ์ ์ /๋์  ๋ฐ์ดํฐ๋ฅผ ์์ฒญํ  ์๋ ์๋ค. (ajax, REST API)
- HTTP(HyperText Transfer Protocol)๋ ์น์์ ๋ธ๋ผ์ฐ์ ์ ์๋ฒ๊ฐ ํต์ ํ๊ธฐ ์ํ ํ๋กํ ์ฝ(๊ท์ฝ)์ด๋ค. HTTP/1.1์ ๊ธฐ๋ณธ์ ์ผ๋ก ์ปค๋ฅ์๋น ํ๋์ ์์ฒญ๊ณผ ์๋ต๋ง ์ฒ๋ฆฌํ๋ค. ๋ฆฌ์์ค์ ๋์ ์ ์ก์ด ๋ถ๊ฐ๋ฅํ ๊ตฌ์กฐ์ด๋ฏ๋ก ์์ฒญํ  ๋ฆฌ์์ค์ ๊ฐ์์ ๋น๋กํ์ฌ ์๋ต ์๊ฐ๋ ์ฆ๊ฐํ๋ ๋จ์ ์ด ์๋ค. HTTP/2๋ ์ปค๋ฅ์๋น ๋ค์ค ์์ฒญ/์๋ต์ด ๊ฐ๋ฅํด ์ฌ๋ฌ ๋ฆฌ์์ค์ ๋์ ์ ์ก์ด ๊ฐ๋ฅํ๊ณ  ํ์ด์ง ๋ก๋ ์๋๊ฐ ์ฝ 50% ์ ๋ ๋น ๋ฅด๋ค.
- HTML ๋ฌธ์๋ฅผ ํ์ฑํ์ฌ ๋ธ๋ผ์ฐ์ ๊ฐ ์ดํดํ  ์ ์๋ ๋ธ๋๋ค๋ก ๊ตฌ์ฑ๋ ํธ๋ฆฌ ์๋ฃ๊ตฌ์กฐ์ธ DOM(Document Object Model)์ ์์ฑํ๋ค. ์ฆ, DOM์ HTML ๋ฌธ์๋ฅผ ํ์ฑํ ๊ฒฐ๊ณผ๋ฌผ์ด๋ค. (๋ฐ์ดํธ -> ๋ฌธ์ -> ํ ํฐ -> ๋ธ๋ -> DOM)
- ๋ ๋๋ง ์์ง์ด HTML๊ณผ CSS๋ฅผ ํ์ฑํ์ฌ DOM๊ณผ CSSOM์ ์์ฑํ๋ฏ์ด ์๋ฐ์คํฌ๋ฆฝํธ ์์ง์ ์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ ํด์ํ์ฌ AST(Abstract Syntax Tree:์ถ์์  ๊ตฌ๋ฌธ ํธ๋ฆฌ)๋ฅผ ์์ฑํ๋ค. ๊ทธ๋ฆฌ๊ณ  AST๋ฅผ ๊ธฐ๋ฐ์ผ๋ก ์ธํฐํ๋ฆฌํฐ๊ฐ ์คํํ  ์ ์๋ ์ค๊ฐ ์ฝ๋์ธ ๋ฐ์ดํธ์ฝ๋๋ฅผ ์์ฑํ์ฌ ์คํํ๋ค.

    ![https://blog.kakaocdn.net/dn/TsUmB/btrbOPGdglj/4eOhmMY4jxKzOmDQyf6KNK/img.png](https://blog.kakaocdn.net/dn/TsUmB/btrbOPGdglj/4eOhmMY4jxKzOmDQyf6KNK/img.png)

- ๋ ๋๋ง ์์ง๊ณผ ์๋ฐ์คํฌ๋ฆฝํธ ์์ง์ ์ง๋ ฌ์ ์ผ๋ก ํ์ฑ์ ์ํํ๋ค. ๋ธ๋ผ์ฐ์ ๋ ๋๊ธฐ์ (synchronous)์ผ๋ก, ์ฆ ์์์ ์๋ ๋ฐฉํฅ์ผ๋ก ์์ฐจ์ ์ผ๋ก HTML, CSS, ์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ ํ์ฑํ๊ณ  ์คํํ๋ค. script ํ๊ทธ์ ์์น์ ๋ฐ๋ผ HTML ํ์ฑ์ด ๋ธ๋กํน๋์ด DOM ์์ฑ์ด ์ง์ฐ๋  ์ ์๋ค๋ ๊ฒ์ ์๋ฏธํ๋ค.
- ์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ head๊ฐ ์๋ body ์์์ ๊ฐ์ฅ ์๋ ๋ซ๋ ํ๊ทธ ๋ฐ๋ก ์์ ์์น์ํค๋ฉด ์๋ฐ์คํฌ๋ฆฝํธ๊ฐ ์คํ๋  ์์ ์ ์ด๋ฏธ ๋ ๋๋ง ์์ง์ด HTML ์์๋ฅผ ๋ชจ๋ ํ์ฑํ์ฌ DOM ์์ฑ์ด ์๋ฃ๋์ด ๋ ๋๋ง๋๋ฏ๋ก ํ์ด์ง ๋ก๋ฉ ์๊ฐ์ด ๋จ์ถ๋๊ณ  ์๋ฌ ๋ฐ์ํ  ์ฐ๋ ค๋ ์๋ค.
# ๐ 39์ฅ DOM (~p684)
- DOM(Document Object Model: ๋ฌธ์ ๊ฐ์ฒด ๋ชจ๋ธ)์ HTML ๋ฌธ์์ ๊ณ์ธต์  ๊ตฌ์กฐ์ ์ ๋ณด๋ฅผ ํํํ๋ฉฐ ์ด๋ฅผ ์ ์ดํ  ์ ์๋ API, ์ฆ ํ๋กํผํฐ์ ๋ฉ์๋๋ฅผ ์ ๊ณตํ๋ ํธ๋ฆฌ ์๋ฃ๊ตฌ์กฐ๋ค.

![https://blog.kakaocdn.net/dn/XMBNt/btrbGA5bkQX/ft3j4aXD79oMTTJLYZUl30/img.png](https://blog.kakaocdn.net/dn/XMBNt/btrbGA5bkQX/ft3j4aXD79oMTTJLYZUl30/img.png)

![https://blog.kakaocdn.net/dn/bCIkYT/btrbIcJIdJZ/IKk70KA3T6CVL3l8k5S5kk/img.png](https://blog.kakaocdn.net/dn/bCIkYT/btrbIcJIdJZ/IKk70KA3T6CVL3l8k5S5kk/img.png)

![https://blog.kakaocdn.net/dn/blpDeU/btrbCt6BbcI/W8mUzTj0cVcxP1ZSNBeXoK/img.png](https://blog.kakaocdn.net/dn/blpDeU/btrbCt6BbcI/W8mUzTj0cVcxP1ZSNBeXoK/img.png)

- ๋ชจ๋  ๋ธ๋ ๊ฐ์ฒด๋ Object, EventTarget, Node ์ธํฐํ์ด์ค๋ฅผ ์์๋ฐ๋๋ค. ์ถ๊ฐ์ ์ผ๋ก ๋ฌธ์ ๋ธ๋๋ Document, HTMLDocument ์ธํฐํ์ด์ค๋ฅผ ์์๋ฐ๊ณ  ์ดํธ๋ฆฌ๋ทฐํธ ๋ธ๋๋ Attr, ํ์คํธ ๋ธ๋๋ CharacterData ์ธํฐํ์ด์ค๋ฅผ ๊ฐ๊ฐ ์์๋ฐ๋๋ค. ์์ ๋ธ๋๋ Element ์ธํฐํ์ด์ค๋ฅผ ์์๋ฐ๋๋ค. ๋ํ ์์ ๋ธ๋๋ ์ถ๊ฐ์ ์ผ๋ก HTMLElement์ ํ๊ทธ์ ์ข๋ฅ๋ณ๋ก ์ธ๋ถํ๋ HTMLHtmlElement, HTMLHeadElement, HTMLBodyElement, HTMLUListElement ๋ฑ์ ์ธํฐํ์ด์ค๋ฅผ ์์๋ฐ๋๋ค.
- DOM์ HTML ๋ฌธ์์ ๊ณ์ธต์  ๊ตฌ์กฐ์ ์ ๋ณด๋ฅผ ํํํ๋ ๊ฒ์ ๋ฌผ๋ก  ๋ธ๋ ๊ฐ์ฒด์ ์ข๋ฅ, ์ฆ ๋ธ๋ ํ์์ ๋ฐ๋ผ ํ์ํ ๊ธฐ๋ฅ์ ํ๋กํผํฐ์ ๋ฉ์๋์ ์งํฉ์ธ DOM API(Application Programming Interface)๋ก ์ ๊ณตํ๋ค. ์ด DOM API๋ฅผ ํตํด HTML์ ๊ตฌ์กฐ๋ ๋ด์ฉ ๋๋ ์คํ์ผ ๋ฑ์ ๋์ ์ผ๋ก ์กฐ์ํ  ์ ์๋ค.

> ๐ก ์์ ๋ธ๋ ์ทจ๋

- HTML์ ๊ตฌ์กฐ๋ ๋ด์ฉ ๋๋ ์คํ์ผ ๋ฑ์ ๋์ ์ผ๋ก ์กฐ์ํ๋ ค๋ฉด ๋จผ์  ์์ ๋ธ๋๋ฅผ ์ทจ๋ํด์ผ ํ๋ค. ํ์คํธ ๋ธ๋๋ ์ดํธ๋ฆฌ๋ทฐํธ ๋ธ๋๋ฅผ ์กฐ์ํ๊ณ ์ ํ  ๋๋ ๋ง์ฐฌ๊ฐ์ง๋ค. ์์ ๋ธ๋์ ์ทจ๋์ HTML ์์๋ฅผ ์กฐ์ํ๋ ์์์ ์ด๋ค. DOM์ ์์ ๋ธ๋๋ฅผ ์ทจ๋ํ  ์ ์๋ ๋ค์ํ ๋ฉ์๋๋ฅผ ์ ๊ณตํ๋ค.
1. id๋ฅผ ์ด์ฉํ ์์ ๋ธ๋ ์ทจ๋
    - Document.prototype.getElementById ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ id ์ดํธ๋ฆฌ๋ทฐํธ ๊ฐ(์ดํ id ๊ฐ)์ ๊ฐ๋ ํ๋์ ์์ ๋ธ๋๋ฅผ ํ์ํ์ฌ ๋ฐํํ๋ค. getElementById ๋ฉ์๋๋ Document.prototype์ ํ๋กํผํฐ๋ค. ๋ฐ๋ผ์ ๋ฐ๋์ ๋ฌธ์ ๋ธ๋์ธ document๋ฅผ ํตํด ํธ์ถํด์ผ ํ๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul>
          <li id="apple">Apple</li>
          <li id="banana">Banana</li>
          <li id="banana">Orange</li>
        </ul>
        <script>
          // id๊ฐ์ด banana์ธ ๋ ๋ฒ์งธ li ์์๊ฐ ํ์ฑ๋์ด ์์ฑ๋ ์์ ๋ธ๋ ๋ฐํ
          // ์ธ์๋ก ์ ๋ฌ๋ id ๊ฐ์ ๊ฐ๋ ์ฒซ ๋ฒ์งธ ์์ ๋ธ๋๋ง ๋ฐํ(๋จ ํ๋์ ์์ ๋ธ๋ ๋ฐํ)
          const $elem = document.getElementById('banana');
          // ์ทจ๋ํ ์์ ๋ธ๋์ style.color ํ๋กํผํฐ ๊ฐ ๋ณ๊ฒฝ
          $elem.style.color = 'red';
          
          // id ๊ฐ ์์ผ๋ฉด null ๋ฐํ
          const $elem2 = document.getElementById('grape');
        </script>
      </body>
    </html>
    ```

2. ํ๊ทธ ์ด๋ฆ์ ์ด์ฉํ ์์ ๋ธ๋ ์ทจ๋
    - Document.prototype/Element.prototype.getElementsByTagName ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ ํ๊ทธ ์ด๋ฆ์ ๊ฐ๋ ๋ชจ๋  ์์ ๋ธ๋๋ค์ ํ์ํ์ฌ ๋ฐํํ๋ค. ์ฌ๋ฌ ๊ฐ์ ์์ ๋ธ๋ ๊ฐ์ฒด๋ฅผ ๊ฐ๋ DOM ์ปฌ๋ ์ ๊ฐ์ฒด์ธ HTMLCollection ๊ฐ์ฒด๋ฅผ ๋ฐํํ๋ค. HTML ๋ฌธ์์ ๋ชจ๋  ์์ ๋ธ๋๋ฅผ ์ทจ๋ํ๋ ค๋ฉด ๋ฉ์๋์ ์ธ์๋ก '*'๋ฅผ ์ ๋ฌํ๋ค.
    - Document.prototype์ ์ ์๋ ๋ฉ์๋๋ document๋ฅผ ํตํด ํธ์ถํ๋ฉฐ DOM ์ ์ฒด์์ ์์ ๋ธ๋๋ฅผ ํ์ํ์ฌ ๋ฐํํ๊ณ  Element.prototype์ ์ ์๋ ๋ฉ์๋๋ ํน์  ์์ ๋ธ๋๋ฅผ ํตํด ํธ์ถํ๋ฉฐ, ํน์  ์์ ๋ธ๋์ ์์ ๋ธ๋ ์ค์์ ์์ ๋ธ๋๋ฅผ ํ์ํ์ฌ ๋ฐํํ๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul id="fruits">
          <li>Apple</li>
          <li>Banana</li>
          <li>Orange</li>
        </ul>
        <ul>
          <li>HTML</li>
        </ul>
        <script>
          // Dom ์ ์ฒด์์ ํ๊ทธ ์ด๋ฆ์ด li์ธ ์์ ๋ธ๋๋ฅผ ๋ชจ๋ ํ์ํ์ฌ ๋ฐํ
          const $lisFromDocument = document.getElementsByTagName('li');
          console.log($lisFromDocument); // HTMLCollection(4) [li, li, li, li]
          
          // ul#fruits ์์์ ์์ ๋ธ๋ ์ค์์ ํ๊ทธ ์ด๋ฆ์ด li์ธ ์์ ๋ธ๋๋ฅผ ๋ชจ๋ ํ์ํ์ฌ ๋ฐํ
          const $fruits = document.getElementById('fruits');
          const $lisFromFruits = $fruits.getElementsByTagName('li');
          console.log($lisFromFruits); // HTMLCollection(3) [li, li, li]
        </script>
      </body>
    </html>
    ```

3. class๋ฅผ ์ด์ฉํ ์์ ๋ธ๋ ์ทจ๋
    - Document.prototype/Element.prototype.getElementsByClassName ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ class ์ดํธ๋ฆฌ๋ทฐํธ ๊ฐ์ ๊ฐ๋ ๋ชจ๋  ์์ ๋ธ๋๋ค์ ํ์ํ์ฌ ๋ฐํํ๋ค. getElementsByTagName ๋ฉ์๋์ ๋ง์ฐฌ๊ฐ์ง๋ก ์ฌ๋ฌ ๊ฐ์ ์์ ๋ธ๋ ๊ฐ์ฒด๋ฅผ ๊ฐ๋ DOM ์ปฌ๋ ์ ๊ฐ์ฒด์ธ HTMLCollection ๊ฐ์ฒด๋ฅผ ๋ฐํํ๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul id="fruits">
          <li class="apple">Apple</li>
          <li class="banana">Banana</li>
          <li class="orange">Orange</li>
        </ul>
        <div class="banana">Banana</div>
        <script>
          // Dom ์ ์ฒด์์ class ๊ฐ์ด 'banana'์ธ ์์ ๋ธ๋๋ฅผ ๋ชจ๋ ํ์ํ์ฌ ๋ฐํ
          const $bananasFromDocu = document.getElementsByClassName('banana');
          console.log($bananasFromDocu);
          // HTMLCollection(2) [li.banana, div.banana]
          
          // #fruits ์์์ ์์ ๋ธ๋ ์ค class ๊ฐ์ด 'banana'์ธ ์์ ๋ธ๋ ๋ชจ๋ ํ์ํด ๋ฐํ
          const $fruits = document.getElementById('fruits');
          const $bananasFromFruit = $fruits.getElementsByClassName('banana');
          console.log($bananasFromFruit); // HTMLCollection [li.banana]
        </script>
      </body>
    </html>
    ```

4.  CSS ์ ํ์๋ฅผ ์ด์ฉํ ์์ ๋ธ๋ ์ทจ๋
    - Document.prototype/Element.prototype.querySelector ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ CSS ์ ํ์๋ฅผ ๋ง์กฑ์ํค๋ ํ๋์ ์์ ๋ธ๋๋ฅผ ํ์ํ์ฌ ๋ฐํํ๋ค. (์์ ๋ธ๋๊ฐ ์ฌ๋ฌ ๊ฐ์ธ ๊ฒฝ์ฐ ์ฒซ ๋ฒ์งธ ์์ ๋ธ๋๋ง ๋ฐํ, ์กด์ฌํ์ง ์๋ ๊ฒฝ์ฐ null ๋ฐํ, ๋ฌธ๋ฒ์ ๋ง์ง ์๋ ๊ฒฝ์ฐ DOMException ์๋ฌ ๋ฐ์)
    - Document.prototype/Element.prototype.querySelectorAll ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ CSS ์ ํ์๋ฅผ ๋ง์กฑ์ํค๋ ๋ชจ๋  ์์ ๋ธ๋๋ฅผ ํ์ํ์ฌ DOM ์ปฌ๋ ์ ๊ฐ์ฒด์ธ NodeList ๊ฐ์ฒด๋ฅผ ๋ฐํํ๋ค. HTML ๋ฌธ์์ ๋ชจ๋  ์์ ๋ธ๋๋ฅผ ์ทจ๋ํ๋ ค๋ฉด querySelectorAll ๋ฉ์๋์ ์ธ์๋ก ์ ์ฒด ์ ํ์ '*'๋ฅผ ์ ๋ฌํ๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul>
          <li class="apple">Apple</li>
          <li class="banana">Banana</li>
          <li class="orange">Orange</li>
        </ul>
        <script>
          // ul ์์์ ์์ ์์์ธ li ์์๋ฅผ ๋ชจ๋ ํ์ํ์ฌ ๋ฐํ
          const $elems = document.querySelectorAll('ul > li');
          console.log($elems);
          // NodeList(3) [li.apple, li.banana, li.orange]
        </script>
      </body>
    </html>
    ```

5.  ํน์  ์์ ๋ธ๋๋ฅผ ์ทจ๋ํ  ์ ์๋์ง ํ์ธ
    - Element.prototype.matches ๋ฉ์๋๋ ์ธ์๋ก ์ ๋ฌํ CSS ์ ํ์๋ฅผ ํตํด ํน์  ์์ ๋ธ๋๋ฅผ ์ทจ๋ํ  ์ ์๋ ์ง ํ์ธํ๋ค. (์ด๋ฒคํธ ์์ ์ฌ์ฉ ์ ์ ์ฉ)

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul id="fruits">
          <li class="apple">Apple</li>
          <li class="banana">Banana</li>
          <li class="orange">Orange</li>
        </ul>
        <script>
          const $apple = document.querySelector('.apple');
          console.log($apple.matches('#fruits > li.apple')); // true
          console.log($apple.matches('#fruits > li.banana')); // false ์ทจ๋ X
        </script>
      </body>
    </html>
    ```
### ๐ 2021๋ 8์ 12์ผ ๋ชฉ์์ผ
# ๐ 39์ฅ DOM (p685~713)
- DOM ์ปฌ๋ ์ ๊ฐ์ฒด์ธ HTMLCollection๊ณผ NodeList๋ DOM API๊ฐ ์ฌ๋ฌ ๊ฐ์ ๊ฒฐ๊ณผ๊ฐ์ ๋ฐํํ๊ธฐ ์ํ DOM ์ปฌ๋ ์ ๊ฐ์ฒด๋ค. ์คํ๋ ๋ ๋ฌธ๋ฒ์ ์ฌ์ฉํ์ฌ ๊ฐ๋จํ ๋ฐฐ์ด๋ก ๋ณํํ  ์ ์๊ณ  ๋ธ๋ ๊ฐ์ฒด์ ์ํ ๋ณ๊ฒฝ๊ณผ ์๊ด์์ด ์์ ํ๊ฒ DOM ์ปฌ๋ ์์ ์ฌ์ฉํ๋ ค๋ฉด ๋ฐฐ์ด๋ก ๋ณํํ์ฌ ์ฌ์ฉํ๋ ๊ฒ์ ๊ถ์ฅํ๋ค.

> ๐ก ๋ธ๋ ์ ๋ณด ์ทจ๋

- Node.prototype.nodeType: ๋ธ๋ ํ์์ ๋ํ๋ด๋ ์์๋ก ๋ฐํ. 1: ์์ ๋ธ๋ ํ์, 3: ํ์คํธ ๋ธ๋ ํ์, 9: ๋ฌธ์ ๋ธ๋ ํ์
- Node.prototype.nodeName: ๋ธ๋์ ์ด๋ฆ์ ๋ฌธ์์ด๋ก ๋ฐํ. ์์ ๋ธ๋, ํ์คํธ ๋ธ๋, ๋ฌธ์ ๋ธ๋

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <div id="foo">Hello</div>
      </body>
      <script>
        // ๋ฌธ์ ๋ธ๋์ ๋ธ๋ ์ ๋ณด๋ฅผ ์ทจ๋ํ๋ค.
        console.log(document.nodeType); // 9
        console.log(document.nodeName); // #document
        
        // ์์ ๋ธ๋์ ๋ธ๋ ์ ๋ณด๋ฅผ ์ทจ๋ํ๋ค.
        const $foo = document.getElementById('foo');
        console.log($foo.nodeType); // 1
        console.log($foo.nodeName); // DIV
        
        // ํ์คํธ ๋ธ๋์ ๋ธ๋ ์ ๋ณด๋ฅผ ์ทจ๋ํ๋ค.
        const $testNode = $foo.firstChild;
        console.log($testNode.nodeType); // 3
        console.log($testNode.nodeName); // #text
      </script>
    </html>
    ```


> ๐ก DOM ์กฐ์

- Element.prototype.innerHTML ํ๋กํผํฐ๋ ์์ ๋ธ๋์ ์ฝํ์ธ  ์์ญ ๋ด์ ํฌํจ๋ ๋ชจ๋  HTML ๋งํฌ์์ ๋ฌธ์์ด๋ก ๋ฐํํ๋ค.
- innerHTML ํ๋กํผํฐ๋ฅผ ์ฌ์ฉํ DOM ์กฐ์์ ๊ตฌํ์ด ๊ฐ๋จํ๊ณ  ์ง๊ด์ ์ด๋ผ๋ ์ฅ์ ์ด ์์ง๋ง ํฌ๋ก์ค ์ฌ์ดํธ ์คํฌ๋ฆฝํ ๊ณต๊ฒฉ(XSS)์ ์ทจ์ฝํ ๋จ์ ๋ ์๋ค. ๊ทธ๋ฆฌ๊ณ  ๊ธฐ์กด์ ์์ ๋ธ๋๊น์ง ๋ชจ๋ ์ ๊ฑฐํ๊ณ  ๋ค์ ์ฒ์๋ถํฐ ์๋กญ๊ฒ ์์ ๋ธ๋๋ฅผ ์์ฑํ์ฌ DOM์ ๋ฐ์ํ๋ฏ๋ก ํจ์จ์ ์ด์ง ์๊ณ  ์๋ก์ด ์์๋ฅผ ์ฝ์ํ  ๋ ์ฝ์๋  ์์น๋ฅผ ์ง์ ํ  ์ ์๋ค๋ ๋จ์ ๋ ์๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul id="fruits">
          <li class="apple">Apple</li>
        </ul>
      </body>
      <script>
        const $fruits = document.getElementById('fruits');
        
        // ๋ธ๋ ์ถ๊ฐ
        $fruits.innerHTML += '<li class="banana">Banana</li>';
        
        // ๋ธ๋ ๊ต์ฒด
        $fruits.innerHTML = '<li class="orange">Orange</li>';
        
        // ๋ธ๋ ์ญ์ 
        $fruits.innerHTML = '';
      </script>
    </html>
    ```

- Element.prototype.insertAdjacentHTML(position, DOMString) ๋ฉ์๋๋ ๊ธฐ์กด ์์๋ฅผ ์ ๊ฑฐํ์ง ์์ผ๋ฉด์ ์์น๋ฅผ ์ง์ ํด ์๋ก์ด ์์๋ฅผ ์ฝ์ํ๋ค. ๊ธฐ์กด ์์์๋ ์ํฅ์ ์ฃผ์ง ์๊ณ  ์๋กญ๊ฒ ์ฝ์๋  ์์๋ง์ ํ์ฑํ์ฌ ์์ ์์๋ก ์ถ๊ฐํ๋ฏ๋ก innerHTML ํ๋กํผํฐ๋ณด๋ค ํจ์จ์ ์ด๊ณ  ๋น ๋ฅด์ง๋ง ๋ง์ฐฌ๊ฐ์ง๋ก HTML ๋งํฌ์ ๋ฌธ์์ด์ ํ์ฑํ๋ฏ๋ก ํฌ๋ก์ค ์ฌ์ดํธ ์คํฌ๋ฆฝํ ๊ณต๊ฒฉ์ ์ทจ์ฝํ๋ค๋ ์ ์ ๋์ผํ๋ค.
- innerHTML ํ๋กํผํฐ์ insertAdjacentHTML ๋ฉ์๋๋ HTML ๋งํฌ์ ๋ฌธ์์ด์ ํ์ฑํ์ฌ ๋ธ๋๋ฅผ ์์ฑํ๊ณ  DOM์ ๋ฐ์ํ๋ค. DOM์ ๋ธ๋๋ฅผ ์ง์  ์์ฑ/์ฝ์/์ญ์ /์นํํ๋ ๋ฉ์๋๋ ์ ๊ณตํ๋ค.

    ```html
    <!DOCTYPE html>
    <html>
      <body>
        <ul id="fruits">
          <li>Apple</li>
        </ul>
      </body>
      <script>
      const $fruits = document.getElementById('fruits');
      
      // 1. ์์ ๋ธ๋ ์์ฑ
      const $li = document.createElement('li');
      
      // 2. ํ์คํธ ๋ธ๋ ์์ฑ
      const $textNode = document.createTextNode('Banana');
      
      // 3. ํ์คํธ ๋ธ๋๋ฅผ $li ์์ ๋ธ๋์ ์์ ๋ธ๋๋ก ์ถ๊ฐ
      $li.appendChild(textNode);
      
      // 4. $li ์์ ๋ธ๋๋ฅผ #fruits ์์ ๋ธ๋์ ๋ง์ง๋ง ์์ ๋ธ๋๋ก ์ถ๊ฐ
      $fruits.appendChild($li);
      </script>
    </html>
    ```

    - Document.prototype.createElement(tagName) ๋ฉ์๋๋ ์์ ๋ธ๋๋ฅผ ์์ฑํ์ฌ ๋ฐํํ๋ค. ์์ ๋ธ๋๋ฅผ ์์ฑํ  ๋ฟ DOM์ ์ถ๊ฐ๋์ง ์๊ณ  ํ๋ก ์กด์ฌํ๊ณ  ์์ ๋ธ๋์ธ ํ์คํธ ๋ธ๋๋ ์๋ ์ํ๋ค.
    - Document.prototype.createTextNode(text) ๋ฉ์๋๋ ํ์คํธ ๋ธ๋๋ฅผ ์์ฑํ์ฌ ๋ฐํํ๋ค. ๋งค๊ฐ๋ณ์ text์๋ ํ์คํธ ๋ธ๋์ ๊ฐ์ผ๋ก ์ฌ์ฉํ  ๋ฌธ์์ด์ ์ธ์๋ก ์ ๋ฌํ๋ค. createElement ๋ฉ์๋์ ๋ง์ฐฌ๊ฐ์ง๋ก ํ์คํธ ๋ธ๋๋ฅผ ์์ฑํ  ๋ฟ ์์ ๋ธ๋์ ์ถ๊ฐํ์ง ์๋๋ค.
    - Node.prototype.appendChild(childNode) ๋ฉ์๋๋ ๋งค๊ฐ๋ณ์ childNode์๊ฒ ์ธ์๋ก ์ ๋ฌํ ๋ธ๋๋ฅผ ๋ฉ์๋๋ฅผ ํธ์ถํ ๋ธ๋์ ๋ง์ง๋ง ์์ ๋ธ๋๋ก ์ถ๊ฐํ๋ค. appendChild ๋ฉ์๋๋ฅผ ํตํด ์์ ๋ธ๋์ ํ์คํธ ๋ธ๋๋ ๋ถ์ ๊ด๊ณ๋ก ์ฐ๊ฒฐ๋์์ง๋ง ์์ง ๊ธฐ์กด DOM์ ์ถ๊ฐ๋์ง ์์ ์ํ๋ค.

        ```jsx
        // ํ์คํธ ๋ธ๋๋ฅผ ์์ฑํ์ฌ ์์ ๋ธ๋์ ์์ ๋ธ๋๋ก ์ถ๊ฐ
        $li.appendChild(document.createTextNode('Banana'));

        // $li ์์ ๋ธ๋์ ์์ ๋ธ๋๊ฐ ํ๋๋ ์๋ ์ ์ฝ๋์ ๋์ผํ๊ฒ ๋์ํ๋ค.
        $li.textContent = 'Banana';
        ```

    - ์์ ๋ธ๋๋ฅผ DOM์ ์ถ๊ฐํ  ๋๋ appendChild ๋ฉ์๋๋ฅผ ์ฌ์ฉํ์ฌ ํ์คํธ ๋ธ๋์ ๋ถ์ ๊ด๊ณ๋ก ์ฐ๊ฒฐํ ์์ ๋ธ๋๋ฅผ $fruits ์์ ๋ธ๋์ ๋ง์ง๋ง ์์ ์์๋ก ์ถ๊ฐํ๋ค. ๋น๋ก์ ์๋กญ๊ฒ ์์ฑํ ์์ ๋ธ๋๊ฐ DOM์ ์ถ๊ฐ๋๋ค. ๋จ ํ๋์ ์์ ๋ธ๋๋ฅผ ์์ฑํ์ฌ DOM์ ํ๋ฒ ์ถ๊ฐํ๋ฏ๋ก DOM์ ํ ๋ฒ ๋ณ๊ฒฝ๋๋ค. ์ด๋ ๋ฆฌํ๋ก์ฐ์ ๋ฆฌํ์ธํธ๊ฐ ์คํ๋๋ค.
