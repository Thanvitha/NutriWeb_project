# NutriWeb – Smart & Sustainable Food Choices

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

## NutriWeb

NutriWeb is an intelligent food recommendation platform designed to enhance dietary choices by providing **personalized insights, transparency, and sustainability tracking**. Unlike existing apps that offer generic ratings, NutriWeb tailors recommendations based on **BMI, allergies, and dietary goals**, while also highlighting the **environmental impact** of food choices.

### **Problem Statement:**
Current nutrition apps **lack clarity, personalization, and sustainability awareness**:
- **Confusing information:** Complex ingredient lists make it hard to understand nutritional values.
- **Lack of personalization:** Generic health scores fail to consider individual dietary needs.
- **Environmental ignorance:** Most apps overlook the carbon footprint and eco-impact of food choices.

### **Solution: NutriWeb’s Unique Approach**
NutriWeb integrates **AI-driven nutrition analysis, visual comparisons, and context-aware insights** to help users make **smarter food choices**:
- **Personalized nutrition** based on user profiles (BMI, allergies, health goals).
- **Ingredient transparency** with easy-to-understand visual comparisons.
- **Sustainability tracking** to highlight a product’s carbon footprint.

## Dataset
1) **Open Food Facts:** Crowdsourced database with 3M+ food products.

The dataset can be accessed [here](https://drive.google.com/file/d/1SrVPakdOvOkUEsJekmsl9786MrxWXH0g/view?usp=sharing).

A food products database
Open Food Facts is a free, open, collaborative database of food products worldwide, with ingredients, allergens, nutrition facts and all the tidbits of information we can find on product labels.

Made by everyone
Open Food Facts is a non-profit association of volunteers.
5000+ contributors like you have added 600 000+ products from 150 countries using our Android, iPhone or Windows Phone app or their camera to scan barcodes and upload pictures of products and their labels.

For everyone
Data about food is of public interest and has to be open. The [complete database](https://world.openfoodfacts.org/data) is published as open data and can be reused by anyone and for any use. Check out the cool reuses or make your own!

Dataset structure
The dataset contains a single table, FoodFacts, in a tab-separated form in en.openfoodfacts.org.products.tsv 

A brief explanation of the columns in our dataset is provided below:

- code: Barcode of the product.
- creator: Contributor who first added the product
- created_t: Date that the product was added in UNIX format.
- last_modified_t: Date that the product page was last modified.
- product_name: Name of the product.
- generic_name: A generic description of the product.
- quantity: The amount of product in the packaging with unit.
- packaging: Information about packaging material.
- brands: Product’s brand name.
- categories: Product categories like groceries, and biscuits.
- origins: Origins of ingredients.
- manufacturing_places: Locations where the product was manufactured.
- labels: Certifications or labels of the product.
- emb_codes: Official manufacturing site codes.
- purchases_places: Locations where the product can be purchased.
- stores: Retail stores that carry the product.
- countries: list of countries where the product is sold.
- ingredients_text: List of ingredients used in the product.
- allergens: Known allergens present in the product.
- nutriments: Nutritional information per serving.
- additives_n: Number of food additives in the product.
- ingredients_from_palm_oil_n: Number of ingredients made from palm oil.
- nutrition-score-fr_100g: Nutri-Score - Nutrition score derived from the UK FSA score and adapted for the French market (formula defined by the team of Professor Hercberg).
- biotin_100g: also known as Vitamine B8.
- pantothenic-acid_100g: also known as Vitamine B5.

and, you can access the complete information on the different fields [here](https://static.openfoodfacts.org/data/data-fields.txt).

2) **NHANES Data:** U.S. health demographics to train personalized models.
- ***link for the dataset: https://www.kaggle.com/datasets/ziya07/diet-recommendations-dataset?resource=download ***

3) **Non-GMO Database:** Identifies GMO-containing products.
- ***link for the dataset: https://world.openfoodfacts.org/data , https://www.nongmoproject.org/find-non-gmo/ ***


<!-- GETTING STARTED -->
## Getting Started

### Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install fuzzywuzzy
```
```bash
pip install rapidfuzz
```

## License

[Open Food Facts](https://world.openfoodfacts.org/data)
