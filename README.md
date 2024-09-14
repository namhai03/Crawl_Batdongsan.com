# Crawling Real Estate Data from Batdongsan.com

This project demonstrates how to crawl real estate data from [Batdongsan.com](https://batdongsan.com.vn), one of the largest real estate brokerage websites in Vietnam. It scrapes property information such as price, area, location, and other property details for data analysis or other use cases.

## Overview

Crawling real estate data can provide insights into market trends, pricing, and availability. This project uses Python and libraries such as `Selenium`,`pandas` to scrape data from Batdongsan.com.  
I have tested Hung Yen real estate. If you need to change the area, please follow the Instructions.  

You can also access my analysis of the data [here]().
### Features

- Extract the following property details from Batdongsan.com:
  - **Link**: URL of the property listing.
  - **Tiêu đề**: The title of the property listing.
  - **Địa chỉ**: The full address of the property.
  - **Mức giá**: The total price of the property.
  - **Giá/m²**: Price per square meter.
  - **Số phòng ngủ**: The total number of bedrooms in the property.
  - **Huyện**: The district where the property is located.
  - **Diện tích**: Total area of the property in square meters (sqm).
  - **Mặt tiền**: The width of the property's frontage.
  - **Đường vào**: The width of the entrance leading to the property.
  - **Hướng nhà**: The direction the house is facing.
  - **Hướng ban công**: The direction of the balcony.
  - **Số tầng**: Total number of floors in the property.
  - **Số nhà vệ sinh**: Total number of toilets in the property.
  - **Pháp lý**: Legal status of the property (e.g., red book, pink book).
  - **Vĩ độ**: Latitude coordinate of the property.
  - **Kinh độ**: Longitude coordinate of the property.
- Export data to a CSV file for analysis.

## Instruction

Before starting, ensure you have the following Python libraries installed:

```bash
pip install selenium undetected-chromedriver numpy pandas
```
Open your Crawl_bds.ipynb file and find the line declaring and change the `base_url` variable. It should look something like this:
``` bash
base_url = "https://batdongsan.com.vn/nha-dat-ban-hung-yen"
```

