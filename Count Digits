//{ Driver Code Starts
// Initial Template for Java

import java.io.*;
import java.util.*;

class GFG {
    public static void main(String args[]) throws IOException {
        BufferedReader read = new BufferedReader(new InputStreamReader(System.in));
        int t = Integer.parseInt(read.readLine());
        while (t-- > 0) {
            int N = Integer.parseInt(read.readLine());
            Solution ob = new Solution();
            System.out.println(ob.evenlyDivides(N));

            System.out.println("~");
        }
    }
}
// } Driver Code Ends


// User function Template for Java

// User function Template for Java

class Solution {
    static int evenlyDivides(int n) {
        int count = 0;
        int originalN = n; // Store the original value of n

        int tempN = n; // Use a temporary variable to extract digits

        while (tempN > 0) {
            int digit = tempN % 10;
            if (digit != 0 && originalN % digit == 0) {
                count++;
            }
            tempN /= 10; // Modify the temporary variable
        }
        return count;
    }
}
