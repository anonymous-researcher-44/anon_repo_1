# Code for Reproducibility

## Notebooks
There are three primary python notebooks

- simulated_example.ipynb
- play_delay_example.ipynb
- power_comparison.ipynb

You may need to install the following python libraries to your environment.
```
pip install numpy pandas matplotlib scipy tqdm joblib fn.py
```

These notebooks contain computationally intensive simulations.
To avoid re-running the simulations, the simulation results have been pickled for convenience.

## Pickled Simulation Results
To bypass reperforming the simulations, one can simply skip the cells in the notebook, and proceed to the cell which reads from the .pkl files.

- bernstein_playdelay_alt.pkl
- bernstein_playdelay_null.pkl
- play_delay_lm_results_alt.pkl
- play_delay_lm_results_null.pkl
- power_0.2.pkl
- power_0.4.pkl
- power_0.pkl
- simulated_example_alternative.pkl
- simulated_example_null.pkl

## Data
The PlayDelay dataset is contained in playdelay.csv.
The columns are:

- treatment, a binary treatment indicator
- play_delay, the post-treatment time outcome, normalized by the largest value
- pre_play_delay, the pre-treatment time outcome, normalized by the largest value of play_delay
- log_play_delay, the post-treatment log-time outcome, normalized by the largest value
- log_pre_play_delay, the pre-treatment log-time outcome, normalized by the largest value of log_play_delay

## Figures
- jasa_play_delay_cdf.png
- playdelay_alt.png
- playdelay_null.png
- simulated_example_alternative.png
- simulated_example_null.png
- stopping_times_xi_0.png
- stopping_times_xi_0.4.png
- stopping_times_xi_0.2.png


