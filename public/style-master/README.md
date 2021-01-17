# potato's style
귀차니즘을 위해서 만든 스타일입니다.   
html 태그의 클래스 이름만 지정해서 스타일을 적용해 줍니다.    

# 사용설명서
## 기본 준비하기
1. 이 리포지토리를 복제하거나 다운받으세요.
2. 적절한 위치에 스타일 파일들을 넣어줍니다.
3. html에서 이 스타일을 불러옵니다. (경로는 알아서 수정하세요..)
```
    <link rel="stylesheet" href="./box.css">    
    <link rel="stylesheet" href="./border.css">    
    <link rel="stylesheet" href="./button.css">    
    <link rel="stylesheet" href="./font.css">    
```

4. 준비가 완료되었습니다! 아래 설명서를 잘 읽어주시기 바랍니다!   

* 참고: 색깔 이름은 <a href = "https://www.w3schools.com/colors/colors_names.asp">여기<a>를 참고했습니다.

## font.css
폰트 속성을 정해줍니다. 
### text-alligin 기능
`center, right, left, justify`   
일반 css와 속성 이름이 같습니다. 택스트 정렬 방향을 정해 줍니다.
#### center
글자를 가운데에 정렬해 줍니다.
#### right
글자를 오른쪽에 정렬해 줍니다.
#### left
글자를 왼쪽에 정렬해 줍니다.
#### justify
가능한 많은 줄이 한 줄에 들어가고 그 줄의 첫 번째 단어는 왼쪽 가장자리를 따르고 마지막 단어는 오른쪽 가장자리를 따르도록 내용 공간이 줄어 바뀝니다.

### text-decoration 기능
`overline, underline, line-through`    
이 기능 역시 css와 속성 이름이 같습니다. 택스트를 꾸며 줍니다.
#### overline
글자에 윗줄을 긋습니다.
#### underline
글자에 밑줄을 긋습니다.
#### line-through
글자에 취소선을 긋습니다.

### text-transform 기능 
`uppercase, lowercase, capitalize`   
이 기능도 css와 속성 이름이 같습니다. 택스트의 대.소문자를 정해줍니다.
#### uppercase
모든 글자를 대문자로 정합니다.
#### lowercase
모든 글자를 소문자로 정합니다.
#### capitalize
모든 단어의 첫 글자를 대문자로 정합니다.

### font-size 기능 
`xx-large, x-large, large, medium, small, x-small, xx-small, intro`   
클래스 이름을 정해주면 클씨 크기가 변합니다. 각 클래스 이름에 대한 설명은 생략합니다.
#### intro
font-size를 xx-large, font-weight를 bold로 정합니다. 제목 쓸 때 유용합니다.

### color 기능
글씨 색을 정해줍니다. 클래스 이름을 색 이름으로 하시면 됩니다.

## box.css
기본 배경색을 정해줍니다.
### opacity 기능
투명도를 정해 줍니다. 0.1에서 0.1단위로 0.9까지 사용 가능합니다. 클래스 이름을 op1~9 으로 하시면 됩니다.

### background-color + color (서로 보색 관계) 지정 기능
태그의 기본적인 배경색과 내부에 있는 택스트를 배경색의 보색으로 적용합니다. 만약 택스트 색깔이 맘에 들지 않은 경우 태그에서 스타일로 덮어쓰시면 됩니다. 클래스 이름은 box-색깔이름 으로 하시면 됩니다.

## border.css
Border 속성을 정해 줍니다.
### border-color 기능 
Border의 색을 정해줍니다. 클래스 이름은 border-색깔이름 으로 하시면 됩니다.
### border-radius 기능 
`smallroundborder, bigroundborder`       
Border을 둥글게 만들어 줍니다.
#### smallroundborder
Border의 radius를 4px로 정해줍니다.
#### mediumroundborder
Border의 radius를 6px로 정해줍니다.
#### bigroundborder
Border의 radius를 8px로 정해줍니다.
### border-style 기능 
`border-dotted, border-dashed, border-solid, border-double, border-groove, border-ridge, border-inset, border-outset`    
Border의 스타일을 정해 줍니다. 위 이름으로 클래스 이름을 정하세요.
## outline.css  
Outline의 속성을 정해줍니다.  
### outline-color 기능 
Outline의 색을 정해줍니다. 클래스 이름은 outline-색깔이름 으로 하시면 됩니다.
### outline-style 기능 
`outline-dotted, outline-dashed, outline-solid, outline-double, outline-groove, outline-ridge, outline-inset, outline-outset`   
Outline의 스타일을 정해줍니다. 위 이름으로 클래스 이름을 정하세요.
### outline-width 기능 
`outline-thin, outline-medium, outline-thick`   
Outline의 두께를 정해줍니다. 위 이름으로 클래스 이름을 정하세요.
