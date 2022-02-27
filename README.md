# pythonrecursion
Some simple functions I wrote in python when I was first learning recursion
1.  sum_list(vals): given a list of integers vals, determines the sum of the list
2.  reverse_string(st): takes in a string and returns a string with the characters ordered in reverse
3.  fibonacci(n): take an integer value n as an argument and return Fn, the n-th Fibonacci number
4.  double_reverse(str_list): takes in a list of strings and returns a new list which has all of the original strings revered, in reverse order.
ex: double_reverse(['these', 'words', 'will', 'be', 'reversed'])
returns ['desrever', 'eb', 'lliw', 'sdrow', 'eseht']  
5. deep_square(nested_list): takes in a list and will go through a nested list of integers, and then return the squared result of each integer, preserving the nested list structure
ex. deep_square([[-1, [2], [3], [[[-4,5]]], [], []]])
returns [[1, [4], [9], [[[16, 25]]], [], []]]
