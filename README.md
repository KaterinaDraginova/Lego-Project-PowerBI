

# LEGO Collector Project

![LEGO Banner](https://github.com/user-attachments/assets/23f67082-0c85-40cd-bbe6-7ba19b29a274)

---

# Project Brief

LEGO collectors often face decision fatigue due to the overwhelming number of options available.  
This Power BI project helps LEGO collectors find their ideal next set by providing an interactive dashboard.  
Users can explore and filter sets based on key criteria like **theme**, **age range**, **piece count**, and **price**.  
The goal is to simplify decision-making through a clean, visual, and user-friendly interface that supports personalized exploration.

---

# Objectives

1. Load and prepare the data (source: [lego_sets.csv](https://github.com/user-attachments/files/20773160/lego_sets.csv))  
2. Design the report layout & visuals  
3. Add interactive components  

---

# Business Objective 1

The `lego_sets.csv` file was cleaned for analysis by removing irrelevant fields (`minifigs`, `bricksetURL`, `thumbnailURL`) and filtering out records missing key data like price, age, pieces, or image URLs.  
Data types were corrected, and new fields were created to categorize sets by **Age Range** and **Price Range** for easier segmentation.  

Key DAX measures were added to track **Total Sets**, distinct **Theme Groups**, and **averages for age, price, and piece count** — providing a solid foundation for interactive exploration.  

<br>

<img width="1259" alt="Business Objective 1" src="https://github.com/user-attachments/assets/fba5e27d-9d7e-45a8-a536-28f76f79311a" />  

---

# Business Objective 2

<ul>
  <li><span style="font-size:17px"><strong>Card visuals</strong> were added to summarize key metrics, including Total Sets, Avg. Pieces, and Avg. Price, providing instant insight. Slicers for Theme Group, Theme, and Age Range allow users to filter sets based on their preferences.</span></li>
</ul>

<img width="765" alt="Card Visuals" src="https://github.com/user-attachments/assets/e3ecc916-caac-45ad-8315-dbe263ac7bcc" />
<br><br>
<br><br>
<ul>
  <li><span style="font-size:17px"><strong>A detailed table visual</strong> was built to display each set’s Name, Set ID, Theme, Age Range, Avg. Pieces, Avg. Price, and Price Range.</span></li>
</ul>  
<img width="473" alt="Table Visual" src="https://github.com/user-attachments/assets/2f63b025-b05d-413c-9362-0090a5da72cf" />

---

# Business Objective 3

<ul>
  <li><span style="font-size:17px"><strong>A Max Price slicer</strong> was created ranging from 0 to 850 in increments of 5, along with a DAX measure to filter the table based on the selected maximum price.</span></li>
</ul>

<img width="376" alt="Max Price Slicer" src="https://github.com/user-attachments/assets/af99c929-312a-46c1-b454-a8bb964abbf9" />  
<img width="461" alt="Price DAX Measure" src="https://github.com/user-attachments/assets/f2b632ba-1510-4466-84bc-3c5d89732d52" />
<br><br><br>

<ul>
  <li><span style="font-size:17px"><strong>DAX Measures for slicers:</strong> I created several DAX measures like the one below to prevent confusion when users select multiple or no values in slicers. If more than one age is selected—or none at all—the measure returns a dash ("-") instead of listing multiple values. This keeps visuals clean, focused, and easy to interpret.</span></li>
</ul>

<img width="616" alt="Slicer Logic DAX" src="https://github.com/user-attachments/assets/41978f48-b048-4742-a399-e41b7fd4cddb" />  
<br>
<img width="333" alt="Slicer Result" src="https://github.com/user-attachments/assets/2ec1bb7d-7c77-44ab-9040-a938bf9c55a7" />
<br><br><br>

<ul>
  <li><span style="font-size:17px"><strong>A decomposition tree visual</strong> was added on a new report page to break down Total Sets by Category, Theme Group, Theme, and Name. Navigation buttons were added for easy page switching.</span></li>
</ul>

<img width="904" alt="Decomposition Tree" src="https://github.com/user-attachments/assets/cf034edb-30f7-49b1-82ea-cd74d4f54ad1" />
<br><br><br>
<ul>
  <li><span style="font-size:17px"><strong>The final designed dashboard</strong> combines all visuals, slicers, and layout elements into one polished board.</span></li>
</ul>

<img width="998" alt="Final Dashboard" src="https://github.com/user-attachments/assets/5600f15d-ab64-4e4b-b601-9c7a1ba7b50c" />

---












