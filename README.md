
## Methodology

- **Data Source:** [StatsBomb Open Data](https://github.com/statsbomb/open-data) for the 2015–2016 Premier League season.
- **Data Preparation:** Data is filtered and cleaned to extract only assist events.
- **Feature Engineering:** 13 features relevant to assist patterns are selected and encoded (see paper for details).
- **Clustering:** Hierarchical Agglomerative Clustering (HAC) with cosine similarity groups assists by pattern.
- **Statistical Analysis:** Statistical comparisons are made between Leicester City and league averages.
- **Visualization:** All plots and charts are generated in `main.ipynb` and saved in `figures/`.

## Required packages
pandas	1.3.0	(Data manipulation and analysis)
numpy	1.21.0	(Numerical operations)
matplotlib	3.4.0	(Plotting and visualization)
seaborn	0.11.0	(Statistical data visualization)
scikit-learn	0.24.0	(Clustering and machine learning utilities)
statsbombpy	1.14.0	(Accessing StatsBomb open data)
scipy	1.7.0	Statistical tests (t-test, chi-square, etc.)
tqdm	4.60.0	Progress bars (optional, for loops)
jupyter	1.0.0	(Running notebooks)
mplsoccer 1.2.6 (Visualizing football pitches)
## How to Reproduce

1. **Clone the repository** and ensure you have Python 3.x, Jupyter Notebook, and the required packages (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, etc.).
2. **Open, and optionally re-run** `main.ipynb` to reproduce all analysis and figures.

## Figures

All generated figures (cluster dendrograms, assist zone distributions, pass length comparisons, etc.) are saved in the `figures/` directory.

## Key Findings

- Identified 33 distinct assist patterns using clustering.
- Leicester City’s assists were longer and more frequently originated from inside the penalty area compared to the league average.
- The methodology and code are fully reproducible for other leagues and seasons.

## Citation

If you use this code or analysis, please cite the associated paper or this repository.

## Contact

For questions or collaborations, please contact i.meghea@student.vu.nl.
