# 정리
- 절대 경로(/) : 루트 디렉토리(폴더)를 기준으로 움직인다.
- 상대 경로(./) : 현재 위치를 기준으로 움직인다.
- 상위 폴더(../) : 현재 위치의 상위 폴더로 움직인다.
- branch를 만들어서 메인 코드/ 개발용 코드를 나누고, 필요할 때 메인에 합친다.
## CSS
- 내부 스타일: head 태그 내부에 style 태그로 정의한다.
``` html
<style>
    h1, h2, h3, h4, h5, h6 {
        color: yellow;
        background-color: red;
    }
</style>
```
- 외부 스타일: HTML 문서와는 별개의 파일에서 스타일을 지정하는 방법. 스타일을 한 번에 작성해서 여러 HTML 문서에 적용할 수 있기에 유지보수에 용이.
- Cascading: 여러 스타일 규칙이 적용될 때, 우선순위에 따라 스타일이 결정된다. 외부스타일 < 내부스타일 < 인라인스타일 로 계단식 성격을 나타낸다.


# margin과 padding
## margin
- Object와 화면과의 여백 **(외부여백)**
- margin-top, margin-left, margin-right, margin-bottom
## padding
- Object 내의 **내부여백** 
- padding-top, padding-left, padding-right, padding-bottom
## 예제
```
    #box1 {
        background-color:green;
        margin-left:10px;
    }
    #box2 {
        background-color:blue;
        padding-top:10px;
    }
```

