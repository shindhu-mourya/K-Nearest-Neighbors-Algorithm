# K-Nearest-Neighbors-Algorithm
K-Nearest Neighbors Algorithm is performed on DonorsChoose Data Sets
# Note:
Any help needed to execute the code or understanding the code, please send me message. I will soon upload the input data and expected output data. More updates coming soon. Meanwhile Please look at the code.

# How to convert categorical feature to numerical feature:
(I) Simply convert the string to number by either some ranking or order. if you have set of strings, give a number to each other. Not a good solution. As this way, number will not take any sense.
(ii) One hot encoding. - Very popular. one-hot encoding, I say I have set of 5 colors, it will replace one feature to 5 features of binary vector of a size of number of distinct colors. It is a sparse and large vector. Hair color is a categorical feature as it has multiple category. If I need to figure out from Country, height of the person, I can do that. Example 200 countries, I can create matrix of 200 features. Each column will have mean of the height of the people per country. so, I can replace the feature of country with avg height. so, I introduce new 200 features by one country feature. so, I convert categorical feature to a set of numeric features. (iii) BoW - Bag of words. - Another popular. And very similar to one-hot encoding.
(iv) Using Domain Knowledge: Given a country, replace food taste or food quality with number.
(iv) Mean replacement.
