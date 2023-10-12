## 강의 제목

### 1. 강의 중간 제목

####  강의 중간 하위 제목


<details><summary>
화살표 내용 작성 
</summary>

주석
*Write here!*
</details>



목록 표시
-
-
-
-
-


링크 연결
https://github.com/pangse

이미지 경로  및 사이즈
```
![title](http://fakeImgUrl.com/img/01.jpg)
![title](/img/myComputer.png)
![title](/img/myImg.png){: width="100" height="100"}
![title](/img/myImg.png){: width="100%" height="100%"}
```

<img src="https://pangse.github.io/assets/img/about-bg.jpg" width="300" height="300">

# css

```
/* 새 css class */
.center {
  display: block;
  margin: auto;
}
```
css 클래스를 만든 후, 마크다운 파일로 와서 이미지에 적용시킨다.


```
![title](/img/myImg.png){: width="300" height="300"){: .center}
```



~~~javascript
def func(a,b):
    return a+b

print(func(a,b))
~~~



~~~xml
<mvc:View controllerName="sap.btp.hellowordui5.controller.View1"
    xmlns:mvc="sap.ui.core.mvc" displayBlock="true"
    xmlns="sap.m">
    <Page id="page" title="{i18n>title}">
        <IllustratedMessage id="ilm1" enableVerticalResponsiveness="true" illustrationType="sapIllus-SuccessBalloon">
            <additionalContent>
                <Button id="but1" text="Alert" class="sapUiSmallMarginBottom" press=".onAlertMessageBoxPress" width="280px" ariaHasPopup="Dialog"/>
            </additionalContent>
        </IllustratedMessage>
        <content />
    </Page>
</mvc:View>

~~~


~~~json
{
  "xsappname": "sapbtphellowordui5",
  "tenant-mode": "dedicated",
  "description": "Security profile of called application",
  "scopes": [
    {
        "name": "uaa.user",
        "description": "UAA"
    }
    ,
    {
        "name": "$XSAPPNAME.Viewer",
        "description": "Viewer"
    },
    {
        "name": "$XSAPPNAME.Admin",
        "description": "Administrator"
    }
  ],
}

~~~


11. 표 Permalink

| --- | NumPy | PyTorch |
| --- | --- | --- |
| 1 | 2 | 3 |
| 4 | 5 | 6 |
| 7 | 8 | 9 |

