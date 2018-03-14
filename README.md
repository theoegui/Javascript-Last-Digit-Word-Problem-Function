# Javascript-Last-Digit-Word-Problem-Function
This problem really deals with data types : Strings vs Numbers 
The lastDigit function accepts two non-negative integer arguments and returns true or false if they have the same last digit.

For example, lastDigit accepts two non-negative integer values. Return true if both number arguments have the same last digit, such as 27 and 57 and false if the last two digits are not equal, such as 998 and 999.



Given EXAMPLES
- INPUT: lastDigit(22,32);
- OUTPUT: true


- INPUT: lastDigit(77, 999);
- OUTPUT: false


- INPUT: lastDigit(33,3);
- OUTPUT: true


Soultion : 

function lastDigit(num1, num2){
	num1 = num1.toString();
	num2 = num2.toString();

	if(num1[num1.length-1] === num2[num2.length-1]){
		return true;
	} else {
		return false;
	}
}
