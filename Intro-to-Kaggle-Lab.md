# Introduction to Kaggle Workshop Lab Guide 

**Developed by [Ishani Udeshika](https://www.linkedin.com/in/ishaniu/)**


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
5. Add the dataset to your notebook.<br><br><img width="846" alt="Screenshot 2025-05-25 at 07 41 45" src="https://github.com/user-attachments/assets/5db0c834-4a10-4808-b526-1934767a49d4" />

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
1. Go to [Titanic Competition Page](https://www.kaggle.com/competitions/titanic). <br><br> <img width="1447" alt="Screenshot 2025-05-25 at 10 14 18" src="https://github.com/user-attachments/assets/997dba11-4264-4a8c-8bf8-cc4a4045ccf7" />

2. Scroll to the **"Code"** section.
3. Open a **highly upvoted notebook**.<br><br><img width="1190" alt="Screenshot 2025-05-25 at 10 12 19" src="https://github.com/user-attachments/assets/3f344938-741b-4410-8578-ce2929f5a65e" />


4. Observe how the notebook:
   - Introduces the problem.
   - Visualizes data (e.g., charts, graphs).
   - Builds and evaluates models.
   - Describes conclusions.


---

##  Task 5: Join a Competition
1. Go to the [Titanic Competition](https://www.kaggle.com/competitions/titanic).<br><br> <img width="1178" alt="Screenshot 2025-05-25 at 10 15 51" src="https://github.com/user-attachments/assets/2d958605-8197-4e9a-a7ea-1647c9d1edfe" />
2. Click **"Join Competition"** (agree to terms).
3. Read the **problem description** and **evaluation metric**.
4. Download the dataset and unzip if needed.

---

##  Task 6: Submit a Prediction
1. In your Titanic notebook, create a basic prediction model or use the sample submission format.
2. Generate a `.csv` file (e.g., `submission.csv`) with predictions.
3. Go back to the Titanic competition page → click **"Submit Predictions"**.<br><br><img width="772" alt="Screenshot 2025-05-25 at 10 23 28" src="https://github.com/user-attachments/assets/5a7c6e1a-bbbb-4dd0-b8d6-23e932558815" />

4. Upload your file and wait for it to appear on the **Leaderboard**.<br><br><img width="1157" alt="Screenshot 2025-05-25 at 09 33 54" src="https://github.com/user-attachments/assets/b6a78d04-081b-45b8-ad14-6f71b217795b" />


---

##  Task 7: Host a Competition (For Future Exploration)
1. Visit: [https://www.kaggle.com/competitions-host](https://www.kaggle.com/competitions-host)<br><br>

2. Kaggle allows organizations to host competitions with various options(Featured, Research, Community).<br><br><img width="600" alt="Screenshot 2025-05-25 at 10 28 56" src="https://github.com/user-attachments/assets/f4a7165c-b3ff-42ce-bed5-b5da412b3196" />
3. Choose your competition type.<br><br><img width="806" alt="Screenshot 2025-05-25 at 10 30 49" src="https://github.com/user-attachments/assets/2a6aef4f-2c12-4638-af0a-fc28e3535bd3" />
4. You need to define:
   - A **problem statement**
   - A **dataset**
   - An **evaluation metric**
<br><br> <img width="1463" alt="Screenshot 2025-05-25 at 10 34 38" src="https://github.com/user-attachments/assets/690173ce-cc2c-462f-8556-6700301a666f" />

---

👏 **Congratulations** on completing the hands-on Kaggle walkthrough!  

