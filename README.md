{\rtf1\ansi\ansicpg1252\cocoartf1404\cocoasubrtf470
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fswiss\fcharset0 ArialMT;}
{\colortbl;\red255\green255\blue255;\red26\green26\blue26;\red255\green255\blue255;\red26\green26\blue26;
}
\paperw11900\paperh16840\margl1440\margr1440\vieww19000\viewh12720\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \

\fs72 R code for producing the results appeared in the paper \

\fs24 \
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\fs36 \cf0 \

\fs48 1- The
\f1 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2  descriptions for the files:\
R code for example 1 in the paper:\
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs36 \cf0 \cb1 \kerning1\expnd0\expndtw0 \ul \ulc0 \outl0\strokewidth0 1)\ulnone Run_file_final.R : The main R code that Run all the methods.\ul \
\ulnone 2)Initial_parameters_final.R : File generate all the initial value for the parameters in example 1.\
3) ABC_MCMC_SIR_final.R: File contains all the function needed to implement MCMC, ABC SMC, ABC SMC with adaptive distance and function to implement Vaart\'92s method. \
4) Sir_data.rds: Sir data that used on example 1.\
\
\ul 5)\ulnone Fig_2.R: R code that produce the figure number 2 in first example.\
6)Fig_3.R: R code that produce the figure number 3 in first example.\
7) Fig_4.R: R code that produce the figure number 4 in first example.\
8)Fig_5: R code that produce the figure number 5 in first example.\
9) Fig_6.R: R code that produce the figure number 6 in first example.\
10) Fig_7.R : R code that produce the figure number 7 in first example. \
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f1\fs48 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf4 \cb1 \outl0\strokewidth0 R code for example 2 in the paper:\
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs36 \cf0 \kerning1\expnd0\expndtw0 11) Run_file_Malariah.R: The main R code that Run all the methods.\
\
12) Initial_parameters_Malariah_final.R : File generate all the initial value for all the parameters.\
\
13) ABC_MCMC_Malariah.R: File contains all the function needed to implement MCMC, ABC SMC and ABC MCMC.\
\
14) Malariah_data.rds : Malariah Data used on example 2.\
\
15) Fig_9.R: R code that produce the figure number 9 in Second example. \
16) Fig_10.R: R code that produce the figure number 10 in Second example. \
\

\f1\fs48 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 \
2- Information in How to run the R code for Example 1 and 2:\

\f0\fs36 \cf0 \cb1 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 \
\ul #######Code and data to generate results for The First Example:\
\ulnone \
To run the software please Run the main file \'93Run_file_final.R \'94(File that Run all the methods) which will call the data, functions and the initial values from \'93Sir_data.rds\'94, \'93ABC_MCMC_SIR_final.R\'94 and \'93Initial_parameters_final.R\'94.\
\
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0
\cf0 \
\
\ul #######Code and data to generate results for Second Example:\
\
\ulnone To run the software please Run the main file \'93Run_file_Malariah.R\'94 (File that Run all the methods.) which will call the data, functions and the initial values from \'93Malariah_data.rds \'94 , \'93ABC_MCMC_Malariah.R:\'94 and \'93 Initial_parameters_Malariah_final.R\'94.\
\
\
\
\
}
