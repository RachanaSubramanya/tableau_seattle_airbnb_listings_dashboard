# Tableau dashboard
## Seattle Airbnb listings

_Understanding Seattle Airbnb listings and it's corresponding prices, and to evaluate the opportune time period to put up a listing using Tableau dashboard._

---

## Table of contents
- <a href= "#overview">Overview</a>
- <a href= "#business-problem">Business problem</a>
- <a href= "#dataset">Dataset</a>
- <a href= "#tools--technologies">Tools and Technologies</a>
- <a href= "#project-structure">Project Structure</a>
- <a href= "#data-cleaning-preparation">Data Cleaning and Preparation</a>
- <a href= "#exploratory-data-analysis">Exploatory Data Analysis</a>
- <a href= "#research-questions-key-findings">Research questions and Key findings</a>
- <a href= "#dashboard">Dashboard</a>
- <a href= "#how-to-run-this-project">How to run this project</a>
- <a href= "#author-contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project aims at understanding how the listing price changes based on locale and neighborhood to derive strategic insights for using the facilities of Airbnb. Data was sourced from kaggle and an interactive dashboard was built using Tableau.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Analysing patterns and trends is crucial for providing solutions. This project aims to viualize:
- Average listing prices of all Airbnbs in Seattle
- Correlation between number of bedrooms and price of the listing
- Average prices of Airbnbs with respect to locality
- Best times to put a listing, for those who want to list their houses only during peak-season

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

Excel file stored in folder `/data/` (seattle_airbnb_listings)

---

<h2><a class="anchor" id="tools--technologies"></a>Tools and Technologies</h2>

- Tableau public 
- Github

---

<h2><a class="anchor" id="project-structure"></a>Project Structures</h2>

```
tableau_seattle_airbnb_listings_dashboard/
│   README.md
│
├───dashboard
│       tableau_seattle_airbnb_listings_dashboard.twbx
│
└───data
        seattle_airbnb_listings.xlsx
```

---

<h2><a class="anchor" id="data-cleaning-preparation"></a>Data Cleaning and Preparation</h2>

Removed rows pertaining to:
- "null" bedrooms
- "0" bedrooms

---

<h2><a class="anchor" id="research-questions-key-findings"></a>Research questions and Key findings</h2>

The following conclusions can be drawn:
- The prime spot for Airbnb listings is 'Fairmount Park' as it has the highest average price of all areas.
- There is direct correlation with the price and the number of bedrooms, as the price for listings goes up with an additional bedroom
- The total number of houses listed, in accordance to the number of bedrooms offered. This shows that there are fewer houses listed as the number of rooms increases.
- Revenue generated from Airbnbs has a trend. It can be observed that there are 2 'peaks', once during mid-July, and once more towards the 3rd week of December, right before christmas. Thus it can be concluded that those who prefer to list their houses temporarily can do so in these optimal time slots.

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

Tableau dashboard shows:
- Average price per bedroom
- Count of house listings for with respect to number of bedrooms
- Average prices per neighborhood
- Revenue generated throughout the year on a weekly basis

![Seattle Airbnb Dashboard Preview](screenshots/dashboard-preview.png)

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to run this project</h2>

Clip on the below link to view the interactive dashboard

<https://public.tableau.com/views/tableau_seattle_airbnb_listings_dashboard/Dashboard1?:language=en-US&:sid=96DC1268F1A945C8A9CCD59035B03A8B-0:0&:redirect=auth&:display_count=n&:origin=viz_share_link>

---

<h2><a class="anchor" id="author-contact"></a>Author & Contact</h2>

*Rachana Subramanya*
email: rachanasubramanya50@gmail.com
[LinkedIn](https://www.linkedin.com/in/rachana-subramanya-4ab0b3303/)
[Github](https://github.com/RachanaSubramanya)

---


