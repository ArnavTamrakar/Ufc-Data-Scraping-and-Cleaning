# UFC Fight Data Analysis

This project is a Jupyter Notebook that processes and analyzes UFC fight statistics using Pandas. It cleans and transforms fight data, making it easier to analyze metrics like strikes, knockdowns, and submission attempts.

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/ufc-fight-analysis.git
cd ufc-fight-analysis
```

2. Install the required Python packages:

```bash
pip install pandas jupyter
```

3. Open the notebook:

```bash
jupyter notebook ufcc.ipynb
```

4. Load your UFC fight dataset in the notebook.

5. Run the cells to process the data and convert fight metrics to numeric values.

## What It Does

- Cleans and converts columns like `Round`, `Knockdowns`, `Strike`, etc., into integers using Pandas.
- Handles errors by converting invalid data to `NaN` where needed.
- Prepares the data for analysis or further processing.

## Columns Converted

- Round
- Knockdowns
- Strike
- Takedown
- SubmissionAttempts
- Significant Strikes (Landed/Attempted/Percentage)
- Head, Body, Leg Strikes (Landed/Attempted)
- Distance, Clinch, Ground Strikes (Landed/Attempted)

## License

Feel free to use this project for whatever you like.
