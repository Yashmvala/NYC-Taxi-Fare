# NYC Taxi Fare Estimator — v2 (Zones + Rain)

**Live app:** <paste your Hugging Face Space link here>  
**Demo video:** <paste link when ready>  

## What this does
Enter trip details (distance, time, weekday/weekend, rush-hour, pickup zone, drop-off zone, rain flag) → get one **total fare** number with a small suggested range.

## Run locally
```bash
pip install -r requirements.txt
python -m streamlit run app.py
