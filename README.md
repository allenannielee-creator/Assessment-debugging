# Setup & Run Instructions
## 1. Install Python
Type these commands to install the correct version of Python and pip
```
sudo apt update
sudo apt install python3
sudo apt install python3-pip
```
## 2. Create and Activate a Virtual Environment
Type these commands into the command line to create a virtual environment to isolate the dependencies.

```
python3 -m venv venv
source venv/bin/activate
```
## 3. Install Dependencies
Type this comand into the command line to install the required packages.
```
pip install -e .
```
## 4. Run the Application
Run the application by typing this command into the terminal
```
python main.py
```
## 5. Access the Application
The application will be running on http://127.0.0.1:10030. Simply copy and paste the URL into your browser