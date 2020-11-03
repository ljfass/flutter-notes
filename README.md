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
