# Topsis_102003759
Topsis Package
https://pypi.org/project/102003759/

 
# What is TOPSIS?
Technique for Order Preference by Similarity to Ideal Solution (TOPSIS) came in the 1980s as a multi-criteria-based decision-making (MCDM) method. TOPSIS chooses the alternative of shortest the Euclidean distance from the ideal solution and greatest distance from the negative ideal solution.

# How to Install this Package?
pip install Topsis-Sushant-102003759

# How to Run this Package?
topsis <inputFileName> <weights> <impacts> <resultFileName>

Eg. topsis /Users/Sushant/Desktop/102003759-data.csv "1,1,1,1,1" "+,+,-,+,+" /Users/Sushant/Desktop/result.csv

# Constraints Applied
Number of parameters should be correct i.e. 5.
Print error message if input file doesn't exist.
The impacts and weights should be comma separated.
Impacts should only have +ve or -ve symbols.
Number of columns in the input csv file should be more or equal to 3.
The 2nd to last columns should be in numeric data type.
Number of weights, impacts and columns should be equal.
# Input File

![image](https://github.com/SushantVij/Topsis_102003759/assets/116457738/80d33d8f-10d7-43a4-bc3d-1209e7100568)

Output File

![image](https://github.com/SushantVij/Topsis_102003759/assets/116457738/af4543cb-944d-4393-bebd-99e4a7672335)


License
MIT


