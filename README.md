👥 College Tech Community
College Tech Community is a Python-based data project that simulates a social network for a college’s tech community. It explores friend recommendations and page suggestions based on user interests and mutual connections using JSON user data.

📍 Inspired by social platforms like Facebook and LinkedIn — built for learning graph traversal, recommendation systems, and network analysis.

🗂️ Project Structure
bash
Copy
Edit
├── CODmain.ipynb             # Main notebook for user-based recommendations
├── CODmain2.ipynb            # Extended version with improved logic
├── PeopleYouMayKnow.ipynb    # Suggests friends based on mutual connections
├── PagesYouMightLike.ipynb   # Recommends pages based on friends' interests
├── introduction.ipynb        # Project introduction and overview
├── 02_Data_cleaning.ipynb    # Notebook for cleaning and validating data
├── cleaned_data2.json        # Cleaned dataset
├── data.json                 # Primary dataset
├── data2.json                # Dataset with deliberate inconsistencies (for testing)
├── massive.json              # Large dataset (30 users) for scalability testing
🔍 Key Features
✅ People You May Know

Suggests new friends using mutual connections

Uses basic graph traversal logic

Mimics real “People You May Know” features

✅ Pages You Might Like

Recommends pages liked by your friends but not by you

Shows how social recommendations can boost engagement

📊 Datasets
Each JSON file contains:

users: ID, name, list of friends, liked pages

pages: Page ID and name (e.g. Python Developers, AI & ML Community)

massive.json mimics a larger social network (30 users) to test scalability.

📌 How to Run
1️⃣ Clone this repo

bash
Copy
Edit
git clone https://github.com/yourusername/college-tech-community.git
cd college-tech-community
2️⃣ Open notebooks (.ipynb) in Jupyter Notebook, VSCode, or Google Colab

3️⃣ Load a dataset — choose data.json, cleaned_data2.json, or massive.json

4️⃣ Run the notebooks and explore how friend and page recommendations work!

🧠 Skills Demonstrated
JSON data parsing

Graph-based recommendation logic

Simple traversal algorithms

Data cleaning and validation

Modular notebook design

🎯 Ideal For
Beginners learning Python and data structures

Students exploring graph networks and recommendations

Developers curious about social media algorithms

Small college or bootcamp projects

🛠️ Built With
Python 3.8+

Jupyter Notebooks

JSON

pandas (optional, for data analysis)
