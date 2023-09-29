
# Tire Data Analysis - Cornering

This project analyzes tire data collected during cornering tests for seven different tires. The analysis includes plotting Normalized Saturated FY vs. FZ and plotting Corner Stiffness vs. FZ under two distinct pressure conditions.
Access to this data is through the FSAE TTC secure forum at www.fsaettc.org. Refer to the acknowledgment for more information.


## Acknowledgements

 - [Formula SAE Tire Test Consortium (FSAE TTC)](http://www.millikenresearch.com/fsaettc.html)
 - [Calspan Tire Research Facility (TIRF)](https://calspan.com/)
 - [Formula SAE® – Tire Force and Moments Overview](https://www.youtube.com/watch?v=2tIr8pgo4ds)


## Screenshots

![](image/Input%20Parameters%20Over%20Time.png)
![](image/FY%20vs.%20SA.png)
![](image/Normalized%20Saturated%20FY%20vs.%20FZ.png)
![](image/Corner%20Stiffness%20vs.%20FZ.png)


## Roadmap

- Read and import the test data

- Plot input parameters over time

- Filter relevant tire tests

- Fit Lateral Force vs. Slip Angle curves

- Calculate Saturated Lateral Force

- Calculate Corner Stiffness

- Create informative plots


## Deployment

To deploy this project run

```bash
  pip install pandas
  pip install matplotlib
  pip install numpy
  pip install seaborn
  pip install plotly
  pip install scipy
```
