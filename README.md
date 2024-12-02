# Python Data Structures vs JavaScript

**I am Abdul Samad. I know JavaScript and am now learning Python.**  
This document serves as comparative notes to help me learn Python with references to JavaScript equivalents.

## 1. Lists vs Arrays

- **Python**: `list` (dynamic, can hold mixed data types)
- **JavaScript**: `array` (flexible, can hold mixed data types)

```python
# Python
my_list = [1, "hello", 3.14]
my_list.append(42)
```

```javascript
// JavaScript
let myArray = [1, "hello", 3.14];
myArray.push(42);
```

---

## 2. Tuples vs Immutable Arrays

- **Python**: `tuple` (immutable, ordered)
- **JavaScript**: No direct equivalent (use `Object.freeze` for immutability)

```python
# Python
my_tuple = (1, 2, 3)
```

```javascript
// JavaScript
const myArray = Object.freeze([1, 2, 3]);
```

---

## 3. Dictionaries vs Objects/Maps

- **Python**: `dict` (key-value pairs, mutable, unordered before Python 3.7)
- **JavaScript**: `object` or `Map` (key-value pairs)

```python
# Python
my_dict = {"key": "value", "age": 30}
my_dict["name"] = "John"
```

```javascript
// JavaScript
let myObject = { key: "value", age: 30 };
myObject.name = "John";
```

---

## 4. Sets vs Sets

- **Python**: `set` (unordered, no duplicates)
- **JavaScript**: `Set` (unordered, no duplicates)

```python
# Python
my_set = {1, 2, 3}
my_set.add(4)
```

```javascript
// JavaScript
let mySet = new Set([1, 2, 3]);
mySet.add(4);
```

---

## 5. Strings

- **Python**: `str` (immutable, iterable)
- **JavaScript**: `string` (immutable, iterable)

```python
# Python
my_str = "hello"
char = my_str[1]
```

```javascript
// JavaScript
let myStr = "hello";
let char = myStr[1];
```

---

## 6. None vs Null/Undefined

- **Python**: `None` (represents null or no value)
- **JavaScript**: `null` or `undefined`

```python
# Python
value = None
```

```javascript
// JavaScript
let value = null;
```

---

## Summary Table

| Python  | JavaScript           | Description         |
| ------- | -------------------- | ------------------- |
| `list`  | `array`              | Dynamic, ordered    |
| `tuple` | Immutable array      | Immutable, ordered  |
| `dict`  | `object` / `Map`     | Key-value pairs     |
| `set`   | `Set`                | Unique, unordered   |
| `str`   | `string`             | Immutable, iterable |
| `None`  | `null` / `undefined` | Represents no value |

---

Save this as a **README.md** for quick reference.
