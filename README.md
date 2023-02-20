## MicroBNetwork
MicroBNetwork is a a computationally efficient and statistically powerful methods for microbial network analyses: 
Hubs, Multiple Conditions, and Complex Design.



1.  [Installation](#installation)
2.  [Framework](#framework)
3.  [Prostate, Lung, Colorectal, and Ovarian Trial](#plco)


Installation
------------

### devtools ###
R packages vegan, plyr installed.

From an interactive R session:

```{r, eval=FALSE}
library(devtools)
install_github("jennylsl/MicroBNetwork")
library(MicroBNetwork)
```

Framework
------------

![image](https://user-images.githubusercontent.com/68125044/220179982-062e7eb1-36e1-4b6e-aa69-b906f144555b.png)
Oral microbiome study in PLCO trial
------------

Three lung cancer cases: Adenocarcinoma (LUAD), Small cell carcinoma (LUSCC), Squamous cell carcinoma (LUSC), and healthy controls
![image](https://user-images.githubusercontent.com/68125044/220180154-e47775ea-d430-4558-a7e6-53e49b37d28e.png)

Testing heterogeneity for three lung cancer cases
![image](https://user-images.githubusercontent.com/68125044/220180421-6c635d68-b1b0-4689-9a6d-5c8fcec281d3.png)

Testing heterogeneity for control and cases
![image](https://user-images.githubusercontent.com/68125044/220180467-99d630ca-748b-494f-a1cc-bc5270a98a79.png)




