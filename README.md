# Regular-Expressions-to-Non-Deterministic-Finite-Automata
For this task I need to implement Thompson’s construction for converting a regular expres- sion to an equivalent NFA.
Using java I should implement a class constructor RegExToNfa and a method toString.
RegExToNfa takes one parameter which is a string of the form A#R. A is a string representation of an alphabet Σ, a semicolon-separated sequence of alphabetically sorted symbols, and R is a postfix regular expression over Σ. RegExToNfa constructs the NFA to R as per Thompson’s construction.
toString returns a string describing the NFA resulting from Thompson’s construction. A string describing the NFA resulting from Thompson’s construction is of the form Q#A#T #I #F .
