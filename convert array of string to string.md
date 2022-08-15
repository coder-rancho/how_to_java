```Java
// Using join()
List<String> array = new ArrayList<>(); // array = ["N", "a", "man"]
String str = String.join("", array); // "Naman"
```

### join()
The join() method returns a new string with the given elements joined with the specified delimiter.

Syntax
```java
String.join(CharSequence delimiter, Iterable elements)
// or
String.join(CharSequence delimiter, CharSequence... elements)
```

> Note: `elements` should be a object of class that implements `charSequence`, for e.g. `String, StringBuffer, CharBuffer`.
