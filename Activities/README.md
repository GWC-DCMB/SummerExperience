# Activities

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Starters](#starters)
	- [Day 2: Variables, Types, & Lists](#day-2-variables-types-lists)
	- [Day 3: Pandas](#day-3-pandas)
	- [Day 4: Numpy & Statistics](#day-4-numpy-statistics)
	- [Day 5: Plotting](#day-5-plotting)
- [Screenless](#screenless)

<!-- /TOC -->

## Starters

[Google Slides](https://docs.google.com/presentation/d/1ZxkFTjXVx5EyF-P2CG3gV0U3dUskxzWrQPV9D9oA1Og/edit?usp=sharing)

### Day 2: Variables, Types, & Lists

1. What are the types of each of the following variables?

    - `name = “Lilah”`
    - `age = 6`
    - `weight = 161.4`
    - `is_dog = True`

1. Think back to our animals 2D list:

    ```
    animals = [['cat','dog','elephant'],
               ['fish','seahorse','whale'],
               ['robin', 'cardinal', 'bat']]
    ```
    - How can we isolate the aquatic animals sub-list?
    - How can we isolate ‘whale’ from the animals list?
    - How can we find the length of the animals list?
    - How can we find the length of the air animals sub-list?
    - BONUS: How can we add ‘gecko’ to the land animals sub-list?

### Day 3: Pandas

1. What data frame methods would you use to see what is at the beginning and end of your data frame?
1. How would you find the number of rows and columns in the data frame?
1. See the code in the screenshot. Which
command will result in '65th' printed
to the screen? Check all that apply.

    ![dataframe](../Figures/pandas_example.png)

    - `df.iloc[0,0]`
    - `df["Congress"][0]`
    - `df.iloc[0, :][0]`
    - `df.iloc[0, 'Congress']`


### Day 4: Numpy & Statistics

1. We have a list called `height_in`. We want to convert these values to cm by multiplying all the values by `2.54`. How can we do this using `numpy`?
1. What statistics can we use to learn about the average of our data? What are the `numpy` functions you’d use to calculate these?
1. Say we split our array into two arrays: `height_cm_males` and `height_cm_females`.
    - What test would we use to see if there is a significant difference in height between the male and female groups?
    - What package do we use to perform this test?
1. We want to see if there is a strong relationship between height and age.
    - What statistic can we compute to test this?
    - What is the `numpy` function to calculate it?


### Day 5: Plotting

1. What kind of plot do we use when we want to see the change in one variable over time?
1. What kind of plot do we use when we want to examine the relationship between two variables?
1. What kind of plot do we use when we want to see the distribution of a continuous variable?
1. What kind of plot do we use when we want to see the distribution of a categorical variable?
1. What parameter helps us color our plots by a certain variable?


## Screenless

See our screenless activities here: [GWC-DCMB/activities](https://github.com/gwc-dcmb/gwc-dcmb/activities).
