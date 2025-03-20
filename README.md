# 20th Century Events Analysis

## 📌 Overview
This project explores key **20th-century historical events** using **Text Mining, NLP, and Network Analysis**. The analysis involves **data scraping, Named Entity Recognition (NER), and community detection** to understand relationships between countries that played a significant role in world history.

## 📂 Project Structure
- **20th_century_scrape.ipynb** – Web scraping historical data from online sources.
- **Data_mining.ipynb** – Preprocessing, tokenization, stopword removal, and POS tagging.
- **NER_Network_Analysis.ipynb** – Named Entity Recognition (NER) to extract country relationships.
- **Network_Visualizations.ipynb** – Building and analyzing network graphs for country connections.
- **community_network.html** – Interactive **network graph** showing detected communities.
- **centrality_measures.csv** – File containing calculated centrality scores.

## 🔎 Key Steps & Methods
### **1. Data Collection (Web Scraping)**
- Scraped a **detailed historical article** on 20th-century events.
- Cleaned the text, removing unnecessary formatting.

### **2. Text Mining & Preprocessing**
- **Tokenized** the text and identified the **10 most common words**.
- Removed **stopwords** and analyzed **Parts of Speech (POS)**.
- Extracted **frequent country mentions** to identify significant nations.

### **3. Named Entity Recognition (NER) & Relationship Mapping**
- Used **spaCy** to extract country names from text.
- **Standardized country names** (e.g., "USA" → "United States").
- Created a **relationship dataframe** showing country interactions.

### **4. Network Analysis & Community Detection**
- Built a **network graph** using **NetworkX** and **PyVis**.
- Applied the **Leiden Algorithm** to detect **historical alliances & rivalries**.
- Calculated **centrality measures** (Degree, Betweenness, Closeness) to identify influential nations.

## 🌍 Key Findings & Insights
- **Frequent Mentions:** The **United States, Germany, Russia, and Japan** dominated historical discussions.
- **Community Detection:** The graph revealed distinct **alliances**, such as **World War II Allies & Axis Powers**.
- **Network Influence:** The **United States and Russia** had high **betweenness centrality**, reinforcing their role as **global superpowers**.
- **Geopolitical Insights:** Countries with **strong historical ties** (e.g., **Germany & France**) had frequent co-occurrences.

## 📈 Visualizations
✔ **[Interactive Community Network](community_network.html)** – A dynamic **network graph** showing relationships between countries.
✔ **POS Tagging Graphs** – Most common **nouns, verbs, adjectives** related to history.
✔ **Centrality Measures CSV** – Insights into **which countries were most influential**.

## 🚀 Next Steps
🔹 Expand NER analysis to **organizations and people** (e.g., UN, NATO, Churchill, Roosevelt).  
🔹 Apply **Sentiment Analysis** to determine **how countries were referenced** (positive/negative tone).  
🔹 Enhance network graphs with **weighted edges** based on co-occurrence frequency.  




