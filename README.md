Women In Sports Data 2022 Hackathon

An Analysis of Pass Type Effectiveness of Italy and England in Euro 2020

Maya McArthur and Z Martinez

Description: 
This project analyzes the effectiveness of different types of soccer passes by Italy and England in the 2020 Euros. We analyze Italy and England because they were the finalists who competed in the championship game with Italy coming out on top. Our motivation for this project stems from our interest in utilizing 360 freeze frame data to map out player locations and analyze pass effectiveness by being able to track the pass recipient's status as either a teammate or an opponent. We define a successful pass as one that is received by a player that is on the same team as the passer (AKA a teammate). Our aim for this project was to analyze pass type effectiveness to identify strengths and weaknesses in each teams offensive strategy, specifically surrounding passing. Using R and RStudio was beneficial in restructuring the data and creating visualizations.

The main challenge we faced was the structure of the data. First, the was structured in such a way that in rows where the player was a ball receiver, the pass type and pass cross variables were N/As. This made matching the ball receiver to the passer and freeze frame id difficult as we had to go through manually and match the receiving play to the passing play and manually change each id. 

Prerequisites:
This project was developed in macOS Monterey Ver. 12.4.
It was coded in RStudio Version 4.1.2.

Installation and running the project: 
1. Install R. To install R, go to https://cran.r-project.org/mirrors.html, find your country and follow the subsequent links. 
2. Install RStudio. To install RStudio, go to https://www.rstudio.com/products/rstudio/download/ and follow the directions corresponding to your software. 
3. With both R and RStudio installed. Open RStudio.
4. From the repo, download WISD_MZCrew.rmd.
5. Open WISD_MZCrew.rmd in RStudio. 
6. Install all necessary packages (listed in the project description) in RStudio. 
7. Aside from ggsankey, all of the other packages can be installed directly in RStudio. To install ggsankey, run the following code:
install.packages("remotes") 
remotes::install_github("davidsjoberg/ggsankey")
library(ggsankey)
7. With packages installed, you are now ready to run the code!

Credits:
Collaboration project between Maya McArthur and Z Martinez.
Hackathon organized by Women in Sports Data.
Data provided by StatsBomb. We used StatsBombR, a package developed for R users by StatsBomb to access their data. This can be found at https://github.com/statsbomb/StatsBombR.
