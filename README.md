# 66.-Plus-One
```C#
    public int[] PlusOne(int[] digits) {
        
        for(int i=digits.Length -1; i>=0 ; i--){
            if(digits[i]<9){
                digits[i] +=1;
                return digits;
            }
            
            digits[i] = 0;
        }
        int[] result = new int[digits.Length +1];
        result[0]=1;
        
        return result;
        
    }
```

## Complexity Analysis

* Time Complexity: O(N) ?????
* Space Complexity: O(N) ????
