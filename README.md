# aug15_2025
The problem that i solved today in leetcode

Given an integer n, return true if it is a power of four. Otherwise, return false.

An integer n is a power of four, if there exists an integer x such that n == 4x.

Code:
class Solution {
    public boolean isPowerOfFour(int n) {
        long x=1;
        while(x<(long)n)
            x*=4;
        return x==n;
    }
}
