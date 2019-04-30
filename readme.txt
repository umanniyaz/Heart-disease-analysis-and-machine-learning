Data Set Information:

This dataset contains 14 attributes.Here the dataset is based on binary classification.
I use Logistic Regression algorithm predict the accuracy of the model and f1 scores.First what i do is data preprocessing and cleaning.First filling in missing values with tool from sklearn library by imputer function using median I also have pasted dummy values to make data in numeric.And scaling data for Principle component analysis algorithm to reduce dimensions or reduce columns.
and then train test split to tarin and tset the accuracy model.Previously improving the accuracy of model from 82 and 88 to 92 percent. 

Attribute Information:

Only 14 attributes used: 1.  (age) 2.  (sex) 3.  (cp) 4.  (trestbps) 5.  (chol) 6.  (fbs) 7.  (restecg) 8. (thalach) 9. (exang) 10.  (oldpeak) 11.  (slope) 12.  (ca) 13. (thal) 14.  (target) (the predicted attribute)


Columns
age age in years
sex(1 = male; 0 = female)
cpchest pain type
trestbpsresting blood pressure (in mm Hg on admission to the hospital)
cholserum cholestoral in mg/dl
fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
restecgresting electrocardiographic results
thalachmaximum heart rate achieved
exangexercise induced angina (1 = yes; 0 = no)
oldpeakST depression induced by exercise relative to rest
slopethe slope of the peak exercise ST segment
canumber of major vessels (0-3) colored by flourosopy
thal3 = normal; 6 = fixed defect; 7 = reversable defect
target1 or 0