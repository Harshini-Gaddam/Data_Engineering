# iPhone Analysis Project
This project provides a comprehensive analysis of Apple iPhone products, focusing on pricing trends, ratings, reviews, and product specifications. The data has been processed and analyzed to uncover insights that can help in understanding product performance and market dynamics.

### Features
#### 1. Database Structure
- A dedicated schema, Iphone_analysis, was created to store and organize iPhone-related data.
- The apple_products table contains rich data attributes including product names, pricing, discounts, ratings, reviews, and technical specifications.
#### 2. Data Insights
- Key Metrics:
   - Calculated average, maximum, and minimum prices (MRP) for iPhone products.
   - Determined the count of total products in the dataset.
- Advanced Filtering:
   - Extracted high-rated products with RAM > 4GB and Star Rating > 4.5.
   - Identified product trends based on pricing and discount percentage.
#### 3. New Column Additions
- iPhone Version:
   - Extracted and stored iPhone versions based on product naming conventions.
- Memory Storage:
   - Parsed product descriptions to identify and store memory capacity.
#### 4. Transformations
- Parsed product names to extract key details like version and storage capacity.
- Updated the dataset to include enhanced metadata for better categorization and analysis.
  
###Key Queries/Operations
- Generated high-level statistics such as:
   - Average MRP of all products.
   - Maximum and minimum prices across the dataset.
- Implemented advanced filtering to identify high-performing products based on RAM and ratings.
### Use Case Examples
- Market Research:
   - Gain insights into pricing trends and discounts to inform marketing strategies.
- Product Analysis:
   - Understand consumer preferences through ratings and reviews.
- Inventory Management:
   - Utilize extracted product specifications for better categorization and stock planning.
     
### Project Highlights
- Enhanced data with additional columns for iPhone version and memory storage.
- Leveraged detailed product attributes to generate meaningful insights.
- Built a structured and organized framework for analyzing large datasets of product information.
