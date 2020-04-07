# USACO Assessment Prep

Make sure you know how to do everything on this page before you take the assessment. It is ok to do Google searches during the assessment, but that should just be to remind yourself of syntax, not learn it for the first time.

## Coding Fundamentals
- Loops: for and while
- Variables: strings and integers
- Conditionals
- Arrays: adding, removing, updating, length

## String Fundamentals
Most of the problems you'll need to manipulate strings, especially since the input and output are often strings. Make sure you are familiar with the following:
- Length
- Substring
- Access a certain character index
- Search / Find / IndexOf
- Split

## Input and Output
You will create your own file for each individual problem and run the test inputs. Here are some examples to get started:

**Python**
```python
import sys
line = sys.stdin.readline()
sys.stdout.write(str(len(line))) #write a string, not an int
sys.stdout.write("\n") #new line character
```

If you save the input as a txt file, you can run it like this:
```
python water.py < water-input.txt 
```

**Java**
```java
import java.util.Scanner;
public class Solution { 
   public static void main(String[] args) { 
	Scanner sc = new Scanner(System.in); 
	String line = sc.next();
	System.out.println(line.length());
	sc.close();
   }
}
```
When you run the program using Eclipse, you can paste the input into the console and hit enter.

**C++**
```cpp
#include <iostream>
using namespace std;
int main() {
  int a, b;
  cin >> a >> b; //read input from stdin
  cout << a + b << "\n"; //prints a + b to stdout
  return 0;
}
```
