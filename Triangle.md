Cho chiều dài 3 cạnh tam giác là a b c số Nguyên Dương:
1. Kiểm tra a, b, c có phải là tam giác? 
2. Kiểm tra tam giác đều?
3. Kiểm tra tam giác cân?
4. Tam giác vuông?
5. Tam giác bình thường?

## [Java Guide](https://github.com/longphung/JavaExercises)

### Câu lệnh `if () {} else {}`
```java
if () {
	// code if TRUE
} else {
	// code if FALSE
}
```
### Cấu trúc `else if`
```java
if (condition1) {
	// code ...
} else if (condition2) {
	// code ...
} else if (condition3) {
	// code ...
}
```

**Ví dụ**: Chương trình xét điểm thi
```java
double grade = 90;

if (grade < 50) {
	System.out.println("Failed");
} else if (grade < 65) {
	System.out.println("Passed");
} else if (grade < 75) {
	System.out.println("Credit");
} else if (grade < 85) {
	System.out.println("Distinction");
} else {
	System.out.println("High Distinction");
}
```

**Expected Output:** `High Distinction`



