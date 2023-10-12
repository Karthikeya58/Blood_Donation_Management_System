# Blood_Donation_Management_System
- Contributers:
Karthikeya Madishetty: 200003044
Aishwarya Vasamshetty: 200003083

The **iDonor** is a **Blood_Donation_Management_System**  designed to help the donors to donate blood to their nearest blood banks and the people who need blood to receive required blood group from the nearby blood banks and active donors.
This website has feature like:
 searching for blood banks in the nearby area, 
 checking blood availability,
 checking eligibility for blood donation,
 taking feedbacks/messages from the users about the website,
 editing the profiles of blood banks and users.

## Instructions For Project Setup

- **Step 1.**
You can directly download the zip file or follow next 2 steps to clone the repo.
Install latest version of git. Open the above github repository link in browser. Click on the code button
and copy HTTPS link.

- **Step 2.**
Create new folder and open git bash inside that folder write command-
```
git clone https://github.com/Karthikeya58/Blood-donation-mangement-system.git
```
- **Step 3.**
  - Install latest version of python and a code editor (Pycharm or Visual Studio Code).
  - Download & Install MYSQLCLIENT For Python : https://www.lfd.uci.edu/~gohlke/pythonlibs/#mysqlclient open this link and under MySQLclient select the wheel according to your python version and 32/64 bit windows system. 
  '''
   cmd.

   

   
- **Step 4.**
   Open the project files in the code editor. Open `app.py` file and if your MySQL username and password are not **root** then you can replace the username and password written in `app.py` file with your MySQL username and password.

- **Step 5.**
  **Installing Packages**

  For Visual Studio Code do the following:
   - Open **New Terminal**

   - And now run the following commands in the terminal:
    ```
    python -m venv env
    Set-ExecutionPolicy Unrestricted -Scope Process
    env\scripts\activate
    pip install flask
    $env:FLASK_APP = "app"
    pip install bcrypt
    pip install flask_mysqldb
    pip install flask_mail
    flask run
    ```

    - Or run `requirements.txt` file :
    ```
    pip install -r requirements.txt
    
    ```


  For Pycharm code editor do the following:
   - Open the terminal

   - And run the following commands:
    ```
    pip install flask,
    pip install bcrypt,
    pip install flask_mysqldb,
    pip install flask_mail

