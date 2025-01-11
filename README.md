# multiplication-table
2. Multiplication Table
import java.util.Scanner;
public class MultiplicationTable {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
System.out.print(&quot;Enter a number: &quot;);
int num = sc.nextInt();
System.out.println(&quot;Multiplication Table of &quot; + num + &quot;:&quot;);
for (int i = 1; i &lt;= 10; i++) {
System.out.println(num + &quot; x &quot; + i + &quot; = &quot; + (num * i));
}
}
}

Output:
Enter a number to print its multiplication table: 7
7 * 1 = 7
7 * 2 = 14
7 * 3 = 21
7 * 4 = 28
7 * 5 = 35
7 * 6 = 42
7 * 7 = 49
7 * 8 = 56
7 * 9 = 63
7 * 10 = 70
