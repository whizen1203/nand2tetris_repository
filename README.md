# nand2tetris_repository 크기1
## nand2tetris_repository 크기2
### nand2tetris_repository 크기3
#### nand2tetris_repository 크기4
##### nand2tetris_repository 크기5
###### nand2tetris_repository 크기6

밑줄 =5개
======
밑줄2 -5개
-----

이텔릭체는 *별표(Asterisk)* 혹은 _언더바(Under Bar)_ 로 표기합니다. 
_언더바는 붙어있으면 적용안됨_가나다라마바사
**볼드체는 별표2개**
***별표3개는 별표1개 + 별표2개***, **_별표2개 + 언더바_**, _**언더바 + 별표2개**_
_**언더바에 무언가 붙어있으면 기울임꼴 적용안됨**_ㅇㅁㅇㄴㄹ
~~취소선은 물결표시 2개 붙이기~~
<u>밑줄은 이렇게?</u> <u>밑줄</u> 안되는데...?

<ol>
1. 순서가 필요한 항목
<ul>-순서가 필요하지 않은 항목?(서브)</ul>
  
  <ul>- 대쉬로 표기</ul>
  <ul>* 별표로 표기</ul>
  <ul>+ 더하기로 표기</ul>

  2. 이건가
  <ul>-순서가 필요하지 않은 항목</ul>
  <ul>-순서가 필요하지 않은 항목 ol 안쪽 ul 바깥쪽2</ul>
  3. 이걸로 되는건가
  <ul>ol안쪽에 작은 분류로 한줄마다 ul 입력인가</ul>
</ol>
<ul>이건 ul</ul>
<ol>이건 ol</ol>


###링크(Links)
=====
[Google] (https://google.com)
[Naver] (https://naver.com "링크설명을 작성하세요")
[상대적 참조] (../users/login)
[Dribbble] [Dribbble link]
[GitHub] [1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"

###이하 이미지관련
=====

![대체 텍스트(alternative text)를 입력하세요!](http://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요.")

![Kayak][logo]

[logo]: http://www.gstatic.com/webp/gallery/2.jpg "To go kayaking."

###이건 이미지에 링크
-----
[![Vue](/images/vue.png)](https://kr.vuejs.org/)


###인라인 코드 강조
=====
`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

###블록 코드 강조
======
```를 세번 입력하고 코드 종류도 적기

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```
######HTML
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>

######css
.list > li {
  position: absolute;
  top: 40px;
}

######javascript
function func() {
  var a = 'AAA';
  return a;
}

######Bash
$ vim ./~zshrc

######Python
s = "Python syntax highlighting"
print s

######YAML
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.


###표
======
삼각괄호 안의 table로 변환, 
헤더 쉘 구분시 -(하이푼 3개 필요), 
헤더 쉘 구분하면서 : (Colons) 기호로 표의 셀 안의 내용 정렬가능, 
가장 좌측과 우측의 | (Vertical Bar)는 생략가능
<table> 
  | 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
</table>

###인용문
=====
삼각괄호 안의 blockquote로 변환
<blockquote>
인용문(blockQuote) >를 이용하여 적용. >>가 늘어날수록 중첩됨.

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3
</blockquote>

###원시 HTML도 적용가능
=====
<u>마크다운에서 지원하지 않는 기능</u>을 사용할 때 유용하며 대부분 잘 동작함.

<img width="150" src="http://www.gstatic.com/webp/gallery/4.jpg" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">

![Prunus](http://www.gstatic.com/webp/gallery/4.jpg)

###수평선(Horizontal Rule)
=====

-(Hyphen), *(asterisk), _(underbar)를 3개씩 사용하여 적용가능

--- 하이푼
*** 별표
___ 언더바

### 줄바꿈(Line Breaks)
=====

일반 줄비꿈이 동작하지 않는 환경(설정 및 버전에 따라)의 경우, ‘2번의 띄어쓰기’나 삼각괄호 안에 br을 넣어 활용할 수 있다.

동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세   <!--띄어쓰기 2번-->
무궁화 삼천리 화려 강산<br>
대한 사람 대한으로 길이 보전하세
