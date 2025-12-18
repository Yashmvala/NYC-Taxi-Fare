# NYC Taxi Fare Estimator 

**Live app:** https://huggingface.co/spaces/Yashu0711/NYC-Taxi-Project
**Demo video:** <paste link when ready>  

## What this does
Enter trip details (distance, time, weekday/weekend, rush-hour, pickup zone, drop-off zone, rain flag) → get one **total fare** number with a small suggested range.

## How to run locally 
pip install -r requirements.txt
python -m streamlit run app.py
# Then open http://localhost:8501

## Reproduce training
Open `notebooks/colab_training_v2.ipynb` in Google Colab → Run All.
It saves `models/model_v2.pkl` (already included in this repo).
