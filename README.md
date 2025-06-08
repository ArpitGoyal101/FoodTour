# FoodTour

# 🍽️ AI-Powered Foodie Tour Planner

This project leverages intelligent agents to curate a personalized foodie tour for a list of cities using live weather, local dishes, and restaurant data. Built using the **Julep AI platform**, it generates a delightful single-day meal itinerary considering real-world conditions.

## 💡 Objective

For each city in a provided list, the workflow:

- Checks current weather and suggests **indoor** or **outdoor** dining.
- Identifies **3 iconic local dishes**.
- Finds **top-rated restaurants** serving those dishes.
- Crafts a **breakfast-lunch-dinner foodie narrative** tailored to the weather and local flavors.

## 🧠 Technologies Used

- 🤖 **Julep AI Agents** for modular logic (weather check, dish finder, restaurant locator, itinerary builder)
- 🧠 **GPT-4o model** for intelligent narrative creation
- 🌐 Real-time APIs accessed via Julep for weather and local recommendations

## 📦 Features

- Dynamic dining suggestions: *indoor* or *outdoor*
- City-specific dish discovery
- Restaurant ranking and filtering
- Daily narrative-based meal plan

## 🛠️ Project Flow

1. **Weather Agent**  
   Classifies cities as suitable for *indoor* or *outdoor* dining based on live weather.

2. **Dish Agent**  
   Lists three authentic and popular dishes for each city.

3. **Restaurant Agent**  
   Searches for top-rated restaurants (using external data sources via Julep).

4. **Tour Builder Agent**  
   Constructs a human-friendly foodie itinerary for the day:
   - 🥐 Breakfast
   - 🍛 Lunch
   - 🍲 Dinner

## 📂 Notebook Structure

The logic is implemented step-by-step in the Jupyter Notebook:
- Agent creation and configuration
- City-wise API calls
- Aggregation of dishes and restaurants
- Final itinerary generation

## ✅ Future Enhancements

- Add price and cuisine filters for restaurant selection
- Multilingual narration
- Map-based routing for walkable food tours

## 📁 Files

- `JulepAIProject.ipynb` — Main implementation notebook
- `README.md` — Project overview (this file)
