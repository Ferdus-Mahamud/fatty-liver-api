# 🩺 Fatty Liver Disease Prediction API

Simple Flask API for predicting Non-Alcoholic Fatty Liver Disease.

## Run Locally

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Start the server:
   ```
   python app.py
   ```

3. Send POST request to:
   ```
   http://localhost:5000/predict
   ```

## Deploy on Render
- Push code to GitHub.
- Create a new Web Service on Render.
- Use build command:
  ```
  pip install -r requirements.txt
  ```
- Start command:
  ```
  python app.py
  ```

## Notes
- Replace `model.pkl` with your trained model file.
