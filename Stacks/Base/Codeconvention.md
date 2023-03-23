# code convention
- 코드는 코드의 통일성을 위하여, 팀, 혹은 언어별로 그 특성에 맞는 작명법이 있고 이를 code conversion 이라고 함.
- 이는 코드 가독성 향상을 위한 규정으로서 존재함.
- 코드작성시, 언어별로 여러 유의사항이 존재하나 C#및 JS는 아래를 따르시면 됩니다.

## 변수명
- snack case
- 모두 소문자와 공백이 들어가는 자리에는 _로 시작하면 됩니다
```js
    let is_bit_set //올바름
    let isBitSet   //🚫
```

## 함수명
- Carmel case
- 소문자로 시작해서, 띄워쓰는 다음부분을 대문자로 씁니다
```js
    function setCafeName(cafe_name) // 올바름
    function set_cafe_name(cafeName) // 코드의 통일성을 해침.
```

## Class
- 클래스 명은 **대문자로 시작해서** , 띄워쓰는 다음부분을 대문자로 씁니다.
```js
class Shop : // ok
class shop : // X
```
- 그러나 메서드명은 카멜케이스처럼 쓰시면 됩니다.
```Csharp
class LathionUnit{
    public int hp;
    public int UnitHp{   //접근가능한 메서드는 대문자로.
           get { getUnitHp();};
           set { this.hp=setUnitHp(); }
    }

}
```
```js
class Shop:
   constructer( name):
        this.cafeName=name // 메서드 

```

## 더읽기
https://velog.io/@cada/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%8A%A4%ED%83%80%EC%9D%BC-%EA%B0%80%EC%9D%B4%EB%93%9C-%EB%84%A4%EC%9D%B4%EB%B0%8D-%EC%BB%A8%EB%B2%A4%EC%85%98-%ED%8E%B8
