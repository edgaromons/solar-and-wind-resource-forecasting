In this project, we:

● Utilized Python and TensorFlow/Keras to develop and evaluate various deep learning models, including Linear, Dense, LSTM, 1-Dimensional Convolutional, and Recurrent Autoencoder models, for one-hour ahead wind speed forecasting. 

● Performed data preprocessing techniques, including data cleaning, downsampling, and scaling, to prepare time-series data for model training. 

● Implemented a persistence model as a baseline for performance comparison with trainable models. 

● Defined and applied evaluation metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE) to assess model accuracy. 

● Conducted hyperparameter tuning using learning rate scheduling to optimize model performance. 

● Visualized model predictions and performance metrics using Matplotlib and Seaborn.


Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
