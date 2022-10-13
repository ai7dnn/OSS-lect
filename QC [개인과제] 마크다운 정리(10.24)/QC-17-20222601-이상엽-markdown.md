# 1. 마크다운의 장/단점

## 1)장점  
-문법이 쉽고 간결하다.  
-관리가 쉽다.  
-별도의 도구없이 작성 가능하다.  
-다양한 형태로 변환이 가능하다.  
-지원 가능한 플랫폼과 프로그램이 다양하다.  
-텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.  

## 2)단점
-표준이 없다.  
-표준이 없기 때문에 표현하는 도구에 따라서 동작하지 않거나, 다르게 표현될 수 있다.  
-모든 HTML 마크업을 대신하지 못하지 못하는 한계점. 

<br/>
<br/>

# 2. 마크다운 문법(syntax)<br/>
## 1)제목 (Header)<br/>
-# 뒤에 띄어쓰기를 넣어주는게 권장하는 방법이다.<br/>
-h1 ~ h6까지 표현 가능하다.<br/>
  
    # 제목1
    ## 제목2 
    ### 제목3
    #### 제목4
    ##### 제목5
    ###### 제목6
  
위와 같이 작성을 하게 되면 아래와 같이 제목이 표시된다.

# 제목1
## 제목2 
### 제목3
#### 제목4
##### 제목5
###### 제목6

## 2) 줄바꿈(Line Breaks)
  
띄어쓰기 2번 or <>안 br/ 로 표현 가능하다.
  
<img width="50" alt="스크린샷 2022-10-11 오후 4 38 00" src="https://user-images.githubusercontent.com/109512986/195025419-63bef538-c169-4820-bfef-e3639d0b2b57.png">


## 3) 수평선(Horizontal Rule)
  
    ---
    ***
  
    ------
    ******
  
위와 같이 작성을 하게 되면 얇은 수평선이 나타난다.

  
    <hr/>
  
위와 같이 작성을 하게 되면 굵은 수평선이 나타난다.
  

## 4) 글자 강조(Emphasis)
  
    **굵은 글씨**
    *이텔릭*
    _이탤릭_
    ~~취소선~~
    <u>밑줄</u>
  
위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
**굵은 글씨**
  
*이텔릭*
  
_이탤릭_
  
~~취소선~~
  
<u>밑줄</u>

## 5) 인용문(BlockQuote)
  
">" 블럭 인용 문자를 사용하면 인용문 표현이 가능하다.(띄어쓰기 해줄 것)
  
    > 인용문장
    >> 중첩된 인용문
    >>> 중첩된 인용문2

위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
> 인용문장
>> 중첩된 인용문
>>> 중첩된 인용문2

## 6)목록(list)
  
1)-,*,+를 이용하여 list 표현(띄어쓰기 해줄 것)
  
    - 순서가 필요하지 않은 목록
    * 순서가 필요하지 않은 목록
    + 순서가 필요하지 않은 목록
  
위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
- 순서가 필요하지 않은 목록
* 순서가 필요하지 않은 목록
+ 순서가 필요하지 않은 목록

  
2)숫자를 이용하여 list 표현(띄어쓰기 해줄 것)
  
    1. 순서가 필요한 목록
    2. 순서가 필요한 목록
    3. 순서가 필요한 목록
  
위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
(순서가 바뀌어도 오름차순으로 정렬된다.)
  
1. 순서가 필요한 목록
2. 순서가 필요한 목록
3. 순서가 필요한 목록
  
## 7)링크(Links)

1)기본방법
  
    [Title](link)
  
위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
Click [here](http://naver.com)
  
[네이버](http://naver.com)
  
2)참조 링크 사용 방법
  
    [link keyword][id]
    [id]:URL"Optional Title"
  
위와 같이 작성을 하게 되면 아래와 같이 나타난다.
  
[네이버][nv]
  
[nv]: http://www.naver.com
  
## 8)이미지(Images)
  
link와 문법이 유사하다. 앞에!만 추가하면 된다.
  
1)기본 문법
  
    ![대체텍스트](이미지주소)
  
<img width="981" alt="스크린샷 2022-10-11 오후 5 31 22" src="https://user-images.githubusercontent.com/109512986/195039815-cdab9e9c-da81-4b55-9c92-f4f29db73151.png">
  
위와 같이 작성을 하게 되면 아래와 같이 이미지를 나타낼 수 있다.
  

![image Description](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMjAyMDdfMTE1%2FMDAxNjQ0MjA2ODE0ODQx.KwvabxkNAmFXYtAKBqrEL_9DPG6UuR_NECK8PlvsGksg.l5xRZXfD6g8Y_hOw3kS1STlmcVLBCXTgr4DWVdJ8w1og.JPEG.gaoni0317%2FIMG%25A3%25DF20211215%25A3%25DF221352%25A3%25DF218.jpg&type=sc960_832)
  
2)참조 링크 사용 방법
  
    ![대체텍스트][id]
    [id]:이미지주소"Optional Title"
  
<img width="899" alt="스크린샷 2022-10-11 오후 5 37 29" src="https://user-images.githubusercontent.com/109512986/195041420-92dd0ef8-29ee-4a7b-9fcc-c31e7a24b76e.png">
  
위와 같이 작성을 하게 되면 아래와 같이 이미지를 나타낼 수 있다.
  
![image Description][dog]
  
[dog]:https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMjAyMDdfMTE1%2FMDAxNjQ0MjA2ODE0ODQx.KwvabxkNAmFXYtAKBqrEL_9DPG6UuR_NECK8PlvsGksg.l5xRZXfD6g8Y_hOw3kS1STlmcVLBCXTgr4DWVdJ8w1og.JPEG.gaoni0317%2FIMG%25A3%25DF20211215%25A3%25DF221352%25A3%25DF218.jpg&type=sc960_832
  
3)이미지 노출과 동시에 링크 처리
  
    [![대체텍스트](이미지주소)](링크주소)
  
<img width="899" alt="스크린샷 2022-10-11 오후 5 37 29" src="https://user-images.githubusercontent.com/109512986/195042922-96f07f14-8918-4e15-9756-070d88e621f4.png">
  
위와 같이 작성을 하면 링크가 첨부된 이미를 나타낼 수 있다.
  
[![image description](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMjAyMDdfMTE1%2FMDAxNjQ0MjA2ODE0ODQx.KwvabxkNAmFXYtAKBqrEL_9DPG6UuR_NECK8PlvsGksg.l5xRZXfD6g8Y_hOw3kS1STlmcVLBCXTgr4DWVdJ8w1og.JPEG.gaoni0317%2FIMG%25A3%25DF20211215%25A3%25DF221352%25A3%25DF218.jpg&type=sc960_832)](https://m.search.naver.com/search.naver?where=m_image&mode=column&sm=mtb_img&query=멍멍이&nso=so%3Ar%2Ca%3Aall%2Cp%3Aall#imgId=r6_image_sas%3Ablog132440130%7C1%7C222641038867_1677768662)
  
## 9)표(Table)
  
-vertical bar 기호를 통해 테이블을 표현 가능.(가장 좌측, 우측 생략 가능)
  
-헤더와 셀을 구분할 때 3개 이상의 -(하이픈,대시)가 필요하다.
  
-:(콜론)기호를 통해 정렬할 수 있다.

    | header | value | description |
    | --: | :-- | :--: |
    | 정렬 | --: | 우측정렬 |
    | 정렬 | :-- | 좌측정렬 |
    | 정렬 | :--: | 가운데정렬 |
  
위와 같이 작성하게 되면 아래와 같이 table이 나타난다.
  
두번째 행과 같이 정렬 조건을 기입해주면 열 전체에 정렬 조건이 적용된다.  

| header | value | description |
| --: | :-- | :--: |
| 정렬 | --: | 우측정렬 |
| 정렬 | :-- | 좌측정렬 |
| 정렬 | :--: | 가운데정렬 |
  
## 10)코드
  
1)인라인 코드(Inline Code)
  
-백틱(':숫자 1번 키 왼쪽에 위치)으로 강조할 내용을 감싸면 된다.
  
    '해당 코드'는 강조할 부분이다.
  
위와 같이 코드를 적용 시켜주면 강조가 된다.

'해당 코드'는 강조할 부분이다

2)블럭 코드(Block Code)
  
-'''html, css,javascript,bash,plaintext 등등
  
-코드의 종류를 명시하지 않은 경우
  
    '''
    코드
    '''
  
-html
  
    ''' html
    코드
    '''
  
-CSS
  
    ''' css
    코드
    '''

-javascript
  
    ''' javascript
    코드
    '''
  
-bash
  
    ''' bash
    코드
    '''
  
-이외 텍스트
  
    ''' plaintext
    코드 이외 텍스트
    '''
    
