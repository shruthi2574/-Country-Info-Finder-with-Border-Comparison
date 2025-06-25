# 🌐 Country Info Finder with Border Comparison


A simple and interactive Python application that allows users to compare any country with its neighboring countries. Using the REST Countries API, this project fetches live data such as population, capital, area, region, and official languages and presents it in a side-by-side comparison format.

---

## 🔍 Features

- 🌍 Fetch country data using name input  
- 🔁 Automatically retrieves and compares bordering countries  
- 📊 Displays fields like capital, region, population, area, and languages  
- ⚠️ Gracefully handles island nations or those without borders  
- 💡 No API key required – uses open-source RESTCountries API

---

## 🛠️ Tech Stack

| Tool         | Purpose                                    |
|--------------|--------------------------------------------|
| Python       | Core programming language                  |
| `requests`   | For making HTTP requests to REST API       |
| RESTCountries API | To fetch real-time country information |

---

## 🚀 How to Run
1. Open Google Colab
👉 https://colab.research.google.com/

2. Create a new notebook.

3. Paste the code into a code cell and run it.

4. Run the notebook and follow the prompt. 

   
## 💡 Example Output

```
🌐 Country vs Bordering Nations Comparator
Enter a country name (e.g., India): india
🌍 India has 6 bordering country(ies).

🔁 Comparing India vs Bangladesh
---------------------------------------------------------------------------
Field           | India                     | Bangladesh               
Capital         | New Delhi                 | Dhaka                    
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 164,689,383              
Area (km²)      | 3,287,590                 | 147,570                  
Languages       | English, Hindi, Tamil     | Bengali                  

🔁 Comparing India vs Bhutan
---------------------------------------------------------------------------
Field           | India                     | Bhutan                   
Capital         | New Delhi                 | Thimphu                  
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 771,612                  
Area (km²)      | 3,287,590                 | 38,394                   
Languages       | English, Hindi, Tamil     | Dzongkha                 

🔁 Comparing India vs Myanmar
---------------------------------------------------------------------------
Field           | India                     | Myanmar                  
Capital         | New Delhi                 | Naypyidaw                
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 54,409,794               
Area (km²)      | 3,287,590                 | 676,578                  
Languages       | English, Hindi, Tamil     | Burmese                  

🔁 Comparing India vs China
---------------------------------------------------------------------------
Field           | India                     | China                    
Capital         | New Delhi                 | Beijing                  
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 1,402,112,000            
Area (km²)      | 3,287,590                 | 9,706,961                
Languages       | English, Hindi, Tamil     | Chinese                  

🔁 Comparing India vs Nepal
---------------------------------------------------------------------------
Field           | India                     | Nepal                    
Capital         | New Delhi                 | Kathmandu                
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 29,136,808               
Area (km²)      | 3,287,590                 | 147,181                  
Languages       | English, Hindi, Tamil     | Nepali                   

🔁 Comparing India vs Pakistan
---------------------------------------------------------------------------
Field           | India                     | Pakistan                 
Capital         | New Delhi                 | Islamabad                
Region          | Asia                      | Asia                     
Population      | 1,380,004,385             | 220,892,331              
Area (km²)      | 3,287,590                 | 881,912                  
Languages       | English, Hindi, Tamil     | English, Urdu            


```

---

## 📂 Project Structure

```
country-comparator/
├── country_comparator.py
└── README.md
```

---

## 🙋‍♀️ Author

**Gugulothu Shruthi**  
B.Tech, 3rd Year — Narayanamma Institute of Technology  
✉️ [gugulothushruthi@gmail.com](mailto:gugulothushruthi@gmail.com)

---



