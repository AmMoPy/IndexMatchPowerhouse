# About

Index and Match: lookup powerhouse.

While you may be familiar with popular lookup functions in excel (V/Hlookup), you are probably not much acquaintedwith its beefed up version Index and Match. This is not a debate about which function is better, rather a simplification of what might seems complex at the first glance.

Why use Index and Match:

- Flexibility, you lookup data no matter how columns are positioned.
- Way faster if you are working with large data set.

Here, I'm demonstrating two application of index and match functions on a 'toy' dataset with different layouts. Let's see how it works.

First things first, I always prefer to name cell ranges that will be used in formulas, instead of just highlighting the range for two main reasons:

- It's more convient and  makes syntax easier to read
- Just looks cleaner!

So how does it work?

- Identify lookup criteria, here I'm using first/last name because of duplicated first name

- Name cell ranges of lookup criteria in the main table (optional)

- Write the syntax: 
  - Index(where to look(main table), match(look up criteria(sub table), location of look up criteria(main table), type of match),what to look up for)





You can generate random(toy) dataset from here https://www.mockaroo.com










