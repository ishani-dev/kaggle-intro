# Kaggle Workshop Lab Guide 

**Developed by Ishani Udeshika**  
[LinkedIn Profile](https://www.linkedin.com/in/ishaniu/)

---

##  Overview
This lab guide is designed to help participants get hands-on experience with Kaggle. It walks through setting up a Kaggle account, exploring the platform, working with notebooks, and participating in competitions. Each task below is structured with detailed steps to help you follow along independently.
<br>

<img width="1390" alt="Screenshot 2025-05-25 at 07 02 07" src="https://github.com/user-attachments/assets/56e6490d-ae2f-4079-af41-cca06e2855c2" />


##  Task 1: Create a Kaggle Account
1. Go to [https://www.kaggle.com](https://www.kaggle.com)
2. Click **"Sign Up"**.
3. Sign up using your **Google account** or any valid **email address**.
4. After signing in:
   - Add a **name** (real or display).
   - Optionally update your **bio**, **profile picture**, **location**, and **interests**.

---

##  Task 2: Explore the Kaggle Interface
Once signed in:
1. Use the **top navigation bar** to explore the following tabs:
   - **Competitions** – Ongoing challenges you can join.
   - **Datasets** – Public datasets for analysis and modeling.
   - **Code (Notebooks)** – Community shared notebooks and your own.
   - **Learn** – Mini courses on data science and ML.
   - **Discussion** – Forum for questions, tips, and collaboration.

<img width="1462" alt="Screenshot 2025-05-25 at 07 10 27" src="https://github.com/user-attachments/assets/c8d6b9e6-0eda-463d-8805-f79160482605" />

---

##  Task 3: Create Your First Notebook
1. Option 1: Go to **Create > Notebook** from top right corner. <br><br> <img width="274" alt="Screenshot 2025-05-25 at 07 14 30" src="https://github.com/user-attachments/assets/e3b7f01d-cb52-4431-ae60-ef6f56a96945" />
2. Option 2: Navigate to the **Code** tab and click **"New Notebook"**. <br><br><img width="801" alt="Screenshot 2025-05-25 at 07 21 04" src="https://github.com/user-attachments/assets/a92323ec-1706-4b12-8e22-9883520ec7e6" />

3. Choose **Python** as the language.<br><br><img width="357" alt="Screenshot 2025-05-25 at 07 25 27" src="https://github.com/user-attachments/assets/8b443d32-d740-4943-b62d-92df647f71dc" />

4. On the right panel, click **"Add Data"**, and search for:

   > Titanic - Machine Learning from Disaster
5. Add the dataset to your notebook.

### Sample Starter Code:
```python
import pandas as pd

df = pd.read_csv("/kaggle/input/titanic/train.csv")

# Basic EDA
print(df.head())
print(df.info())
print(df.isnull().sum())
print(df.describe())
print(df['Survived'].value_counts(normalize=True))
print(df['Sex'].value_counts())

```
---

##  Task 4: Explore an Existing Notebook
1. Go to [Titanic Competition Page](https://www.kaggle.com/competitions/titanic).
2. Scroll to the **"Code"** section.
3. Open a **highly upvoted notebook**.
4. Observe how the notebook:
   - Introduces the problem.
   - Visualizes data (e.g., charts, graphs).
   - Builds and evaluates models.
   - Describes conclusions.

---

##  Task 5: Join a Competition
1. Go to the [Titanic Competition](https://www.kaggle.com/competitions/titanic).
2. Click **"Join Competition"** (agree to terms).
3. Read the **problem description** and **evaluation metric**.
4. Download the dataset and unzip if needed.

---

##  Task 6: Submit a Prediction
1. In your Titanic notebook, create a basic prediction model or use the sample submission format.
2. Generate a `.csv` file (e.g., `submission.csv`) with predictions.
3. Go back to the Titanic competition page → click **"Submit Predictions"**.
4. Upload your file and wait for it to appear on the **Leaderboard**.

---

##  Task 7: Host a Competition (For Future Exploration)
1. Visit: [https://www.kaggle.com/competitions-host](https://www.kaggle.com/competitions-host)
2. Kaggle allows organizations to host competitions with various options.
3. Choose your competition type (Featured, Research, Community).
4. You need to define:
   - A **problem statement**
   - A **dataset**
   - An **evaluation metric**

---

👏 **Congratulations** on completing the hands-on Kaggle walkthrough!  
Feel free to explore further and share your progress on LinkedIn 🚀
