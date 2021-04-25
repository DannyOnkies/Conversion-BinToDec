# Conversion-BinToDec
*Converts a binary number to decimal*

![Image](https://github.com/DannyOnkies/Conversion-BinToDec/blob/main/pic/Algorithm%20to%20convert%20Binary%20to%20Decimal.gif?raw=true)

To convert a binary number to a decimal just multiply the digits of the number to be converted by suitable '''sh powers of 2''' and add the products together

Here is how to proceed:

1) Assign the position to the digits of the considered number, starting from the first digit on the right and moving to the left.
    The first digit on the right is the one in the first position, the digit to its left is the one in the second position, and so on.

2) Multiply the first digit by 2^0, the second by 2^1, the third by 2^2, and continue in this way until all are exhausted.

3) Add the products thus obtained.

The resulting number is the result of the base ten conversion. 
