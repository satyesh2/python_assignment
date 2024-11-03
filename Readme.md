the task is to write a Python-program that uses training data to choose the four ideal functions which are the best fit out of the fifty provided (C) *.
i) Afterwards, the program must use the test data provided (B) to determine for each and every x-y-pair of values whether or not they can be assigned to the four chosen ideal functions**; if so, the program also needs to execute the mapping and save it together with the deviation at hand
ii) All data must be visualized logically
iii) Where possible, create/ compile suitable unit-test
* The criterion for choosing the ideal functions for the training function is how they minimize the sum of all y-deviations squared (Least-Square) ** The criterion for mapping the individual test case to the four ideal functions is that the existing maximum deviation of the calculated regression does not exceed the largest deviation between training dataset (A) and the ideal function (C) chosen for it by more than factor sqrt(2)
