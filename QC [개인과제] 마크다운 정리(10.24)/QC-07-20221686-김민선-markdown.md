# 1. 마크다운이란?
## 1-1. 마크다운이란?
일반 텍스트 문서에 서식 요소를 추가하는 데 사용할 수 있는 plain-text 포맷을 기반으로 한 경량형 마크업 언어.
## 1-2. 장점
- .md 확장자 파일로 텍스트 에디터에서도 키보드 하나로 쉽게 포맷하면서 빠르게 문서를 작성할 수 있고, 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다.
- 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다.
- 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다.



# 2. 마크다운 태그
## 2-1. 표제 (Header)
### 표제
"H1"부터 "H6"까지 표현 가능하다.
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

### 대체 구문
텍스트 아래의 행에 임의의 수를 추가한다.
```
This is an H1
=============
This is an H2
-------------
```
This is an H1
=============
This is an H2
-------------

## 2-2. 강조
글자를 강조할 수 있다.

```
굵은 글씨 **bold text**  -> 단어 중간에도 사용 가능
굵은 글씨 __bold text__  -> 단어 중간에 사용 불가능
이탤릭체 *italicized text*  -> 단어 중간에도 사용 가능
이탤릭체 _italicized text_  -> 단어 중간에 사용 불가능
취소선 ~~The world is flat.~~
하이라이트 ==very important words==.
```
- **bold text**
- __bold text__
- *italicized text*
- _italicized text_
- ~~The world is flat.~~
- ==very important words==

## 2-3. 인용 상자(Blockquotes)
블럭 인용 문자를 이용한다.
```
> This is a first blockqute.
>> This is a second blockqute.
>>> This is a third blockqute.
```
> This is a first blockqute.
>> This is a second blockqute.
>>> This is a third blockqute.

## 2-4. 목록(List)
목록을 나타낼 수 있다.
```
순서 리스트
1. First item
2. Second item
3. Third item

순서가 필요하지 않은 리스트
- First item
- Second item
- Third item

* First item
* Second item
* Third item

+ First item
+ Second item
+ Third item

task list
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
순서 리스트
1. First item
2. Second item
3. Third item

순서가 필요하지 않은 리스트
- First item
- Second item
- Third item

* First item
* Second item
* Third item

+ First item
+ Second item
+ Third item

task list
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## 2-5. 링크(Links)
링크를 삽입할 수 있다.
```
제목 추가 [title](https://www.example.com)
URL 및 이메일주소 <https://www.example.com>, <example@example.com>

```
제목 추가 [title](https://www.example.com)
URL 및 이메일주소 <https://www.example.com>, <example@example.com>

## 2-6. 이미지(Image)
이미지를 삽입할 수 있다.
```
![GitHub](https://user-images.githubusercontent.com/112846255/194908122-2388f06f-3c64-4e83-ad5b-d6d463956f4b.png)
```
![GitHub](https://user-images.githubusercontent.com/112846255/194908122-2388f06f-3c64-4e83-ad5b-d6d463956f4b.png)

## 2-7. 코드(Code)
단어 또는 구를 코드로 나타내려면 Backtick(`)으로 묶는다.
```
`code`
```
`code`

## 2-8. 수평선(Horizontal Rule)
수평선을 작성할 수 있다.
```
***
---
_________________
```
***
---
_________________

## 2-9. 탈출 문자(escape character)
마크다운 문서에서 텍스트 형식을 지정하는 데 사용되는 문자 그대로를 표시하려면 백슬래시(\)를 추가한다.
\
```
*text*
\*text\*
~~text~~
\~\~text\~\~
```
*text*

\*text\*

~~text~~

\~\~text\~\~



# 3. 마크다운 사용 방법
마크다운은 메모장부터 전용 에디터까지 많은 곳에서 활용할 수 있다.

- 웹 사이트, 문서, 노트, 책, 프레젠테이션, 이메일 메시지 및 기술 문서를 만드는 데 사용된다.
특히, 요즘 깃허브 README.md 파일에서 정말 많이 이용되어지고 있다.
- PR(Pull Request) 설명을 작성할 때도 쓰이고, 많은 디지털 노트를 사용할 때도 간편하게 키보드로 작성할 수 있게 도와준다.
- Markdown 형식의 텍스트를 포함하는 파일은 거의 모든 응용 프로그램을 사용하여 열 수 있다. 현재 사용 중인 Markdown 응용 프로그램이 마음에 들지 않으면 Markdown 파일을 다른 Markdown 응용 프로그램으로 가져올 수 있다.



이런 마크다운의 편리함 때문에 .md 파일들과 깃허브를 연동해서 다른 디지털문서 없이도 자신만의 문서를 관리하는 개발자도 많다.
