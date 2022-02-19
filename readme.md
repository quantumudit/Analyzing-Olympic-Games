![Project Logo][project_logo]

---

<h4 align="center">Analyzing Olympic Games with T-SQL Querying</h4>

<p align='center'>
<img src="https://i.ibb.co/KxfMMsP/built-with-love.png" alt="built-with-love" border="0">
<img src="https://i.ibb.co/MBDK1Pk/powered-by-coffee.png" alt="powered-by-coffee" border="0">
<img src="https://i.ibb.co/CtGqhQH/cc-nc-sa.png" alt="cc-nc-sa" border="0">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

## Overview

This project focuses on historical dataset on the modern Olympic Games, including all the games from Athens 1896 to Rio 2016.

The repository directory structure is as follows:

Analyzing-Olympic-Games<br>
├─ 01_DATABASE<br>
├─ 02_ANALYSIS<br>
├─ 03_RESOURCES<br>

The type of content present in the directories is as follows:

**01_DATABASE**

This directory contains the T-SQL script to create the database and the underlying tables for the analysis

**02_ANALYSIS**

This directory contains the SQL Notebooks that analyzes the data through T-SQL querying

**03_RESOURCES**

This directory contains images, icons, layouts, etc. that are used in this project

## Prerequisites

The major skills that are required as prerequisite to fully understand this project are as follows:

- Intermediate to Advance T-SQL querying
- Microsoft SQL Server interface
- Basic understanding of Azure Data Studio (ADS)

In order to complete the project, I've used the following applications and libraries

- SQL Server Management Studio (SSMS)
- Azure Data Studio (ADS)

> The choice of applications & their installation might vary based on individual preferences & system settings.

## Architecture

The project architecture is quite straight forward and can be explained through the below image:

![Process Architecture][process_workflow]

As per the above workflow suggests; we are first get the underlying data from [kaggle][kaggle_link] to create the database and it's tables.

Finally, we use T-SQL queries to analyze the data in a SQL notebook.

## Support

If you have any doubts, queries or, suggestions then, please connect with me in any of the following platforms:

[![Linkedin Badge][linkedinbadge]][linkedin] [![Twitter Badge][twitterbadge]][twitter]

If you like my work then, you may support me at Patreon:

<a href="https://www.patreon.com/quantumudit" target="_blank">
<img src="https://i.ibb.co/94bkJwp/become-a-patreon.png" alt="become-a-patreon" border="0" width="170" height="50">
</a>

## License

<a href = 'https://creativecommons.org/licenses/by-nc-sa/4.0/' target="_blank">
    <img src="https://i.ibb.co/mvmWGkm/by-nc-sa.png" alt="by-nc-sa" border="0" width="88" height="31">
</a>

This license allows reusers to distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, and only so long as attribution is given to the creator. If you remix, adapt, or build upon the material, you must license the modified material under identical terms.

<!-- Image Links -->

[project_logo]: 06_RESOURCES/project_cover_image.png
[process_workflow]: 06_RESOURCES/process_architecture.png
[scraping_graphic]: 06_RESOURCES/scraping_graphic.gif

<!-- External Links -->

[kaggle_link]: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results

<!-- Profile Links -->

[linkedin]: https://www.linkedin.com/in/uditkumarchatterjee/
[twitter]: https://twitter.com/quantumudit

<!-- Shields Profile Links -->

[linkedinbadge]: https://img.shields.io/badge/-uditkumarchatterjee-0e76a8?style=flat&labelColor=0e76a8&logo=linkedin&logoColor=white
[twitterbadge]: https://img.shields.io/badge/-@quantumudit-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/quantumudit
