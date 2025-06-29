# CS-340 Project Reflection – Dylan Miller

## Writing Maintainable, Readable, and Adaptable Code

To ensure my programs are maintainable and adaptable, I focused on writing modular and well-documented code. This was especially evident in my custom Python CRUD module developed in Project One. By separating database interaction logic into its own class, I was able to cleanly connect it to the dashboard components in Project Two without rewriting queries or handling connections repeatedly.

This modular approach allowed for:
- Reusability across different parts of the dashboard
- Easier debugging and testing
- Clearer separation of concerns between data access and UI logic

In future projects, this CRUD module could be reused in other MongoDB-backed applications or extended to support different data validation rules or additional operations like aggregation pipelines.

---

## Approaching Problems as a Computer Scientist

For this project, I approached the problem with an engineering mindset: identify the client’s goals (Grazioso Salvare’s need to quickly evaluate animals for search-and-rescue), design tools to visualize and filter relevant data, and build reusable, scalable components.

Compared to previous courses that may have emphasized isolated algorithms or smaller scripts, this project required me to integrate:
- Database design and queries (MongoDB + pymongo)
- Interactive UI development (Dash + Plotly)
- Data cleaning and transformation (pandas)

This full-stack integration forced me to think holistically about data flow, user experience, and edge-case handling. In future client projects, I’ll apply this same modular, layered approach to ensure clarity and flexibility from the start.

---

## What Computer Scientists Do – and Why It Matters

Computer scientists solve real-world problems by designing and building digital systems that are robust, user-centered, and data-driven. This project helped demonstrate how a technical tool (a dashboard) could support a real organization, Grazioso Salvare, by:

- Filtering shelter animal records for traits relevant to different rescue types
- Visualizing breed distribution to help staff make training decisions
- Mapping animal locations to coordinate logistics or field teams

In essence, this dashboard streamlines operations and enables more informed decisions — a key outcome for any software product. Projects like this show how thoughtful programming can translate data into real-world action.

---

## Technologies Used

- **Python** – Primary development language
- **MongoDB** – Flexible NoSQL database for animal records
- **Dash & Plotly** – Framework for building the dynamic dashboard UI
- **Dash Leaflet** – For rendering interactive maps
- **JupyterDash** – Used for development and testing in a notebook environment
- **pandas** – For transforming MongoDB data into tabular format

---

## Highlights

- Built a CRUD module for clean MongoDB interaction
- Developed a dynamic dashboard with charting and geolocation
- Resolved common issues with callback errors, missing data, and data type mismatches
- Designed UI elements that update reactively and enhance decision-making

---

## Future Applications

The architecture and techniques used here can be adapted for any organization needing a live data dashboard — whether that’s logistics, medical data, inventory tracking, or personnel analytics. With modularity and a clean interface, it becomes easy to plug in new datasets and deliver insights efficiently.

---
