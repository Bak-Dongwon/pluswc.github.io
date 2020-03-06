---
title: "마크다운 문법"
excerpt: "두 번째로 마크다운 문법을 알아보자."

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2020-03-05T17:45:10
---

#### 2.1 텍스트 줄바꿈  

기본적인 텍스트 표기 방식이다.
마크다운은 줄바꿈을 인식하지 않는다.

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번  
표기해야 한다.

여러가지 강조 표시가 존재한다. 첫번째로 *single asterisks*,
두번째로 _single underscores_, 세번째로 **double asterisks**,
네번째로 __double underscores__, 다섯번째로 ~~ cancelline~~가 있다.





#### 2.2 글머리 달기
# This is a H1  
## This is a H2  
### This is a H3  
#### This is a H4  
##### This is a H5  
###### This is a H6  

#### 2.3 인용
인용문을 사용할때는 > 블럭 인용 문자를 사용하면, 단계별 깊이를 지원
```
> This is a blockqute
```
> This is a blockqute

```
> This is a blockqute  
>> This is a blockqute  
>>> This is a blockqute  
```
> This is a blockqute  
>> This is a blockqute  
>>> This is a blockqute  

#### 2.4 정렬 목록  
1. 봄  
2. 여름  
3. 가을  
4. 겨울  

#### 2.5 비정렬 목록
```
* 과자  
  * 라면  
    * 사탕  
```
* 과자  
  * 라면  
    * 사탕  

```cpp
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5 + 6;
  cout << "Hello World! " << x << std::endl();
}
```
#### 2.6 코드 인용  
```
```    
function test() {
  console.log("notice the blank line before this function?");
}
```
```

```    
function test() {
  console.log("notice the blank line before this function?");
}
```

```python
s = "Python syntax highlighting"
print(s)
```


#### 2.7 수평선  

모두 수평선을 만드는 여러가지 표기법이다.

```
* * *  
***  
*****  
- - -  
--------------------------  
```

* * *  
***  
*****  
- - -  
--------------------------  


#### 2.8 링크
- 링크 표시법 :[Title](link)
[opgg](op.gg)

* 주소 직접 표시법

```
<op.gg>
```
op.gg

#### 2.9 이미지 삽입

```
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)
```

![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)


```
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg){: .align-center}
```

![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg){: .align-center}

```
![키보드 사진](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg "내 키보드 사진"){: .align-center}
```

![키보드 사진](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg "내 키보드 사진"){: .align-center}
