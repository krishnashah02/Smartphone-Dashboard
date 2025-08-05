# Smartphone Dashboard

## Overview
The **Smartphone Dashboard** is an interactive Power BI solution designed to analyze smartphone specifications and pricing.  
It helps users compare features, evaluate brand performance, and explore the relationships between pricing, ratings, and key specifications.

## Dataset
**Source:** `Smartphones_cleaned_dataset.csv`  
**Rows:** 980  
**Columns:** 26  

### Key Columns
- **Basic Information:** `brand_name`, `model`, `price`, `rating`
- **Connectivity Features:** `has_5g`, `has_nfc`, `has_ir_blaster`
- **Processor Details:** `processor_brand`, `num_cores`, `processor_speed`
- **Battery & Charging:** `battery_capacity`, `fast_charging_available`, `fast_charging`
- **Memory & Display:** `ram_capacity`, `internal_memory`, `screen_size`, `refresh_rate`
- **Camera Details:** `num_rear_cameras`, `primary_camera_rear`, `num_front_cameras`, `primary_camera_front`
- **Other Features:** `os`, `extended_memory_available`, `extended_upto`, `resolution_width`, `resolution_height`

## Dashboard Features
- **Brand-Level Analysis:** Compare smartphone brands by average price, rating, and specifications.
- **Feature Distribution:** Filter smartphones based on key features (5G, NFC, IR Blaster).
- **Price vs. Performance:** Explore the relationship between price and ratings.
- **Camera & Display Insights:** Analyze resolution, camera specs, and display refresh rates.
- **Filtering & Slicing:** Interactive slicers for brand, processor type, RAM capacity, OS, and price range.
