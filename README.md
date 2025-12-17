# NYC Taxi Fare Estimator 

**Live app:** https://huggingface.co/spaces/Yashu0711/NYC-Taxi-Project
**Demo video:** <paste link when ready>  

## What this does
Enter trip details (distance, time, weekday/weekend, rush-hour, pickup zone, drop-off zone, rain flag) → get one **total fare** number with a small suggested range.

## Run locally
```bash
pip install -r requirements.txt
python -m streamlit run app.py
