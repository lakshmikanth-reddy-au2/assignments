### For the day 16-July-2020

Given a chemical formula as a string, the task is to get the count of atoms in the chemical formula.
```
Input: str = "Fe2H3OH"
Output: Fe 2
        H 4
        O 1

Input: str = "NaCl2NaO2"
Output: Na 2
        Cl 2
        O 2
```

### For the day 17-July-2020

Write a Javascript function that takes a string and compresses it.

You can use a simple character count algorithm for the compression. So for each character in the input string, replace it with a number if the next character(s) are the same.

So an input string like `AAABCCDDDD` will become `A3BC2D4`.

### For the day 18-July-2020

Write a Javascript program that removes duplicates from an array.

For example, if the input array is `[1, 2, 2, 3, 4, 5, 6, 6, 7]`, the output of the program should be [1, 2, 3, 4, 5, 6, 7]

### For the day 19-July-2020

Write a Javascript function that prints the frequency of all the elements in an array.

Examples:
```
Input :  arr = [10, 20, 20, 10, 10, 20, 5, 20]
Output : 10 -> 3
         20 -> 4
         5  -> 1

Input : arr = [10, 20, 20]
Output : 10 -> 2
         20 -> 1
```



### For the day 20-July-2020

Roman numerals are represented by seven different symbols:
```
Symbol       Value
I                1
V                5
X               10
L               50
C              100
D              500
M             1000
```

For example, two is written as `II` in Roman numeral - just two one's added together. Twelve is written as `XII`, which is simply `X` + `II`. The number twenty-seven is written as `XXVII`, which is `XX` + `V` + `II`.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not `IIII`. Instead, the number four is written as `IV`. Because the one is before the five, we subtract it making four. The same principle applies to the number nine, which is written as `IX`. There are six instances where subtraction is used:

- `I` can be placed before `V` (5) and `X` (10) to make 4 and 9. 
- `X` can be placed before `L` (50) and `C` (100) to make 40 and 90. 
- `C` can be placed before `D` (500) and `M` (1000) to make 400 and 900.

Examples:
```
Input: 3
Output: "III"

Input: 4
Output: "IV"

Input: 9
Output: "IX"

Input: 58
Output: "LVIII"

Input: 1994
Output: "MCMXCIV"
```
Assume that, the input integer is guaranteed to be within the range from 1 to 3999.


### For the day 21-July-2020


Given `n` pairs of parentheses, write a function to generate all combinations of well-formed parentheses.

For example, given n = 3, a solution set is:
```
[
  "((()))",
  "(()())",
  "(())()",
  "()(())",
  "()()()"
]
```



### For the day 22-July-2020 (Create a React app )

1. Use the timer example at https://reactjs.org/ and modify it to tick at every 100 millisecond.
0.0, 0.1, 0.2 -> ... 
2. Add this .jsx code to an npm project. [Reference](https://reactjs.org/docs/add-react-to-a-website.html#add-jsx-to-a-project)
3. Use `npx` commands to compile .jsx to js.
4. Use the compiled file as a script in your html file.
5. Give the html an `h1` of 'React 100ms Counter'.

**Hint:** Use `number.toFixed()` to display `45` as `45.0`. [Reference](https://www.w3schools.com/jsref/jsref_tofixed.asp)


### For the day 23-July-2020

Create a function which takes a state as input and loops through the data to output the cities that belong to that state. The data can be found in the file [cities.json](data/cities.json)

Example: getCities("Telangana");
Output: ["Hyderabad", "Warangal", "Nijambadh", "Rangareddy".....]

### For the day 24-July-2020

Create a Javascript function which takes author and language as input nd loops through the data to output the titles that the author has written in that particular language. [books.json](data/books.json)

example: getTitles("Chinua Achebe", "English")
Output: ["Things Fall Apart"]