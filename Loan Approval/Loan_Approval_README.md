𝐋𝐨𝐚𝐧 𝐀𝐩𝐩𝐫𝐨𝐯𝐚𝐥 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧 – 𝐌𝐋 𝐏𝐫𝐨𝐣𝐞𝐜𝐭

This project is part of my Elevvo Pathways Machine Learning Internship Tasks. The aim is to analyze a loan approval dataset, clean and process the data, and build machine learning models to predict whether a loan application will be approved or rejected.

📌 𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐖𝐨𝐫𝐤𝐟𝐥𝐨𝐰

𝟏. 𝐃𝐚𝐭𝐚 𝐋𝐨𝐚𝐝𝐢𝐧𝐠 & 𝐄𝐱𝐩𝐥𝐨𝐫𝐚𝐭𝐢𝐨𝐧
-> Loaded dataset using pandas.
-> Checked data shape, information, and summary statistics.
-> Verified missing values and duplicates.

𝟐. 𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠 & 𝐏𝐫𝐞𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠
-> Replaced invalid values (-100000) with NaN.
-> Filled missing values using the median.
-> Encoded categorical variables using one-hot encoding.

𝟑. 𝐎𝐮𝐭𝐥𝐢𝐞𝐫 𝐃𝐞𝐭𝐞𝐜𝐭𝐢𝐨𝐧 & 𝐓𝐫𝐚𝐧𝐬𝐟𝐨𝐫𝐦𝐚𝐭𝐢𝐨𝐧
-> Identified outliers with the IQR method.
-> Applied Box-Cox transformation to normalize asset-related features.
-> Used histograms and boxplots for visualization.

𝟒. 𝐄𝐱𝐩𝐥𝐨𝐫𝐚𝐭𝐨𝐫𝐲 𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 (𝐄𝐃𝐀)
-> Histograms for numerical features.
-> Count plots for categorical features (education, self_employed, loan_status).
-> Correlation heatmap for numerical features.

𝟓. 𝐌𝐨𝐝𝐞𝐥 𝐁𝐮𝐢𝐥𝐝𝐢𝐧𝐠
-> Logistic Regression – trained and tested on the dataset, evaluated with classification report.
-> Decision Tree Classifier – trained and tested on the dataset, also evaluated with classification report.
-> Cross-validation performed for accuracy checking.

⚙️ 𝐓𝐨𝐨𝐥𝐬 & 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬
-> Python (Pandas, NumPy)
-> Seaborn & Matplotlib (Visualization)
-> SciPy (Box-Cox Transformation)
-> Scikit-learn (Preprocessing, Models, Metrics)
