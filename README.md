# ISTM_6212 - FEC Campaign Financial Data Storytelling with SQL on AWS
https://www.fec.gov/data/browse-data/?tab=bulk-data

## My team and I used open data source on FEC to answer those interesting questions. 
1.	Candidates received most contribution by individual (top 5)
    + Total amount of contributions by individual (2020 vs 2016)
    + Contributions by individual breakdown in 2020 for Biden vs Trump 
      * Among swing states
      * Among regions
    + Contributions by individual breakdown for Trump in 2020 vs 2016
      * Among regions
2.	Top 5 Committees that received most funds (2020 vs 2016)
3.	Which five states have the most candidate offices?
    +	2020 vs 2016
    +	Among those top 5 states with the most candidates’ offices, what are the distribution of parties in 2020 and 2016?
4.	Contribution by individual and committee breakdown by States
    +	Committees contribution in 2016
    +	Individual contribution in 2016
    +	Committees contribution in 2020
    +	Individual contribution in 2020
5.	Contribution Comparison for Trump, Biden, Clinton in year 2020 and 2016
    +	Total amount by individual and by Committee
    +	Contribution by individual break down by month
6.	Occupation breakdown for individual contributors supporting Democrat and Republican (2016 vs 2020)


## All the work is accoumplished on Amazon AWS EC2 and data is imported using S3. Data was then sorted in dimensional schema.
### Table 1 - Contribution
![alt text](https://github.com/rainieluo2016/ISTM_6212/blob/main/contribution%20table.png?raw=true)

### Table 2 - Candidate
![alt text](https://github.com/rainieluo2016/ISTM_6212/blob/main/candidate_final.png?raw=true)
