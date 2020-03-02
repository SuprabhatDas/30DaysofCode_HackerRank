### Day 0: Hello, World.

------------

**Task**

To complete this challenge, you must save a line of input from stdin to a variable, print Hello, World. on a single line, and finally print the value of your variable on a second line.

**Input Format**

A single line of text denoting `inputString` (the variable whose contents must be printed).

**Output Format**

Print Hello, World. on the first line, and the contents of `inputString` on the second line.

------------

**Solution**

```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;
public class Solution {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in); 
		String inputString = scan.nextLine(); 
		scan.close(); 
		System.out.println("Hello, World.");
        	System.out.println(inputString);
	}
}
```
