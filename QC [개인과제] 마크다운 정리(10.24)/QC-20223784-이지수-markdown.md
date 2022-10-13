## 1. markdown이란?



마크업 언어로 2004년 존그루버 의해 만들어졌으며 **HTML**로 변환이 가능하다. 특수기호와 문자를 이용한 구조의 문법을 사용하여 웹에서 보다 빠른 컨텐츠를 작성할 수 있고
가독성이 높아 사용이 유용하며 마크다운을 통해 설치방법, 소스코드 설명, 이슈등을 간단하게 기록할 수 있다. 이 마크다운은 현재 우리가 쓰고 있는 깃허브에서 많이 사용되고 있다.
###### HTML: 웹사이트의 모습을 기술하기 위한 마크업 언어(문서 구조나 서식)


## 2. markdown 사용법

들어가기에 앞서 마크다운은 **띄어쓰기,  유무**에 따라 실행이 안될 수 있으니 그 점을 유의하자.

### <h2> 2-1 제목 (Headers) </h2>

* 글머리 설정
총 6개의 단계로 사용이 가능하다.
```
# hi Git Hub
## hi Git HUb
### hi Git Hub
#### hi Git Hub
##### hi Git Hub
###### hi Git Hub
```

<출력결과>

# hi Git Hub
## hi Git HUb
### hi Git Hub
#### hi Git Hub
##### hi Git Hub
###### hi Git Hub

* 큰 제목

`#` 말고도 다른 방법으로 표현이 가능하다.

```
hi git hub
==========
```

* 부 제목

```
hi Git hub
----------
```
<출력>

hi git hub
==========

hi Git hub
----------




### <h2> 2-2 목록 </h2>

* 글머리 기호(순서가 필요 없는 목록)

글머리 기호는 각각 `*,+,-`를 이용하여 사용 가능하다.

```
* 강아지
  + 고양이
   - 너구리
```

<출력결과>
* 강아지
  + 고양이
    - 너구리

 `*` **앞에 띄어쓰기를 하지 않으면 적용이 안됨. (다른 것들도 마찬가지)**

* 순서있는 목록

```
1. 첫번째
3. 세번째
5. 다섯번째
4. 네번째
2. 두번째
```

<출력결과>

1. 첫번째
3. 세번째
5. 다섯번째
4. 네번째
2. 두번째

###### 어떤 번호를 입력하던지 숫자의 순서는 내림차순으로 정의된다.

### <h2> 2-3 블럭인용문자 </h2>

`>`를 이용하여 블럭이용 문자를 사용 할 수 있다.

```
> 안녕하세요
> > 안녕하세요
> > > 안녕하세요
```
< 출력결과>
> 안녕하세요
> > 안녕하세요
> > > 안녕하세요

### <h2> 2-4 수평선(horizon) </h2>

수평선은 주로 페이지 나누기 용도로 사용한다.

```

* * *

***

*****

- - -

---------------------------------------
```

<출력결과>

* * *

***

*****

- - -

---------------------------------------


   
 ### <h2> 2-5 텍스트 강조 </h2>

`*,~,_,<u>`을 이용하여 텍스트 강조를 할 수 있다


```
**hi git hub**
__hi git hub__
~~hi git hub~~
*hi git hub*
_hi git hub_
<u>hi git hub</u>
```

<출력 결과>

**hi git hub**

__hi git hub__

~~hi git hub~~

*hi git hub*

_hi git hub_


 ### <h2> 2-6 링크 </h2>
 
 * 외부링크
 
 ```
 <양식>
 
[Title](link,"Optional Title")

<적용 시>

 [Git Hub](https://github.com, "Git hub")
 ```
 
 <출력 결과>
 
  [Git Hub](https://github.com, "Git Hub")
  
  
 * 참조링크

```
<양식>

[link keyword][id]

[id]: URL,"Optional Title here"

<적용시>

Link: [Google][googlelink]

[googlelink]: https://google.com "google"
```
<출력 결과>

Link: [Google][googlelink]

[googlelink]: https://google.com "google"


* 일반적인 링크 형성

```
<양식>

<URL>

<적용시>

* 이지수의 깃허브: <https://github.com/easywater030/myrepo>
```
<출력 결과>

* 이지수의 깃허브: <https://github.com/easywater030/myrepo>


### <h2> 2-7 이미지 </h2>
```
<양식>

![Alt text](이미지 주소 복사)

<적용 시>

![Alt text](https://cafeptthumb-phinf.pstatic.net/MjAyMTA5MjZfMjUg/MDAxNjMyNjQ2MDMwNzMz.h3RaUSoEpm1vHsxNXQAajK-Se_l27hQH2CG7tAHSd-kg.3C-H98qH2UT_sva6Hm6DhKLxke2fb5SHQe2i7Js6-tcg.JPEG/externalFile.jpg?type=w800)
```

<출력 결과>

![Alt text](https://cafeptthumb-phinf.pstatic.net/MjAyMTA5MjZfMjUg/MDAxNjMyNjQ2MDMwNzMz.h3RaUSoEpm1vHsxNXQAajK-Se_l27hQH2CG7tAHSd-kg.3C-H98qH2UT_sva6Hm6DhKLxke2fb5SHQe2i7Js6-tcg.JPEG/externalFile.jpg?type=w800)


## 3. 마크다운 사용처

* 위지윅(WSYWIG) 에디터
```
우리가 흔하게 접하는 웹에서 사용되는 에디터(네이버, 다음, 구글 등)이 대부분 위지윅 에디터에 속한다.
```
* 깃헙Github, 비트버킷Bitbucket과 요비Yobi 

```
이 플랫폼은 마크다운을 변환하는 기능을 기본탑재하고 있기 때문에 
마크다운 문법으로 작성한 텍스트를 그대로 복사해서 붙여넣거나 업로드하는 것만으로 마크다운의 적용이 가능하다.
```
* MS워드

```
View 영역의 항목을 그대로 붙여넣거나 HTML 내보내기 등으로 생성한 파일을 불러오는 형태로 사용가능 하다
```









- - -


# <참고 문헌>

* <https://gist.github.com/ihoneymon/652be052a0727ad59601>
* <https://inpa.tistory.com/entry/MarkDown-%F0%9F%93%9A-%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4-%EB%AC%B8%EB%B2%95-%F0%9F%92%AF-%EC%A0%95%EB%A6%AC#Links_(Anchor)_%EB%A7%81%ED%81%AC
* https://www.markdownguide.org/
* https://daringfireball.net/projects/markdown/basics
