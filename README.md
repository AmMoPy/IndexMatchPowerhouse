## About

Index and Match: lookup powerhouse.

While you may be familiar with popular lookup functions in excel (V/Hlookup), you are probably not much acquainted with its beefed up version Index and Match. This is not a debate about which function is better, rather a simplification of what might seems complex at the first glance.

Why use Index and Match:

- Flexibility, you lookup data no matter how columns are positioned.
- Way faster if you are working with large data set.

Here, I'm demonstrating two application of index and match functions on a ['toy'](https://www.mockaroo.com) dataset with different layouts. Let's see how it works.

First things first, I always prefer to name cell ranges that will be used in formulas, instead of just highlighting the range for two main reasons:

- It's more convenient and makes syntax easier to read
- Just looks cleaner!

So how does it work?

- Identify lookup criteria, here I'm using first/last name because of duplicated first name

- Name cell ranges of lookup criteria in the main table (optional)

- Write the syntax: 
  - Vertical lookup : Index(where to look(main table), match(look up criteria(sub table), location of look up criteria(main table), type of match),what to look for)
  - Horizontal lookup : Index(what to look for(main table), match(look up criteria(sub table), location of look up criteria(main table), type of match))
 
- Apply the function: Just Hit enter and you will get a nasty error!. Array like functions can't be activated buy just using Enter, rather, Ctrl + Shift + Enter. Remember that each time you edit the function you need to apply it using this combo.

*If you are wondering what &"|"& in the syntax means, it is just telling excel to search for both first and last name as a unique criteria.*

You can combine this powerhouse with other functions to be a real excel wizard. Try it, you will like it.
