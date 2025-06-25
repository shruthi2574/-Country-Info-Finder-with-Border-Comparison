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

4. Run the notebook and follow the prompt  

   
## 💡 Example Output

```
🌐 Country vs Bordering Nations Comparator
Enter a country name (e.g., India): India

🌍 India has 6 bordering country(ies).

🔁 Comparing India vs Nepal
-------------------------------------------------------------------------
Field           | India                     | Nepal
Capital         | New Delhi                 | Kathmandu
Region          | Asia                      | Asia
Population      | 1,407,563,842             | 29,136,808
Area (km²)      | 3,287,263                 | 147,181
Languages       | Hindi, English            | Nepali

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



