**yoit**, gottem

Here is an example of code that will take an array and sort it either from **largest to smallest** ("bts") or **smallest to largest**:
`

boolean isPalindrome(int[] a) {
		for (int j = 0; j < a.length/2; j++) {
			if (a[j] != a[(a.length-1)-j]) {
				return false;	
			}
		}
		return true;
}

`


