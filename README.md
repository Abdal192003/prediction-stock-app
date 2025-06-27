![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005015.png?raw=true)
![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005031.png?raw=true)
![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005047.png?raw=true)
![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005101.png?raw=true)
![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005114.png?raw=true)
![image alt](https://github.com/Abdal192003/prediction-stock-app/blob/main/Screenshot%202025-06-28%20005131.png?raw=true)

# Stock Price Prediction

A machine learning project for predicting stock prices using deep learning.

## Project Structure

- `Stock_Price_Prediction_model.ipynb`: Jupyter notebook containing the model training and evaluation code
- `app.py`: Streamlit web application for making predictions
- `my_stock_prediction_model.keras`: Trained Keras model
- `requirements.txt`: Python dependencies

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```
   conda create -p myenv python==3.10
   ```
3. Activate the virtual environment:
   - Windows: `conda activate myenv`
4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
5. Run the Streamlit application:
   ```
   streamlit app.py
   ```
6. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Open `Stock_Price_Prediction_model.ipynb` in Jupyter Notebook to explore the model training
2. Use the Flask web interface to make predictions

## Dependencies

- Python 3.x
- TensorFlow/Keras
- streamlit
- pandas
- numpy
- scikit-learn
- yfinance (for fetching stock data)

## License

This project is open source and available under the [MIT License](LICENSE).
