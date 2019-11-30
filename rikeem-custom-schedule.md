## wk T-1
- review basic python tutorial .org exercises

## wk 0
- advanced python tutorial .org exercises
- research and learn about objects and classes
- keep notes of all interesting exercises/snippets in a text editor like spyder:
    - comments in py files
    - a .md file for each week with some fomratted code snippets using ``` to delimmit the code

## wk1 (last week, due last tuesday)
- install anaconda and an editor (spyder, sublime, vscode)
- create repo on github and locally (cd code/rikeem-u/ && git init .)
- develop habit of git status, git commit, git push, git log

## wk2 (this week, due tomorrow)
- load csv file of heights/weights gender
- probability of rolling a 7 with 2 dice

## wk3 (Nov 12)
- load html table of heights/weights gender (pd.read_html('https://totalgood.org/midata/teaching/rikeem-u/...')
- linear regression on heights/weights gender (sklearn LinearRegression class/object
- `np.random.rand`

## wk4 (Nov 19)

### data cleaning
- find an interesting table of data in html from wikipedia or elsewhere
- use pd.read_html to load your table of data into a dataframe
- write your dataframe of data to a csv and an html file
- use ssh to upload your table to totalgood.org/midata/teaching/rikeem-u

### probability/statistics
- use a nested for loop to create all the possible pairs of dice rolls and their sum/score
- create a dataframe with 3 columns for the 2 die rolls and the sum
- use df.sum() and df.value_counts() to compute the probability of every possible sum (try to do this without a for loop)

## wk5 (Nov 26)

### data
- clean up your dataset from last week so that it contains only floats (numbers)
    - loop through the elements of a column to trsnform the strings into floats/ints using `strip()`, `.lstrip()`, `.rstrip()`, `.replace()`, `.split()`, indexing/slicing with `[]`,
    - use  `float()` and `int()` to "coerce" strings into ints or floats (this only works if the string contains a valid floating point or integer representation of a numerical value like `"1e23"` or `"-1.234"`)
- plot a histogram, line plot, scatter plot of your data set, and explain what you learned from the plot(s)
- use `.describe(...)` on your dataset and explain what it tells you about your data
### probability & statististics
- use `from itertools import product` to compute all the possible dice rolls (should get same results as in wk4)
    - read up on Cartesian product and Sets
    - Cartesian Product is not the normal multiplication product you are used to. A better word for it might be "combinations". It's a way to combine two or more sets. It's how you "multiply" mathematical `set`s.
    - read the docs on itertools.product()
- use `.value_counts` and .plot (or just .hist() without `value_counts`) to display a histogram of dice roll sums



- research dot product, inner product and outer product


## wk 6.
- generalize your dice code to handle any number of dice (use a function definition and keyword arguments)
- make it a command line app that processes `sys.argv` in a main function

## wk 7.
- compute and plot the cumulative probability distribution for any number of die rolls added together

## wk 8
- write python code that can sample from that discrete random distribution for any number of dice rolled.

## wk 9
- make your dice rolling simulator more efficient by using only one call to `np.random.rand` no matter how many dice your distribution is designed for
## wk9 (New Year ?)
- how would you do this for a continuous distribution like the heights and weights of people? we'll have to work on that together, because I haven't done that in a while

