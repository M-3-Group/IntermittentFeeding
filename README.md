# IntermittentFeeding
Codes for the paper "Modulating microbial intake helps to maintain the gut microbiome diversity" by Vitor M. Marquioni, Ann-Cathrin Hofacker, Jocksan V. Villavicencio, and Florence Bansept
Available on Zenodo: 10.5281/zenodo.18802498

## File 1: Intermittent Feeding - 2 types.nb
This code integrates the dynamics for a two microbial types case. It also calculates the heatmap the time-averaged Shannon diversity, identifying the Optimal Feeding Strategy and calculating its linear approximation. (This is the code behind figures 1 and 2)

### Data 1: heatmap-data.zip

Heatmap data generated and used in "File 1".

## File 2: Maximal Diversity - Many types.nb

This code uses the numerical method we describe in the paper to solve the equation of the optimal feeding rate in the where there are many different microbial types with random parameters. (This is the code behind figures 3, 4 and S2-S7).

### Data 2: data-behind-figure-3and4.zip

This folder comprises the exact data (in JSON format) plotted in figures 3 and 4, generated with the code within "File 2". However, this is not the rawdata that is loaded when running the Output Analysis in "File 2."

## File 3: Noisy Intermittent Feeding - 2 types.nb

This code extends the "File 1" in order to include dispersal noise. (This is the code behind figure 5 and S8)

### Data 3: Noise-heatmap-data.zip

Heatmap data generated and used in "File 3".
