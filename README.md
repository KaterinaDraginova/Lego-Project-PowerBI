

# LEGO Collector Project


![eec2a8a17fc00fbd773fa1fb3b4af779 (1)](https://github.com/user-attachments/assets/23f67082-0c85-40cd-bbe6-7ba19b29a274)





# Project Brief

LEGO collectors often face decision fatigue due to the overwhelming number of options available. 
This Power BI project helps LEGO collectors find their ideal next set by providing an interactive dashboard. Users can explore and filter sets based on key criteria like **theme**, **age range**, **piece count**, and **price**. The goal is to simplify decision-making through a clean, visual, and user-friendly interface that supports personalized exploration.


# Objectives

1. Load and prepare the data (source: [lego_sets.csv](https://github.com/user-attachments/files/20773160/lego_sets.csv))
2. Design the report layout & visuals
3. Add interactive components

# Business Objective 1:

<img width="1259" alt="image" src="https://github.com/user-attachments/assets/fba5e27d-9d7e-45a8-a536-28f76f79311a" />  

⠀

The lego_sets.csv file was cleaned for analysis by removing irrelevant fields (minifigs, bricksetURL, thumbnailURL) and filtering out records missing key data like price, age, pieces, or image URLs. Data types were corrected, and new fields were created to categorize sets by **Age Range** and **Price Range** for easier segmentation.
Key DAX measures were added to track **total sets**, distinct **theme groups**, and **averages for age, price, and piece count** — providing a solid foundation for interactive exploration.
⠀




⠀

# Business Objective 2:
<img width="914" alt="image" src="https://github.com/user-attachments/assets/17074f31-b539-45d8-a3b5-2a50fad587ea" />

⠀

The report layout was carefully structured to guide LEGO collectors through a personalized exploration experience. Card visuals were added to summarize key metrics, including Total Sets, Avg. Pieces, and Avg. Price, providing instant insight. Slicers for Theme Group, Theme, and Age Range were integrated to allow users to filter sets based on their preferences. A detailed table visual was built to display each set’s Name, Set ID, Theme, Age Range, Avg. Pieces, Avg. Price, and Price Range.Dynamic measures were used to ensure that the detail view displays actual values only when a single set is selected



# Business Objective 3:

<img width="909" alt="image" src="https://github.com/user-attachments/assets/068ead95-2a8e-45a0-a40e-3357a944905d" />


⠀



Max Price slicer was created ranging from 0 to 850 in increments of 5, along with a DAX measure to filter the table based on the selected maximum price. Tooltips were enabled to show LEGO set images on hover for better context. A new report page with a decomposition tree visual was developed to analyze Total Sets by Category, Theme Group, Theme, and Name, including navigation buttons for easy page switching.

⠀


<img width="904" alt="image" src="https://github.com/user-attachments/assets/cf034edb-30f7-49b1-82ea-cd74d4f54ad1" />












