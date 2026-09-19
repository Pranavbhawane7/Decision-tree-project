Drug Classification using Decision Trees
Project Overview  
This project applies Decision Tree Classification to predict drug types for patients based on medical attributes. It demonstrates end-to-end data preprocessing, model building, and interpretation using Python and scikit-learn. The model is designed to be interpretable, allowing clear extraction of decision rules for each drug class.

----

Objective  
To build a classification model that explains how sodium-to-potassium ratio (Na/K), blood pressure (BP), age, and cholesterol level influence drug prescriptions, and to evaluate its accuracy using standard metrics.

----

Dataset  
The dataset contains patient medical attributes, including:

Sodium-to-potassium ratio (Na/K)

Blood pressure (BP: High, Normal, Low)

Age

Cholesterol level (High/Normal)

Target variable: Drug type (Drug A, Drug B, Drug C, Drug X, Drug Y)

----

Tech Stack

Python (data analysis & modeling)

Pandas & NumPy (data wrangling)

Matplotlib & Seaborn (visualization)

Scikit-learn (decision tree model building & evaluation)

----

Results & Insights  
The decision tree produced clear, interpretable rules for each drug class:

Drug Y: 
𝑁
𝑎
/
𝐾
>
14.627

Drug A: 
𝑁
𝑎
/
𝐾
≤
14.627
,
𝐵
𝑃
=
𝐻
𝑖
𝑔
ℎ
,
𝐴
𝑔
𝑒
≤
50.5

Drug B: 
𝑁
𝑎
/
𝐾
≤
14.627
,
𝐵
𝑃
=
𝐻
𝑖
𝑔
ℎ
,
𝐴
𝑔
𝑒
>
50.5

Drug C: 
𝑁
𝑎
/
𝐾
≤
14.627
,
𝐵
𝑃
=
𝐿
𝑜
𝑤
,
𝐶
ℎ
𝑜
𝑙
𝑒
𝑠
𝑡
𝑒
𝑟
𝑜
𝑙
≤
𝐻
𝑖
𝑔
ℎ

Drug X: 
𝑁
𝑎
/
𝐾
≤
14.627
,
𝐵
𝑃
=
𝑁
𝑜
𝑟
𝑚
𝑎
𝑙
,
𝐶
ℎ
𝑜
𝑙
𝑒
𝑠
𝑡
𝑒
𝑟
𝑜
𝑙
=
𝐻
𝑖
𝑔
ℎ

These rules highlight how patient attributes directly influence drug recommendations. The model’s interpretability makes it suitable for educational purposes and healthcare decision support, as clinicians can trace exactly why a particular drug is suggested.
