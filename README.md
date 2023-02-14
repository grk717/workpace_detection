# Workplace detection research
Many computer vision applications are using UI and manual input when it comes to finding person's workplace.
This is a little research on possibility of automatic detection of workplaces.

## Data
Data for this research was taken from free live cameras directory insecam.com
Parser is available in /parser folder.

## Results
Some results are presented in /results folder.
Some findings:
1) Moving cameras are bad when we use clusterization (lol). We could use some registration algorithms for fixing it.
2) MediaPipe works bad on low-res images (as expected).
3) Overall, we've managed to cluster persons interest points.
