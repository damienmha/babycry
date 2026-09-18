# Background

The goal of this project was to explore if human babies' crying sounds can give information about their underlying causes. Research into the emotions that cause babies to cry, such as tiredness, hunger, and discomfort are key in communication and intervention with babies' issues, since babies cannot speak.

Completed in collaboration with other students, this project supplements previous research conducted in a UCLA Neuropsychology Lab.  From prior research and experimental trials, we were provided data with acoustic features of babies' cries. Each cry was recorded as a certain 'type' due to its underlying cause, including hungry, belly pain, tired, discomfort and burping. The data also included junk noise in the form of adult humans talking

# Literature Review

We reviewed a total of seven research studies that previously investigated classifying baby cry causes. The majority of these studies used convolution neural networks to classify cry types. It is worth noting that some of these studies did not acknowledge skewness of data and did not report cross-valiation

# Methodology

After performing exploratory data analysis and noting a class imbalance (cries due to hunger had a disproportionate number of observations in the data), we conducted principle component analysis (PCA) to focus on the variables most contributing to cry outcomes. We then trained four machine learning models to classify all five cry types and noted prediction accuracy. Due to the imbalance of hunger-related cries, we also split the data into two classes, 'hunger' and 'other' and noted that accuarcy as well


































