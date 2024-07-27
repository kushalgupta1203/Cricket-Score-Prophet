# Cricket-Score-Prophet 🏏

Cricket-Score-Prophet is a Flask web application that predicts cricket match scores using a pre-trained model. The application leverages historical T20 match data to provide score predictions for upcoming T20 matches.

## Installation

To get started, clone the repository and install the required dependencies.

### 1. Clone the Repository:
   ```bash
   git clone https://github.com/your-username/Cricket-Score-Prophet.git
   cd Cricket-Score-Prophet
```

### 2. Create a Virtual Environment:

```bash
python -m venv venv
```
#### On MacOS
```bash
source venv/bin/activate
```
#### On Windows
```bash
venv\Scripts\activate
```
### 3. Install Dependencies:

```bash
pip install -r requirements.txt
```
## Dataset
The application uses the dataset t20i_info.csv, which contains historical T20 match data. Ensure this file is placed in the root directory of the project.

## Usage
### Run the Flask Application:

```bash
python app.py
```
### Access the Web Application:
Open your web browser and navigate to http://127.0.0.1:5000/.

![Alt text](https://github.com/kushalgupta1203/Cricket-Score-Prophet/blob/main/sample/1.png)
![Alt text](https://github.com/kushalgupta1203/Cricket-Score-Prophet/blob/main/sample/2.png)
![Alt text](https://github.com/kushalgupta1203/Cricket-Score-Prophet/blob/main/sample/3.png)
![Alt text](https://github.com/kushalgupta1203/Cricket-Score-Prophet/blob/main/sample/4.png)

### Code Structure
- app.py: The main Flask application file.
- model/: Contains the pre-trained model files.
- static/: Contains static files such as CSS and JavaScript.
- templates/: Contains HTML templates for the Flask application.
