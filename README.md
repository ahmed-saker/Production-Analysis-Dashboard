# 📊 Production Analysis Dashboard – Power BI

An interactive Power BI dashboard connected to a database, built to analyze hotel booking production in the travel & hospitality industry. It provides a complete view of room nights, bookings, sales, and profit, with year-over-year comparisons across customers, hotels, hotel chains, product groups, departments, and destinations.

![Dashboard Preview](images/overview.png)

---

## 📌 What Does This Dashboard Do?

The dashboard converts raw production data into clear, interactive visuals so teams can monitor performance, measure growth or decline against the previous year, and identify what drives revenue and profitability. It covers:

- Core performance KPIs with last-year comparison
- Production trends over time by booking date
- Performance by customer, nationality, department, and product group
- Hotel, hotel chain, and hotel category analysis
- Destination analysis by country and city
- Year-over-year change tables with visual up/down indicators

## 💡 How Does It Help?

- **Monitor performance at a glance:** track room nights, bookings, sales, and profit against last year in one place.
- **Spot trends and seasonality:** see how production changes month by month and compare years side by side.
- **Understand customers:** identify the customers that contribute the most and detect which ones are growing or declining.
- **Know your profit drivers:** compare nationalities, chains, and product groups by both volume and profit, not just bookings.
- **Evaluate suppliers and properties:** find top-performing hotels, chains, and categories, and the ones losing ground.
- **Track internal channels:** measure production across departments and product groups to see which channels perform best.
- **Detect risks and opportunities early:** growth/decline indicators highlight where action is needed, whether a drop to investigate or a rising partner to support.
- **Drill down easily:** global filters and drop-down tables let users move from country to city to individual hotel.

## 🗂️ Dashboard Pages

| Page | Purpose |
|------|---------|
| **Overview** | KPI cards (Room Nights, Bookings, Sales, Profit) with last-year comparison, top nationalities, bookings by hotel category, room nights trend by booking date, and top customers |
| **Profit & Distribution** | Top nationalities by profit, top hotels by bookings, and production by department |
| **Hotel Chain Production** | Room nights, bookings, sales, and profit per chain, plus top chains comparison |
| **Hotel Chain & Category YoY** | Year-over-year change per hotel chain and per hotel star category |
| **Product Group Production** | Production summary per product group and top groups comparison |
| **Product Group YoY** | Year-over-year change for each product group |
| **Customer YoY** | Year-over-year change in bookings, room nights, sales, and profit per customer |
| **Hotel YoY** | Hotel-level change with drop-down detail by property |
| **Country YoY** | Year-over-year change by destination country |
| **City YoY** | Year-over-year change by city / province |

## 🎛️ Global Filters

Hotel Chain · Category · Customer Name · Month · Year · Nationality · Department · Product Group

## 📐 Key Metrics

| Metric | Description |
|--------|-------------|
| **Room Nights** | Total number of nights booked |
| **Bookings** | Total number of bookings |
| **Sales** | Total sales value |
| **Profit** | Total profit generated |
| **LY Comparison** | Value and % change versus the same period last year |
| **Diff / % Change** | Absolute and percentage change between periods, shown with up/down arrows |

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI Desktop | Dashboard design & visualization |
| DAX | Measures, time intelligence, and YoY calculations |
| Power Query (M) | Data cleaning & transformation |
| `[SQL Server / MySQL / PostgreSQL]` | Data source |

## 🗄️ Data Source

The dashboard connects directly to a relational database containing bookings, customers, hotels, product groups, departments, and geography data, modeled as a star schema with fact and dimension tables.

> ⚠️ Connection details and real data are **not** included in this repository.

## 📂 Repository Structure

```
├── Production_Analysis_Dashboard.pbix   # Power BI file
├── images/                              # Dashboard screenshots
├── sql/                                 # SQL scripts / schema (optional)
└── README.md
```

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/[repo-name].git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Go to **Transform Data → Data Source Settings** and enter your own server and database details.
4. Click **Refresh** to load the data.

## 👤 Author

**[Your Name]**
- LinkedIn: [your-linkedin-link]
- GitHub: [@your-username](https://github.com/your-username)
- Email: [your-email]

---

⭐ If you find this project useful, feel free to give it a star!
