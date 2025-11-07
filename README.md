# Flight Data Analysis with Python 🛫

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** `airlines_flights_data.csv` – Indian domestic flight booking data (scraped)

---

## Project Overview
This project analyzes **domestic flight booking data across major Indian cities** using **Pandas, NumPy, Matplotlib, and Seaborn**. The dataset includes real-world flight details such as airline, price, departure/arrival times, stops, duration, and ticket class.

---

## Dataset Columns
| Column             | Description |
|--------------------|-----------|
| `airline`          | Name of the airline (e.g., Vistara, SpiceJet) |
| `flight`           | Flight number |
| `source_city`      | Departure city |
| `destination_city` | Arrival city |
| `departure_time`   | Time of day (Early Morning, Morning, etc.) |
| `arrival_time`     | Arrival time of day |
| `stops`            | Number of stops (`zero`, `one`, `two_or_more`) |
| `class`            | Ticket class (`Economy`, `Business`) |
| `duration`         | Flight duration in hours |
| `days_left`        | Days before departure when booked |
| `price`            | Ticket price in INR |

---

## Key Analysis Performed
- Loaded and explored the flight dataset
- Filtered flights by:
  - Airline: **Vistara**
  - Route: **Delhi → Hyderabad**
  - Class: **Business**
- Calculated **average ticket price** for premium business flights on this route

> **Result:** Average Business Class fare = **₹47,939.84**

---

## Tools & Libraries
```python
pandas, numpy, matplotlib, seaborn

```
### Insights Gained

- **Business class tickets are significantly more expensive than economy**  
- **Direct flights (`zero` stops) are common on high-demand routes**  
- **Prices vary widely based on booking window (`days_left`) and time of day**
