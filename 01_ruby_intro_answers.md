# Ruby Intro Answer Sheet

## Check your ruby version
Your ruby version: 2.6.0

## Floats and integers 
1. 3.0 / 2
    1. Expected (integer or float):    float  
    2. Actual (integer or float): float
    3. Answer: 1.5
2. 3 / 2.0
    1. Expected (integer or float):   float   
    2. Actual (integer or float): float
    3. Answer: 1.5
3. 4 ** 2.0
    1. Expected (integer or float):  integer        
    2. Actual (integer or float): float
    3. Answer: 8.0
4. 4.1 % 2
    1. Expected (integer or float):   float   
    2. Actual (integer or float): float
    3. Answer: 0.999999994

## Strings
1. "tom" * 3
    * Expected:  tom tom tom          
    * Actual: tomtomtom
2. "tom" + "tom"
    * Expected:   tomtom         
    * Actual:
3. "tom" + 1
    * Expected:tomtom            
    * Actual: fail - no implicit conversion of integer into string
4. "tom" / 2
    * Expected: fail        
    * Actual:  fail - undefined method

## Calculations in IRB
1. How many hours are in a year?
    * Answer: 24 * 365 = 8760
2. How many minutes are in a decade?
    * Answer: 60 * 24 * 365 * 10 = 5256000
3. How many seconds old are you?
    * Answer: (Time.new)-(Time.local(1991, 11, 12))