# ML Model For Heart Disease Prediction

(data source: https://www.kaggle.com/ronitf/heart-disease-uci)

When the blood supply to the heart is cut off, a heart attack develops. The most common cause of a blockage is a buildup of fat, cholesterol, and other chemicals in the arteries that supply the heart, forming a plaque (coronary arteries). 

A plaque can break and generate a clot, obstructing blood flow. Parts of the heart muscle can be damaged or destroyed if blood flow is disrupted.

This dataset contains patient medical data that indicates whether a person's risk of having a heart attack is low or high. Explore the dataset utilising the information and classifying the target variable using several Machine Learning models to determine which approach is best for this dataset is the main objective of this study.

The 13 variables identified in the dataset are given as follows

1. age	age
2. sex	sex
3. cp	chest pain type (4 values)
4. trestbps	resting blood pressure
5. chol	serum cholestoral in mg/dl
6. fbs	fasting blood sugar > 120 mg/dl
7. restecg	resting electrocardiographic results (values 0,1,2)
8. thalach	maximum heart rate achieved
9. exang	exercise induced angina
10. oldpeak	oldpeak = ST depression induced by exercise relative to rest
11. slope	the slope of the peak exercise ST segment
12. ca	number of major vessels (0-3) colored by flourosopy
13. thal	thal: 3 = normal; 6 = fixed defect; 7 = reversable defect


The following list explains what each variable means and what kind of data (float or category) it should contain:

•	Age (Float) : 
The most major risk factor for developing cardiovascular or heart disorders is age, with the risk about doubling every decade of life. In adolescence, fatty streaks in the coronary arteries might occur. 82 percent of patients who die of coronary heart disease are 65 or older, according to estimates. At the same time, after the age of 55, the risk of stroke doubles every decade.

•	sex :
0 indicates a female 
1 indicates a guy 

Men have a higher risk of heart disease than women before menopause. It has been claimed that once a woman has through menopause, her risk is similar to that of a man, although more recent data from the WHO and UN contradicts this. A female with diabetes is more likely than a male with diabetes to get heart disease.

•	cp: chest pain

(Category)
1 = typical angina
2 = atypical angina
3 = non-anginal pain
4 = asymptomatic

Angina is chest pain or discomfort caused by a lack of oxygen-rich blood to your heart muscle. In your chest, you may feel pressure or a squeezing sensation. In addition to your shoulders, arms, neck, mouth, and back, you may experience discomfort in your shoulders, arms, neck, jaw, or back. Angina pain might mimic the symptoms of dyspepsia.

•	restbp: resting blood pressure (in mm Hg) (Float)

High blood pressure can damage the arteries that supply your heart over time. High blood pressure combined with other health problems, such as obesity, high cholesterol, or diabetes, raises your risk even more.

•	chol: serum cholesterol in mg/dl  (Float)

Serum Cholesterol: A high amount of low-density lipoprotein (LDL) cholesterol (the "bad" cholesterol) is the most common cause of artery narrowing. A high amount of triglycerides, a type of blood fat linked to your food, increases your chances of having a heart attack. A high amount of high-density lipoprotein (HDL) cholesterol (the "good"), on the other hand, reduces your chance of a heart attack.

•	fbs: fasting blood sugar

(Category)
0 = >=120 mg/dl
1 = <120 mg/dl
When your pancreas does not produce enough insulin or your body does not respond to insulin adequately, your blood sugar levels rise, increasing your risk of a heart attack.

•	restecg: resting electrocardiographic results

(Category)
1 = normal
2 = having ST-T wave abnormality
3 = showing probable or definite left ventricular hypertrophy

The USPSTF concludes with intermediate certainty that the potential hazards of screening with resting or exercise ECG equal or outweigh the potential benefits for those at low risk of cardiovascular disease. Current evidence is insufficient to assess the balance of benefits and harms of screening for persons at intermediate to high risk.

•	thalach: maximum heart rate achieved (Float)

The increase in cardiovascular risk related with heart rate acceleration was comparable to the risk associated with high blood pressure. An increase in heart rate of 10 beats per minute has been linked to a 20% increase in the risk of cardiac death, which is equivalent to the rise in risk seen with a 10 mm Hg increase in systolic blood pressure.

•	exang: exercise induced angina

(Category)
0 = no
1 = yes

Angina pain or discomfort is usually tight, gripping, or squeezing, and it can range from mild to severe. Angina normally affects the centre of your chest, but it can also affect one or both shoulders, as well as your back, neck, jaw, or arm. It's even palpable in your palms. Angina comes in a variety of forms- Angina Pectoris
o	Stable Angina 
o	Unstable Angina 
o	Variant (Prinzmetal) Angina 
o	Angina Microvascular

•	oldpeak: ST depression induced by exercise relative to rest (Float)

When the ST-segment depression is less than 1 mm at 60–80 ms following the J point on a treadmill ECG stress test, it is considered abnormal. Exercise ECGs with up-sloped ST-segment depressions are commonly referred to as a "equivocal" test. In general, horizontal or down-sloping ST-segment depression at a lesser workload (measured in METs) or heart rate predicts a poor prognosis and a greater risk of multi-vessel disease. The duration of ST-segment depression is particularly crucial, as a positive treadmill ECG stress test is associated with a protracted recovery after peak stress.

•	slope: the slope of the peak exercise ST segment

(Category)
1 = upsloping
2 = flat
3 = downsloping

•	ca: The number of major blood vessels(0-3) supplying blood to heart blocked (Float)
•	thal: thalium heart scan
(Category)
3 = normal (no cold spots)
6 = fixed defect (cold spots during rest and exercise)
7 = reversible defect (when cold spots only appear during exercise)

•	target (predicted attribute): diagnosis of heart disease (angiographic disease status)

Value 0: < 50% diameter narrowing 

Value 1: > 50% diameter narrowing


The Project explores 4 ML Models i.e to draw conclusions for predictions of Heart disease based on 13 factors 
1. Logistic Regression
2. Random Forest
3. K Nearest Neighbors
4. SVC 


