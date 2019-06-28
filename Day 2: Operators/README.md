## Task 
Given the meal price (base cost of a meal), tip percent (the percentage of the meal price being added as tip), and tax percent (the percentage of the meal price being added as tax) for a meal, find and print the meal's total cost.</br>

**Note:** Be sure to use precise values for your calculations, or you may end up with an incorrectly rounded result! </br>

## Input Format

There are 3 lines of numeric input: </br>
The first line has a double, mealCost (the cost of the meal before tax and tip). </br>
The second line has an integer, tipPercent (the percentage of mealCost being added as tip). </br>
The third line has an integer, taxPercent (the percentage of mealCost being added as tax).</br>

## Output Format

Print the total meal cost, where totalCost is the rounded integer result of the entire bill (mealCost with added tax and tip). </br>

## Sample Input

<pre>
12.00
20
8
</pre>

## Sample Output

<pre>
15
</pre>

## Explanation

**Given:** </br>
mealCost = 12, tipPercent = 20, taxPercent = 8 </br>

**Calculations:** </br>
 tipPercent = 12 * 20/100 = 2.4</br>
 taxPercent = 12 * 8/100 = 0.96</br>
 totalCost = mealCost + tip + tax = 12 + 2.4 + 0.96 = 15.36</br>
 round(totalCost) = 15</br>

We round totalCost to the nearest dollar (integer) and then print our result, 15.</br>
