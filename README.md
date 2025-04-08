# product-analytics-simulator
E-commerce behavior analytics project using simulated SQL + Python data
# Product Analytics Simulator

A practical, end-to-end project that simulates a realistic product analytics environment for an e-commerce platform.  
Built to reflect how modern companies structure data, ask business questions, and extract value — with a touch of French analytical flair, of course.

---

## Project Overview

This project aims to showcase a business-focused data workflow by:
- Simulating a transactional dataset (users, products, events)
- Exploring user behavior across the purchase funnel
- Designing KPIs and insights relevant to product managers and business analysts
- Bridging the gap between raw data and decision-making

---

## Dataset Structure

The dataset consists of 3 generated `.csv` files:

| File         | Description                                      |
|--------------|--------------------------------------------------|
| `users.csv`   | User info including ID, signup date, location   |
| `products.csv`| Product catalog with category and price         |
| `events.csv`  | User-product interactions: view, cart, purchase |

Generated using Python (`pandas`, `numpy`) — see `simulate_data.py` for reproducibility.

---

## Stack & Tools

- **SQL** – for querying and aggregating data
- **Python** – for simulation and analysis
- **Jupyter / Colab** – for exploration and storytelling
- **Matplotlib / Seaborn** – for visualization
- **GitHub** – for structuring the project (like any good analyst should)

---

## Roadmap

- [x] Simulate realistic e-commerce data
- [ ] Write SQL queries for product funnels, conversion rates, and retention
- [ ] Explore user behavior by location and category
- [ ] Visualize insights in clean, business-ready formats
- [ ] Bonus: deploy a simple dashboard (Streamlit or Looker Studio)

---

## About the Author

**Sacha Brouck**  
Incoming MSBA student @ University of Washington – Foster School of Business  
Former startup founder, real estate investment analyst, and data enthusiast  
Exploring the intersection of **analytics, business impact, and purpose**

> "As we say in France — rigueur et clarté avant tout."

[LinkedIn](https://www.linkedin.com/in/sacha-brouck)

---

## License

This project is open for learning and collaboration purposes.
Feel free to fork it, use it, or improve it.
