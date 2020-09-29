# Diamond_Clarity---Classification

Date created
12/18/2017

Project Title
Classifying Diamond Clarity

Description
Using R Classify diamond clarity based on multiple features.

Files used
diamonds.csv

Project Overview
Natural diamonds are result of carbon exposed to tremendous heat and pressure deep in the earth. This process can result in variety of internal characteristics called “inclusions” and external characteristics called “blemishes”. Evaluating the diamond clarity involves determining the number, size, relief, nature and position of these characteristics, as well as how these effect the appearance of this stone. While no diamond is perfectly pure, the closer it comes, higher the value.
Many inclusions and blemishes are too tiny to be seen by anyone other than a trained grader. To naked eye VS1 and SI2 may exactly look the same, but they quite different in terms of quality. Expensive equipment and trained professionals are required to grade the clarity of the diamond. Due to this the buyer is dependent on the certificate given by the trader and no other means of verifying the diamond clarity. This leads to buyer getting duped or accidently got sold the wrong clarity diamond. This model tries to classify the clarity of the diamond based on other features of the diamond, so the buyer can get a sense of confidence that he is being sold the correct diamond. This model classifies the groups of clarity of the diamond and but does not include several level within each group.

The data set contains 10 variables, 3-categorical variables (Cut, Color and clarity) and 7 –continuous variables (Price, Carat, X, Y, Z, Depth and Table). Since the measurement of each continuous variable is a different measurement and different scale, data normalization is required for any methods which uses distance based algorithms. Since the scope of the project to classify the Clarity of diamond based on other features, Clarity is our response variable and rest of the variables are our independent variables.
Below is the explanation of each variable in the data set:
•	Price: price in US dollars (\$326--\$18,823), Carat:  weight of the diamond (0.2--5.01), Cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal), Color:  diamond color, from J (worst) to D (best)
•	Clarity: measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best)), X:  length in mm (0--10.74), Y:  width in mm (0--58.9), Z: depth in mm (0--31.8), Depth:  total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79) and Table: width of top of diamond relative to widest point (43--95)

