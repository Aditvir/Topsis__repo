# TOPSIS

A Streamlit web application for performing TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) analysis.

## Features

- Upload CSV data files
- Configure weights and impacts
- Instant TOPSIS analysis
- Download results as CSV
- Email results directly to your inbox
- Modern, user-friendly interface

## Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Streamlit app locally:
```bash
streamlit run streamlit_app.py
```

## Usage

1. **Upload CSV**: Select your TOPSIS decision matrix CSV file
2. **Enter Weights**: Comma-separated values (will be normalized automatically)
3. **Enter Impacts**: Use `+` for benefit criteria, `-` for cost criteria
4. **Email Address**: Provide your email to receive results
5. **Run Analysis**: Click the "Run TOPSIS Analysis" button
6. **Download/Share**: Download results or send via email

## File Structure

```
.
TOPSIS-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── topsis.py              # Core TOPSIS algorithm
├── streamlit_app.py       # Main Streamlit application
├── app.py                 # (Optional) Flask version
├── Topsis.ipynb           # Jupyter notebook demo
│
├── data/
│   └── sample_data.csv    # Example dataset (rename data_topsis.csv)
│
├── static/                # (Only if using Flask)
│   └── style.css
│
├── templates/             # (Only if using Flask)
│   └── index.html
│
└── .streamlit/
    └── config.toml        # Streamlit config (optional)

streamlit Link https://pypi.org/project/Topsis-Aditvir-102317150/
```

## Requirements

- Python 3.8+
- See `requirements.txt` for all dependencies

## License

MIT

## Author

Aditvir Rinwa
