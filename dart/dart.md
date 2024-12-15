# Dart

dartpad.dartlang.org


# Condition

```
var a =10;
  (a == 10) ? print('hello'): print('no hello');
}
```

# String to Number

num.parse();

```
var n = num.parse('345');
  print(n -100);//245

```

# Concat

```
var nine = 9;
  print('this is number : ${nine}');
```

# List

```
 //List
  var listItem = [1, 'hello', 2, 'goodbye'];
  print(listItem[0]);//1
  print(listItem[1]);//hello
 for (var i = 0; i < listItem.length; i++) {
    print(listItem[i]);
  }
  

```

List with default values

```
var fillableList = new List<int>.filled(3, 1, growable: true);
  //List length =3, default value =1, growable
 fillableList[0]= 1;
 fillableList[2] = 2;

  
  for (var i = 0; i < fillableList.length; i++) {
    print(fillableList[i]);
  }
  //1
  //1
  //2
```
## Basic Operation on List

add()
addAll()
insert()
insertAll()

```
 fillableList.add(3);
  
  for (var i = 0; i < fillableList.length; i++) {
    print(fillableList[i]);
  }
  //1
  //1
  //2
  //3
```
remove(), removeAt(), removeLast(), removeRange()
```
 fillableList.remove(2);
  
  for (var i = 0; i < fillableList.length; i++) {
    print(fillableList[i]);
  }
  //1
  //1
  //2-->removed
  //3
```
removeAll works with String

```
//removeAll works with String
  final characters = <String>{'Hello', 'Stay Calm', 'Goodbye', 'Hi'};
  characters.removeAll({'Hello', 'Stay Calm', 'Laugh'});
  print(characters); // {Goodbye, Hi}

```
# Map

```
var mapExp = {1:'Hello', 2:'Goodbye'};
  print(mapExp);
  print(mapExp[1]);//Hello
  print(mapExp[2]);//Goodbye
```

Example

```
var mapExp = {1:'Hello', 2:'Goodbye', 3:'Confused', 4: 'No Confused'};
  for (var i =1; i <= mapExp.length; i++)
  {
    print(mapExp[i]);
    //Hello
    //Goodbye
    //Confused
    //No Confused
  }
  print(mapExp);
  //{1: Hello, 2: Goodbye, 3: Confused, 4: No Confused}
 
 
```

