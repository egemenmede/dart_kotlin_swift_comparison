# Dart vs Kotlin vs Swift Comparison

### Basics, Variables & Constants
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>
<tr>
<td>
  
```dart
// Implicit type = int
var myVariable = 5;

// Explicit type: String
String name = "Kral";

// Dynamic type: dynamic
dynamic dinamik = "Dynamic";
dinamik = 5; // Valid

// Constant
final name = "Enes";
const name = "Enes";
// Anything that isn't known at 
// compile time 
// should be final over const.
```
[Difference between const and final](https://stackoverflow.com/questions/50431055/what-is-the-difference-between-the-const-and-final-keywords-in-dart)
  
</td>
<td>

```kotlin
// Implicit type = Int
var myVariable = 5 

// Explicit type: String
var name: String = "Kral"

// Dynamic type: dynamic
var dinamik: dynamic = "String"
dinamik = 5 // Valid

// Constant
// Fill
```

</td>
<td>
  
```swift
// Implicit type = Int
var myVariable = 5 
myVariable = "a string" // Not valid

// Explicit type: String
var name: String = "Kral"

// Dynamic type: Any
var dinamik: Any = "String"
dinamik = 5 // Valid

// Constant
let gender = "Man"
gender = "Woman" // Not valid
```
    
</td>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Enum
enum MessageKind {
    case placeholder
    // Associated values allowed.
    case image(URL)
    case text(String)

    // Computed variables & Static variables allowed.
    var debugPrint: String {
        switch self {
        case .image(let url):
            return "Url: \(url)"
        case .text(let text):
            return "Text: \(text)"
        default:            
            return "Placeholder"
        }
    }

    // Functions are allowed as well.
    func debugPrintFoo() -> String {
        debugPrint
    }
}
```
    
</td>
</tr>

<tr>
<td>
  
```dart
typedef GestureTapCallback = void Function();
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Type alias
typealias TapCallback = () -> Void
```
    
</td>
</tr>


<tr>
<td>
  
```dart
// Check type
if (myVariable is String) { .. }
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Check type
if myVariable is String { .. }
```
    
</td>
</tr>

</table>

### Strings
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Declaration
var string1 = "String";
var string2 = 'String';

// Multiline
var multilineStr = """
Here you can have your string multiline for easier readability;
Start & end with 3 quote character.
""";

// String interpolation
var name = "Enes";
print("Hello $name");
print("For objects use ${person.name}");
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Declaration
let string = "String"

// Multiline
let multilineStr = """
Here you can have your string multiline for easier readability;
Start & end with 3 quote character.
"""

// String interpolation
let name = "Enes"
print("Hello \(name)")
print("For objects use \(person.name)")
```
    
</td>
</tr>

</table>

### Functions
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>

### Control Flow
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>

### Collections
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>

### Optionals & Nullability
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>

### Extensions
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>

### Class, Struct, Protocol..
<table>
<tr>
<th> Dart </th>
<th> Kotlin </th>
<th> Swift </th>
</tr>

<tr>
<td>
  
```dart
// Fill
```
  
</td>
<td>

```kotlin
// Fill
```

</td>
<td>
  
```swift
// Fill
```
    
</td>
</tr>

</table>
