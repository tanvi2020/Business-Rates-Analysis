# Business Rates Analysis 🏢📊
Project Overview 📌
This project analyzes business properties liable to non-individuals in the UK. The dataset includes information on property addresses, descriptions, rateable values (RV), liable parties, empty properties, and rate reliefs. The goal of this analysis is to identify trends in property values, types, and locations while also evaluating the impact of reliefs and vacancy rates.

Dataset Information 📂
Source: UK Government Data

## Key Columns:
🏠 Property Address: Location of the business property.
📑 Description: Type of commercial property.
💰 Rateable Value (RV): The yearly rental value of the property.
👥 Liable Party: Entity responsible for the property.
🚪 Empty Property Information: Indicates if the property is vacant.
🎟️ Rate Relief: Details on reliefs applied to the property.

## Data Cleaning & Preprocessing 🧹⚙️
1. Checked for Null Values ❌ Used df.info() to identify missing data
2. Checked Column Relevance ✅ All columns were deemed relevant for analysis.
3. Checked for Duplicates 🔄 Ensured no duplicate rows were present.
4. Checked Data Types 🏷️ Verified and corrected data types where necessary.
5. Handled Skewness 📊 Applied log transformation to RV values to normalize distribution.

## Analysis Goals 🎯
Goal 1: Understand trends in property usage, values, and types. 🏢📈
Goal 2: Evaluate rate relief distribution and its impact on property values. 🎟️📊
Goal 3: Analyze vacant properties and identify vacancy patterns. 🚪🔍
Goal 4: Examine the relationship between property values, location, and property type. 📍💰

## Key Findings 🔍📊
🏬 Property Type Trends: High-value properties include Wind Farm and Premises 🌬️ and Superstore and Premises 🏬, while low-value properties include Properties in Disrepair 🏚️ and Property Beyond Economic Repair 🏗️.
💰 Rateable Value (RV) Analysis:
RV data was initially skewed but became more uniform after log transformation. 📊
Large commercial properties generally have higher RV values. 🏢
Properties under reconstruction or beyond repair tend to have zero or low RV values. 🏚️

🎟️ Rate Relief Correlation:
Mandatory Relief and Small Business Rate Relief showed weak correlation with RV values. 🤔
This indicates that relief policies do not significantly impact property valuations. 📉

🚪 Vacancy Rate:
Only 15.3% of properties were vacant, suggesting a strong demand for commercial properties. 📈
Policies could be improved to support struggling property types. 🏗️

Future Scope 🚀
📍 Deeper analysis of location-based property trends.
🤖 Predictive modeling to forecast rateable values using Machine Learning.
📊 Policy evaluation to recommend improvements for underperforming property categories.
