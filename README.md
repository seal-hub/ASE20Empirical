## Test Automation in Open-Source Android Apps: A Large-Scale Empirical Study (ASE'20)

![Methodology](methodology.png)

### Abstract
Automated testing of mobile apps has received significant attention in the recent years from researchers and practitioners alike. In this paper, we report on the largest empirical study to date, aimed at understanding the test automation culture prevalent among mobile app developers. We systematically examined more than 3.5 million repositories on GitHub and identified more than 12,000 non-trivial and real-world Android apps. We then analyzed these non-trivial apps to investigate (1) the trends in adoption of test automation; (2) working habits of mobile app developers in regards to automated testing; and (3) the correlation between the adoption of test automation and the popularity of projects. Among others, we found that (1) only 8% of the mobile app development projects leverage automated testing practices; (2) developers tend to follow the same test automation practices across projects; and (3) popular projects, measured in terms of the number of contributors, stars, and forks on GitHub, are more likely to adopt test automation practices. To understand the rationale behind our observations, we further conducted a survey with 148 professional and experienced developers contributing to the subject apps. Our findings shed light on the current practices and future research directions pertaining to test automation for mobile app development. 

### Artifacts
The artifacts can be found here:
https://drive.google.com/file/d/1OXyitVmphv2jFrvwDSizv-ZnVYoDVZuk/view?usp=sharing (zip, 353MB)

It includes:
* Our data set, including the analysis of the RQs, sample of our survey, survey responses, and a list of 12,562 repos in our study.
* The scripts and database file to reproduce our analysis. Prerequisites to run the script:
  * Python 3.6, with these packages installed: `numpy, scipy, python-dateutil, peewee`
  * Unzip the database file as `db.sqlite3`
* To run the analysis:
```
python stats.py
```
To produce the curated json file:
```
python output.py
```

### Publication
Jun-Wei Lin, Navid Salehnamadi, and Sam Malek, "Test automation in open-sourceandroid apps: A large-scale empirical study," in 2020 35th IEEE/ACM International Conference on Automated Software Engineering (ASE), 2020
