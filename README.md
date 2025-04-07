# **Level_Up** – Gamify Your Life! 🎮  

Hello! I’m **Satou** (an alias).  
This README will help you understand what this repository does and how to set it up.  

## **What Does It Do?**  
**Level_Up** is a life-gamification app inspired by the anime *Solo Leveling*. Unlike the original, this system allows **multiple users** to level up together by completing tasks and earning XP (experience points).  

### **Key Features:**  
✅ **Leveling System** – Earn XP by doing "Good Work" and daily tasks.  
✅ **Leaderboard** – Compete with others and show off your progress.  
✅ **Bank & XP Transfers** – Send XP to other users.  
✅ **Community Chat & DMs** – Communicate with other players.  
✅ **Shop** – Spend XP on items (managed by superusers).  

### **Superusers vs. Normal Users**  
- **Superusers** have admin privileges:  
  - Manage users’ XP.  
  - Assign extra tasks.  
  - Set up shop items.  
  - No daily task limits.  
- **Normal users** follow standard progression rules.  

---

## **How to Set Up?**  

### **Prerequisites:**  
- **Python** (Download: [python.org/downloads](https://www.python.org/downloads))  
- **Git** (Download: [git-scm.com](https://git-scm.com/downloads))  

### **Installation Steps:**  

1. **Install Django**  
   ```sh
   python -m pip install django
   ```
2. **Clone The Repository**
  ```sh
   git clone https://github.com/ManavBisen/Level_Up
  ```
3. **Navigate to the Project Directory**
  ```sh
   cd Level_Up
  ```
4. **Install Dependencies**
  ```sh
   pip install -r requirements.txt
  ```
5. **Run the Server**
   ```sh
    python manage.py runserver
   ```
   → Access the app at: http://127.0.0.1:8000

### Creating a Superuser (Admin)
```sh
python manage.py createsuperuser
```
Follow the prompts to set up an admin account.

## Next Steps
* Host the app online (e.g., PythonAnywhere, Heroku, or Railway) so friends can join.

* Explore & customize the system for your needs!

## Thank You! 🎉
Enjoy Level_Up and have fun gamifying your life!
