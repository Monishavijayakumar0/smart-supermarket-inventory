# Smart Supermarket Inventory & Shelf Space Optimization

## Project Overview

This project analyzes supermarket inventory to identify products that need restocking, calculate suggested order quantities, and estimate shelf-space utilization.

The goal is to support better inventory management, reduce the risk of stockouts, and use available shelf space efficiently.

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI (for future dashboard development)

## Project Features

### 1. Inventory Analysis
- Calculate total products and stock units.
- Compare current stock with reorder levels.
- Identify products that need restocking.

### 2. Reorder Planning
- Analyze weekly product sales.
- Calculate suggested order quantities.
- Support inventory replenishment decisions.

### 3. Shelf-Space Optimization
- Calculate product area using product dimensions.
- Estimate total shelf area required.
- Calculate shelf utilization and unused space.
- Estimate the number of shelves required.

### 4. Data Visualization
- Shelf space required by product.
- Current stock versus reorder level.
- Used versus unused shelf space.

## Sample Results

The current sample dataset contains:

- **Total products:** 6
- **Total stock units:** 121
- **Products requiring reorder:** 3
- **Suggested total order quantity:** 140 units
- **Estimated shelf utilization with 6 shelves:** 87.75%

Products identified for restocking include milk, bread, and cereal.

## Shelf-Space Assumptions

Each shelf is assumed to be 120 cm long and 40 cm deep.

The calculations use product dimensions and current stock quantities. The model assumes a single layer of products and does not account for gaps, packaging orientation, or other practical shelf constraints.

## Project Structure

- `data/` — Inventory dataset
- `notebooks/` — Jupyter Notebook analysis
- `outputs/` — Charts and results
- `powerbi/` — Power BI files

## Limitations

This project uses a small sample dataset for demonstration. The results and recommendations should be validated using real supermarket inventory, sales data, and shelf measurements.

## Author

Monisha Vijay Kumar