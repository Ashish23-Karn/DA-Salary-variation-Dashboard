# DA/DS salary variation
**--Introduction--**

As data is the fuel for the future economic growth of a company and Data Science is the fastest-emerging field in the world. It becomes necessary and need of the hour to analyze the salary variations for data science and its streams corresponding to factors such as skills, years, and locations.

**--Problem aimed to solve--**
The aim of the project is to have some basic insights which can affect the salary in the data science field and to create the interactive PowerBi dashboard for the same.
The dataset contains information about the minimum salary, maximum salary, average salary, job description, location of the company, years, etc.

**--Data Description--**
1. Excel dataset files: This folder has the cleaned dataset for salary variation in .csv format.
2. PowerBi dashboard: This folder has the PowerBi Dashboard in .pbix format.

**--Methodolgy--**

The project involves collecting and processing DA/DS salary variation data for different locations and years. It utilizes data analysis techniques to have insights about salary variation corresponding to basic skills, years, and locations.

**--Phases--**

1. Scrape the data
2. Data cleaning using Power Query editor
3. Data visualization/Dashboard by using PowerBi


**--DashBoard Creation--**

Here is the main PowerBi dashboard which is dynamic in nature and the slicer added is for different countries/locations and corresponding years so that we can see the growth/fall yearly and at different locations.

![Screenshot 2023-07-01 052025](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/0b5d1174-7373-488a-a689-95c78729be26)

**--Insights--**

1.
![Screenshot 2023-07-01 052712](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/53b14bc2-1b10-4342-bbad-01374400ce43)

Here is the variation of "average salary" according to different "locations", From the chart we can conclude that Chile offers more salaries to data scientists in comparison to all other major countries like the USA, the UK or India followed by Hungary.

2.
![Screenshot 2023-07-01 061228](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/3429bb59-5ea8-49f7-a44a-dcd2164c34e4)


Here is the maximum salary offered at a location and again Chile is having the lead followed by Hungary.

3.
![Screenshot 2023-07-01 052553](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/5b18d92e-46f8-472b-a790-4789c730f598)

Here is the number of companies we have taken into consideration and their segregation based on size.

4.
![Screenshot 2023-07-01 052628](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/217ff9e7-93aa-41a7-bf7c-a9a30d206cf7)

Here is the chart depicting the employment type. Most of the companies' data that we take into consideration was having full-time analyst/scientist

5.
![Screenshot 2023-07-01 060926](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/a31e30e4-0d19-4709-8b11-031d067562fa)

Here are the top salaries by skills/profession, As we can see business data analyst has the highest salary than a data scientist or a data analyst guy.

6.
![Screenshot 2023-07-01 052757](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/60c91236-011f-4845-8c1c-40c33389017f)

Here is the "remote work variation" offered by companies in a year, As there were some issues due to coronavirus, in the years 2020, 2021, and 2022 there was continuous growth in "work from home" but there is a dip in remote work phenomena in 2023.

7.
![Screenshot 2023-07-01 052826](https://github.com/Ashish23-Karn/DA-Salary-variation-Dashboard/assets/121361369/b29adf17-8045-4590-8e3c-aa13c41bf8be)

Here is the variation of the number of openings based on experience level, as we can conclude, companies are offering more jobs to "SE" (senior executives) followed by "MI" (mid-level).

--Challenges and learnings--

The main challenge posed by this project was to extract the data. The dataset is scraped from the Glassdoor website using Selenium Scrapper. After scrapping, the raw dataset was cleaned and made usable for performing data analysis.

