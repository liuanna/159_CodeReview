#Results from coding review

After reviewing all three function, extract, asum, and mean, we found that
the function becomes slower and harder for interpretation when we use
map,zip,reduce etc buitin functions more often. But such fuctions are brief.
After calculating the runtime of functions, we found that wdSolution's extract
and asum gives fastest speed because they avoid for loop and builtin functions.
