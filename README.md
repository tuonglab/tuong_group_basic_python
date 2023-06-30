# tuong_group_basic_python
Basic template repository for python classroom for Tuong group students.

This repository holds the basic scripts/questions for basic python usage to prep you for advanced analysis in single-cell. The idea is that there are simple functions and objectives included in this repository for everyday python usage. However, I have written mistakes into the codes in the `learn` folder and it is your task to find the mistakes and suggest the solutions. Good luck and hope you learn something from this!

## lists

The first learning plan is on `lists`.

A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements. Each element or value that is inside of a list is called an item. Just as strings are defined as characters between quotes, lists are defined by having values between square brackets `[]`
https://www.w3schools.com/python/python_lists.asp

The objective for this learning plan is to learn the simplest way to interact with python which is storing items/elements in a `list`. There are many ways to manipulate a list so this is just an introduction. We use `lists` all the time for single-cell analysis, including for inserting new metadata, forming lists of items we want to plot etc. Imagine you have 80,000 cells and you want to colour them by treatment status and also by cell-type. How would you construct this information so that we can create the relevant treatment status + cell-type information for each cell e.g. "treated_B cell", "untreated_B cell"? You can achieve this creating a `list` that holds this information!

There are 4 simple functions written in `learn/learn_list.py` but the tests are failing for each of them. Can you fix them up so that the tests succeed?

## dictionary

The second learning plan is on `dictionary`.

Dictionaries are used to store data values in key:value pairs. Dictionaries are defined by having values between square brackets `{}`
https://www.w3schools.com/python/python_dictionaries.asp

The objective of this part of the learning plan is to learn how to use dictionaries for matching/changing values to suit our needs, which is very relevant for single-cell analysis.
Imagine you have 10 clusters that you identified but you want to give each of them a biologically meaningful name. How would you go about changing the individual names? You can achieve this using `dictionaries`!

There are 2 functions written in `learn/learn_dict.py` but the tests are failing for each of them. Can you fix them up so that the tests succeed?

## dataframes

The third learning plan is on `dataframe`. We use the popular `pandas` package to interact with dataframes.

A `pandas` `DataFrame` is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.
https://www.w3schools.com/python/pandas/pandas_dataframes.asp#:~:text=What%20is%20a%20DataFrame%3F,table%20with%20rows%20and%20columns.

The objective of this part of the learning plan is to learn how to slice the `DataFrame` object so that we end up with the information that we want. This is very important for how we deal with single-cell data. Imagine that you have 10,000 cells but you only want to subset to just 2,000 of them as they are from the spleen and not any other organ. How would you go about doing this? You can achieve this by slicing the `DataFrame` to only contain the relevant cells!

There are 2 functions written in `learn/learn_pandas.py` but the tests are failing for each of them. Can you fix them up so that the tests succeed?
