# Titanic Survival Prediction Project

---

## **Projeck ki Jankari (Project Overview)**

Is project ka maqsad **Titanic disaster** ke data ka istemal kar ke yeh predict karna hai ke kaun se musafir (passengers) zinda bache (survived) aur kaun nahi. Maine is mushkil problem ko solve karne ke liye Machine Learning ke concepts aur techniques ka end-to-end (shuru se aakhir tak) istemal kiya hai.

Is project ke zariye, maine ek **classification model** banaya hai jo musafiron ke alag-alag features (jaise ke umar, gender, ticket class, waghaira) par depend karta hai.

---

## **Seekhi Hui Techniques aur Maharat (Skills Demonstrated)**

Yeh project dikhata hai ke mujhe in Machine Learning techniques par acchi maharat hai:

### **1. Data Preprocessing & Cleaning**
* **Missing Values:** Maine data mein maujood khaali values (missing values) ko samajhdaari se deal kiya hai. Jaise ke, `Age` aur `Embarked` columns mein missing values ko sahi tareeqe se bhara.
* **Categorical Data Handling:** Text-based data (jaise ke `Sex`, `Embarked`) ko machine learning models ke liye taiyaar kiya, jiske liye maine **One-Hot Encoding** jaisi techniques ka istemal kiya.

### **2. Feature Engineering**
* Maine maujood data se naye aur zyada informational features banaye hain.
    * **`Family_Size`:** Is feature se pata chalta hai ke musafir akela safar kar raha tha ya apne parivar ke saath.
    * **`Title`:** Musafir ke naam se unka title nikaal kar ek naya feature banaya, jisse unki social status ka pata chalta hai.

### **3. Model Training**
* Maine do alag-alag classification models ko train kiya hai taaki unki performance ka muqabla (comparison) kiya ja sake:
    * **Logistic Regression**
    * **Random Forest**

### **4. Model Evaluation & Comparison**
* Sirf accuracy par depend karne ke bajaye, maine models ki performance ko aur bhi zaroori metrics se jaancha hai, jisse unki asli taqat ka pata chalta hai:
    * **Accuracy Score**
    * **Precision**
    * **Recall**
    * **F1-Score**
* Analysis ke baad, **Random Forest** model ne sabse behtar performance di, jisse yeh mera final model ban gaya.

---

## **Repository Structure**
* `Titanic - Machine Learning from Disaster.ipynb`: Is Jupyter Notebook file mein poora code hai jismein data analysis, cleaning, feature engineering, model training, aur evaluation shamil hai.
* `train.csv`: Kaggle se liya gaya training data.
* `test.csv`: Kaggle se liya gaya test data (is project mein abhi tak predictions nahi kiye gaye hain).

---

## **Istemal Ki Gayi Libraries (Technologies Used)**
* `Python`
* `Pandas`
* `Numpy`
* `Scikit-learn`
* `Matplotlib`
* `Seaborn`

---

**Agar aapko is project ke baare mein koi aur jankari chahiye ya koi sawal hai, to aap mujhse zaroor contact kar sakte hain.**
