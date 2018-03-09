# Exploring Red Tape in Vietnam (Under construction)

This project is a reboot of an earlier academic paper from my a statistics class for my masters program in International
Economics at the University of California, San Diego. Instead of Stata, I used R to assess the effect of bureaucracy 
on new business registration in Vietnam.

## Background 

In 2009, Vietnam halted the operation of People's Councils in ten provinces, specifically chosen as a quasi-random sampling, in order to statistically assess the effects of recentralization on service provision and corruption. In this project, I used a random effects model on panel data to show that removing an extra step in the hierarchy of specific provinces correlated with shortening new business registration times by more than 2 days with a high degree of statistical significance, likely by cutting new business registration times. This result suggests that further recentralization of power to the provincial level would improve the efficiency of bureaucracy in dealing with business startups and growign the Vietnamese economy.

## Installation

Clone the GitHub repository and use Conda to start a new environment using R and install associated packages. 
Then open the Jupyter Notebook.

```
$ git clone https://github.com/briantfriederich/Exploring_red_tape_in_Vietnam
$ cd ~/Exploring_red_tape_in_Vietnam-master
$ conda create -n huyenproj r-essentials r-base
$ source activate huyenproj
$ jupyter notebook
```

## License

This project is released under the MIT License.

