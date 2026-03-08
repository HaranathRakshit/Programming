# Programming
C, C++, Java, Python - Installation Guidance 

<!DOCTYPE html>
<html>
<head>

</head>
<body>

<h2>Basic Syntax Comparison: Adding Two Numbers</h2>
<p>This table shows the bare-minimum code required to read two integers and print their sum.</p>



<table>
  <tr>
    <th>Language</th>
    <th>Code (Simplified)</th>
    <th>Execution Command</th>
  </tr>
  
  <tr>
    <td><strong>C</strong></td>
    <td>
<pre>#include &lt;stdio.h&gt;
int main() {
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d", a + b);
    return 0;
}</pre>
    </td>
    <td><code>gcc add.c && ./a.out</code></td>
  </tr>

  <tr>
    <td><strong>C++</strong></td>
    <td>
<pre>#include &lt;iostream&gt;
using namespace std;
int main() {
    int a, b;
    cin >> a >> b;
    cout << a + b;
    return 0;
}</pre>
    </td>
    <td><code>g++ add.cpp && ./a.out</code></td>
  </tr>

  <tr>
    <td><strong>Java</strong></td>
    <td>
<pre>import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print(sc.nextInt() + sc.nextInt());
    }
}</pre>
    </td>
    <td><code>javac Main.java && java Main</code></td>
  </tr>

  <tr>
    <td><strong>Python</strong></td>
    <td>
<pre>a, b = map(int, input().split())
print(a + b)</pre>
    </td>
    <td><code>python3 add.py</code></td>
  </tr>
</table>

</body>
</html>
