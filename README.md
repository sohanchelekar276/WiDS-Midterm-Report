# WiDS-Midterm-Report

## Assignment 1
I will document my learning procedure and the solutions for the first assignment and the first week. This assignment majorly focused on the first 2 pillars of DS: numerical computation by Numpy and data manipulation using Pandas. On top of that, we used the Matplotlib to visualise the trends in video game sales.



**Part 1: With Numpy**

The first part of the assignment helped me understand how to handle multidimensional arrays effectively without using redundant Python loops for each thing.

Key Concepts I learned:
* Array Initialisation: I learned to use np.random.randint to generate datasets for testing
* Slicing and Indexing: Accessing elements using [row,col] became intuitive too.
* Statistical Analysis: I learnt that axis= 1 performs calculations horizontally across columns while axis=0 works vertically
* Boolean Masking: Instead of writing if statements, I understood how to use boolean masking (arr[arr>mean]) which is much faster and cleaner to write

The most difficult part at that ime was surely the numpy_spiral_order function, I implemented a simulation approach using four boundary pointers(top, bottom, left, right). I had multiple errors due to careless handling of indices, so I had to spend time in ensuring that no element was visited twice.


**Part 2: With Pandas**

The second part involved analysing a real world dataset. This showed how data can be turned into insights we can actually take action on

Key Concepts I learned:
* Data Manipulation: I learned that we need to add features in datasets, for example, dataset didnt have a "Total Global Sales" column, so I made that.
* Filtering and String Operations: To analyse the GTA franchise, I used str.contains which was powerful as it gave me every version of the game regardless of the specific title formatting. I also performed grouped calculations, summing specific regional sales for these rows.

**Part 3: Data Visualisation**

Using Matplotlib, I converted the numerical tables into visual charts to make trends easier to spot.
* Bar Charts: By grouping by Genre, I visualised which types of games are most popular globally. The bar chart clearly showed that Actions and Sports genres dominate the market.
* Pie Charts: I created pie chart to visualise the regional market share for GTA. This showed how less the market share in Japan was than North America and Europe.


