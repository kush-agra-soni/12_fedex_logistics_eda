# FedEx Logistics EDA

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a FedEx logistics dataset. The dataset includes detailed information about various shipments, such as project codes, shipment modes, product details, freight costs, and more.

The goal of this project is to uncover patterns and insights within the dataset, which can potentially optimize logistics processes and improve decision-making.

## Dataset Information

The dataset contains 10,324 entries and 33 columns, with key details such as:

- **Shipment Information**: Project code, shipment mode, shipment dates, and delivery dates.
- **Product Information**: Product group, brand, dosage form, item description, and more.
- **Logistics Information**: Weight, freight costs, insurance costs, and manufacturing site details.
  
### Columns in the Dataset:
1. `ID`: Unique identifier for each entry
2. `Project Code`: Code associated with the logistics project
3. `PQ #`: Purchase order number
4. `PO / SO #`: Sales order number
5. `ASN/DN #`: Advanced shipment notice number
6. `Country`: Country of the shipment
7. `Managed By`: Person or team managing the shipment
8. `Fulfill Via`: Method used to fulfill the shipment
9. `Vendor INCO Term`: Vendor shipping terms
10. `Shipment Mode`: Mode of shipment (e.g., air, sea, land)
11. `PQ First Sent to Client Date`: Date when PQ was first sent to the client
12. `PO Sent to Vendor Date`: Date when PO was sent to the vendor
13. `Scheduled Delivery Date`: Scheduled delivery date for the shipment
14. `Delivered to Client Date`: Actual delivery date
15. `Delivery Recorded Date`: Date when the delivery was recorded
16. `Product Group`: Group under which the product is categorized
17. `Sub Classification`: Subcategory of the product group
18. `Vendor`: Vendor supplying the product
19. `Item Description`: Description of the item
20. `Molecule/Test Type`: Type of molecule or test associated with the item
21. `Brand`: Brand name of the product
22. `Dosage`: Dosage of the item (some missing values)
23. `Dosage Form`: Form of dosage (tablet, liquid, etc.)
24. `Unit of Measure (Per Pack)`: Units per pack
25. `Line Item Quantity`: Quantity of items in the shipment
26. `Line Item Value`: Monetary value of the line item
27. `Pack Price`: Price per pack
28. `Unit Price`: Price per unit
29. `Manufacturing Site`: Location where the product is manufactured
30. `First Line Designation`: Designation of the first line
31. `Weight (Kilograms)`: Weight of the shipment (some missing values)
32. `Freight Cost (USD)`: Cost of shipping in USD
33. `Line Item Insurance (USD)`: Insurance cost for the shipment

### Missing Data:
- `Shipment Mode`: 60 missing values
- `Dosage`: 736 missing values
- `Line Item Insurance (USD)`: 287 missing values
- `Weight (Kilograms)`: Missing data for some entries
- `Freight Cost (USD)`: Missing values for some shipments

## Steps Involved in the EDA

1. **Data Cleaning**: Handle missing values, outliers, and incorrect data types.
2. **Data Visualization**: Create visualizations to understand trends, patterns, and correlations.
3. **Descriptive Statistics**: Analyze key statistics such as mean, median, standard deviation, etc.
4. **Exploratory Analysis**: Investigate relationships between different columns, focusing on shipment modes, cost analysis, and product details.
5. **Insights and Recommendations**: Provide insights to optimize logistics processes.

## Tools & Libraries Used
- **Pandas**: Data manipulation and analysis
- **Matplotlib** & **Seaborn**: Data visualization
- **NumPy**: Numerical operations
- **Jupyter Notebook**: For running and documenting the analysis

## Installation

To get started with this project, clone the repository and install the required libraries:

```bash
git clone https://github.com/yourusername/fedex-logistics-eda.git
cd fedex-logistics-eda
pip install -r requirements.txt
```

## License
This project is licensed under the MIT License - see the LICENSE file for details.
