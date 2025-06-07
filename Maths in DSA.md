- All the conversion things :
	- Hexa to Decimal
	- Binary to Decimal
	- Octal to Decimal
- Find Even Odd
- Reverse the num
	- using units tens hundreds.
- Count the digits
	- One approach - Using unit tens approach and just adding the counter to count it.
	- Second approach (*Faster one*) - Use log to get the count of digits.
	- Code (2nd approach) :
		```java
		public static void countDigitsusingLog(int num) {
		
		if(num==0) {
		
		System.out.println("Digits are : 1");
		
		return;
		
		}
		
		int count1=(int)((int)Math.log(num)/Math.log(10))+1;
		
		int count = (int)Math.log(num)+1;
		
		System.out.println("Digits are : "+count1);
		
		}
		```
- 