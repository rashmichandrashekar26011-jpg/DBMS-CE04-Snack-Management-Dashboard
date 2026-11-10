# DBMS CE-04: Snack Brand & Production Batch Management Dashboard

## Project Overview

This project focuses on developing a relational database management application for managing snack brands, production batches, and packing items.

The application is developed using Python, SQLite, Pandas, and ipywidgets. It provides an interactive dashboard within Jupyter Notebook to insert, delete, validate, and view records.

## Objectives

- Design a relational database with primary and foreign keys.
- Implement relationships between brands, production batches, and packing items.
- Apply `ON DELETE CASCADE` to maintain referential integrity.
- Perform database insertion and deletion operations.
- Implement input validation.
- Display database records through an interactive dashboard.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python 3 | Application development |
| SQLite | Relational database |
| Pandas | Displaying database records |
| ipywidgets | Interactive dashboard |
| Jupyter Notebook | Development environment |

## Database Design

The project consists of three relational tables:

1. **Brands** – Stores snack brand information.
2. **Production Batches** – Stores production batch details associated with brands.
3. **Packing Items** – Stores packing item descriptions and costs associated with production batches.

### Relationship

`Brands (1) → (Many) Production Batches (1) → (Many) Packing Items`

Primary keys, foreign keys, and cascading delete constraints are used to maintain database integrity.

## Key Features

- Automatic sample data insertion when the database is empty.
- Insert Panel to add brands, production batches, and packing items.
- Delete Panel to remove brands, batches, or individual packing items.
- Input validation for blank fields and invalid costs.
- Automatic cascading deletion using foreign keys.
- Four interactive tabs:
  - Combined View
  - Brands
  - Production Batches
  - Packing Items
- Automatic refresh of tables and dropdown selections after database operations.
- Parameterised SQL queries for database operations.

## How to Run the Project

1. Install Python and Anaconda.
2. Open Jupyter Notebook or JupyterLab.
3. Download the `.ipynb` notebook from this repository.
4. Install the required packages if they are not already installed:

   `pip install pandas ipywidgets`

5. Open the downloaded notebook.
6. Run all cells in sequential order.
7. The SQLite database is created automatically when the notebook runs.

## Project Files

- `DBMS_CE04_Report_Public.pdf` – Project report and documentation.
- `Snacks dashboard report DBMS CE-04 .ipynb` – Complete Python implementation.
- `Snacks dashboard report DBMS CE-04 .html` – HTML version of the notebook.

## Conclusion

This project demonstrates the practical implementation of relational database concepts using Python and SQLite. It provides an interactive dashboard for managing snack brands, production batches, and packing items while maintaining data consistency through primary keys, foreign keys, and cascading delete operations.

---

**Course:** Database Management System (DBMS)  
**Course Code:** DSC202A  
**Project:** Continuous Evaluation 4 (CE-04)
