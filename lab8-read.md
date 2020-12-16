# Operators 

## Logical Operators
   operators in javascript check 2 values and return a boolean true or false value
     * operators in js are
       1. > : indicate value on left bigger than value on right.
       2. < : indicate value on left smaller than value on right.
       3. == : indicate value on left equal value on right.
       4. ===: indicate value and type of expressions on left equal value on right.
       5. >== : indicate value and type of expressions on left equal or bigger than expression on right.
       6. <== : indicate value and type of expressions on left equal or smaller than expression on right.
       7. !== : indicate value and type of expressions on left not equal to expression on right.
       8. != : indicate value of expressions on left equal or bigger than expression on right.
       9. >= : indicate value of expressions on left equal or bigger than expression on right.
       10. <= : indicate value of expressions on left equal or smaller than expression on right.

   * example : 
      1. 5 > 4     result : true
      2. 5 > '4'   reslut:  true.
      3. 5 >== '4' reslut:  false.
      4. 'anna' == 'anna'  result :true

## Comparison Operators.

   * Comparison operators in javascript used to compare two values or more and produce 1 boolean value either true or false.
     1. AND operator represented like this &&, at least all of inputs should be true.
       * exapmle true == true  result true
                 true == false result false
       * table of truth for the AND
          | x | y | r |
          |---|---|---|
          | T | T | T |
          | T | F | F |
          | F | F | F |
   
     2. OR operator represented like this ||, at least one of inputs should be true.
       * exapmle false == false  result false
                 true == false result true
       * table of truth for the OR
          | x | y | r |
          |---|---|---|
          | T | T | T |
          | T | F | T |
          | F | F | F |

   2. not operator represented like this ! then followed by && operator or || operator, and it reverse the result and i will take OR operator in this explination
       * exapmle !(false == false)  result true
                 !(true == false) result false
           because the ending result is true, not operator reverse it to false, vice versa
       * table of truth for the OR
          | x | y | r | -r  |
          |---|---|---|---|
          | T | T | T | F |
          | T | F | T | F |
          | F | F | F | T |

