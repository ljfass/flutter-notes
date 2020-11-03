# flutter-notes
flutter 笔记

## borderRadius写法:
  borderRadius: BorderRadius.circular(10.0)
  borderRadius: BorderRadius.only(
    bottomLeft: Radius.circular(10.0),
    bottomRight: Radius.circular(10.0),
  )
## border写法:
  border: Border.all(color: Colors.green, width: 0.5)
  border: Border(
    bottom: BorderSide(color: Colors.green, width: 0.5)
  )
## container背景图
  Container(
  height: xx,
  width: xx,
  decoration: BoxDecoration(  
    borderRadius: BorderRadius.only(  
      topLeft: Radius.circular(63),  
      bottomLeft: Radius.circular(63),  
    ),
    image: DecorationImag(  
      alignment: Alignment.centerLeft,  
      fit: BoxFit.cover,  
      image: AssetImage("assets/images/img.png"),  
    )
  )
)

## 设置scaffold背景颜色：
  --全局：  
    theme: ThemeData(  
      scaffoldBackgroundColor: xx  
    )  
  -- 局部：  
    Scaffold(  
      backgroundColor: xx  
    )
