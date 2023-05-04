# 호스팅이란?
웹은 클라이언트 프로그램과 서버 프로그램을 통해 작동한다.
유저가 웹페이지에서 명령을 내리면, 클라이언트 컴퓨터가 서버 컴퓨터에게 명령에 대한 값을 요청하는데 이때, 서버 컴퓨터는 데이터 베이스에서 데이터를 찾아 클라이언트 컴퓨터에 보내주고, 클라이언트 컴퓨터는 이를 전달받아 유저에게 보여준다. 여기서 중요한 부분은 홈페이지 운영을 위해, 자료가 저장되는 공간인 서버가 꼭 필요하다.

![알아보기-전](https://user-images.githubusercontent.com/129261961/236128440-6cc63b2b-e822-4ac8-b7b4-28e585dee090.png)

그렇다면 ‘호스팅 뜻’은?
호스팅은 정보의 집약체인 서버의 전체 혹은 일부를 이용할 수 있도록 임대해 주는 서비스를 말한다.
서버를 관리하기 위해서는 24시간 내내 안정적으로 전기를 공급해야 하고, 빠르고 안정적인 인터넷 회선을 사용해야 하며, 철저한 보안 시스템을 갖추고 있어야 한다. 따라서 개인이 서버를 관리하기보다 전문 업체의 호스팅 서비스를 사용하는 것이 일반적이다. 

## 호스팅의 종류?
![호스팅 종류와 장단점](https://user-images.githubusercontent.com/129261961/236126985-5c59c704-14b9-4490-b682-be62033c3391.jpeg)


# HTML 기초
## 1. HTML이 무엇인가?
HTML(Hypertext Markup Language)은 일종의 마크업 언어로, 우리가 보는 웹페이지가 어떻게 구조화되어 있는지 브라우저로 하여금 알 수 있도록 정보를 제공한다. 페이지에 제목, 문단, 표, 이미지, 동영상 등 리소스들을 정의하고, 그 구조에 의미를 부여한다. 정적 언어라고도 불리며, 페이지의 뼈대와 의미에 중요성을 둔다. 

## 2. HRML 기본구조
다음은 HTML 문서의 기본적인 구조를 보여주는 그림이다.

![html_template](https://user-images.githubusercontent.com/129261961/236131549-4ddb2bf6-d10c-4f80-949c-ebf6f725bf35.png)

<code>!DOCTYPE</code> : 현재 문서가 HTML 문서 타입을 명시한다. (HTML5 문서 타입은 <code>!DOCTYPE html</code> 이다.)

<code>html</code> : HTML 문서의 루트(root) 요소를 정의한다.

<code>head</code> : HTML 문서의 메타데이터(metadata)를 정의한다.

- 메타데이터(metadata)란 HTML 문서에 대한 정보(data)로 웹 브라우저에는 직접적으로 표현되지 않는 정보를 의미한다.
- 이러한 메타데이터는 <code>title</code>, <code>style</code>, <code>meta</code>, <code>link</code>, <code>script</code>, <code>base</code>태그 등을 이용하여 표현할 수 있다.

<code>title</code> : HTML 문서의 제목(title)을 정의하며, 다음과 같은 용도로 사용된다.

- 웹 브라우저의 툴바(toolbar)에 표시된다.
- 웹 브라우저의 즐겨찾기(favorites)에 추가할 때 즐겨찾기의 제목이 된다.
- 검색 엔진의 결과 페이지에 제목으로 표시된다.
<code>body</code> : 웹 브라우저를 통해 보이는 내용(content) 부분이다.

<code>h1</code>~<code>h6</code> : 제목(heading)을 나타낸다.

<code>p</code> : 단락(paragraph)을 나타낸다.

