### Key Value pair

```yaml
Name: "Aryan Sharma"
1: "This a list"
```

### List

```yaml
- apple
- mango
- Banana
- banana
```
or

```yaml
cities: [new delhi, patna,gujrat]
```

### String and Variables

```yaml
name: Aryan Sharma
fruit: "Mango"
job: 'Advocate'
age: 65
marks: 10.33
booleanValue: No, N, false, False, FALSE 
```

### Multiline String

```yaml
Address: |
  01
  Delhi
  India
```
Single line in multiple line.

```yaml
message: >
  This all
  will be in a single
  line

```

### Nested Mapping

```yaml
names: aryan
role:
  age: 22
  job: student
```  

### Nested Sequence

```yaml
-
  - mango
  - apple
  - banana
-
  - marks
  - roll
```

##### Specify the data type

```yaml

# Integer
Zero: !!int 0
positiveNumber: !!int 45
negativeNumber: !!int -45
hexa: !!int 0x45

# Float
mark: !!float 56.55
infinity: !!float .inf
not a num: .nan
itNot: !!bool false

# String
string: !!str "hello"

# Null
surname: !!null #null or NULL ~ 
~: this a null key

# Exponential Numbers
myNum: 6.22ES56

# Dates and time
date: !!timestamp 2002-01-02
no Time zone: 2012-12-15T02:59:43
India Time: 2012-12-15T02:59:43 +5:30
```
