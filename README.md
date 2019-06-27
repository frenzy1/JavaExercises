# Table Of Content
- [1. Java Starter Code](#1-java-starter-code)
- [2. Java Scanner](#2-java-scanner)
- [3. Scanner Data Type Methods](#3-scanner-data-type-methods)
- [4. Operators](#4-operators)

## 1. Java Starter Code
```java
public class [FileName]
{
	public static void main (String[] args)
	{
		// CODE HERE
	}
}
```

## 2. Java Scanner
### Step 1: `import java.util.*;` at start of file
```java
import java.util.*;
```

### Step 2: initiate and use scanner object
```java
Scanner sc = new Scanner(System.in);
x = sc.nextLine();
```

## 3. Scanner Data Type Methods
|Input Types|Methods|
|---|---|
|boolean|nextBoolean()|
|byte|nextByte()|
|double|nextDouble()|
|float|nextFloat()|
|int|nextInt()|
|String|nextLine()|
|long|nextLong()|
|short|nextShort()|

## 4. Operators
### Arithmetic Operators
|Operator|Description|Example|
|---|---|---|
|+| Cộng 2 số|`a + b`|
|-| Trừ 2 số|`a - b`|
|\*| Nhân 2 số|`a * b`|
|\/| Chia 2 số|`a / b`|
|%| Chia lấy phần dư |`a % b`|
|++| Thêm 1|`i++`|
|--| Trừ 1|`i--`|

### Logical Operators
|Operator|Description|
|---|---|
|&&|Logical AND|
|\|\||Logical OR|
|!|Logical NOT. Cái này lấy giá trị đảo. T -> F. F -> T|
