# Exploring Red Tape in Vietnam

This project is a reboot of an earlier academic paper from my a statistics class for my masters program in International
Economics at the University of California, San Diego. Instead of Stata, I will use R to assess the effect of bureaucracy 
on new business registration in Vietnam.

## Background 

In 2009, Vietnam removed all district-level councils in ten provinces, specifically chosen as a quasi-random sampling, 
in order to statistically assess the effects of recentralization on service provision and corruption. 
However, removing an extra step in the hierarchy of specific provinces also simplified new business registration in those areas, 
cutting new business registration times by 2.5 days, suggesting that further recentralization of power to the provincial level 
may improve the efficiency of bureaucracy in dealing with business startups.

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

