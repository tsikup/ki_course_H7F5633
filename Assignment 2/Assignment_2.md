# "Assignment 2 - Dongchen Assignment Review by Nikos Tsiknakis"

**1.1 Is the assignment well structured?**

The assignment is well structured with a clear separation of the tasks. Additional comments could be added to long piped commands to make them more readable, but the code is easy to follow anyway.

**1.2 Is the formatting appropriate?**

The formatting is appropriate with the use of markdown headers and code blocks.

**2.1 Are all the tasks addressed?**

All required tasks are addressed.

**3.a Are the given answers correct to the best of your understanding?**

- I believe Task 4.6 is not correct, as the question asks for the number of ordered combinations. `ABC` is different than `BAC`, but `choose(100, 3)` selects the unordered combinations. I believe the correct answer is `factorial(100) / factorial(100 - 3)`.

- The answer for Task 2.b gives a different figure than I had given. I believe that geom_bar should be used instead of geom_histogram, as the data is already aggregated (with histogram one would show counts of counts!).

- The proteins data results miss a histogram graph, which would show extreme outliers, indicating the use of log transform before further analysis.

Otherwise the answers are correct.

**4.a Do the provided analyses address the questions asked?**

The analyses address the questions asked.

**4.b Are the provided insights conclusive given the conducted analyses?**

The results' of the protein dataset analysis could have been augmented with additional comments for conclusive insights. Otherwise the provided insights are conclusive.

**5.a Is the provided R code well documented?**

The R code is generally well documented and easy to follow; but I would have liked additional comments for long piped commands to make them more readable.
