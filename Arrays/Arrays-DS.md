# Arrays - DS

https://www.hackerrank.com/challenges/arrays-ds

```java
import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int n = in.nextInt();
        int arr[] = new int[n];

        for(int i=0; i<n; i++) {
            arr[i] = in.nextInt();
        }

        for(int j=n-1; j>-1; j--) {
            System.out.printf("%d ", arr[j]);
        }

    }
}
```