
# 🍎 Calorie Counter Web App

A simple **Calorie Counter** web application that helps users track their daily calorie intake and exercise, giving a clear view of remaining calories, surplus, or deficit.

## Features

- Add multiple **food and exercise entries** per category:
  - Breakfast, Lunch, Dinner, Snacks, Exercise
- Automatically **calculate remaining calories**
- Highlight **surplus or deficit** calories in color
- Clear form to reset all entries
- Responsive design for mobile and desktop
- Modern and colorful UI with animated background

## Usage

1. Enter your daily calorie budget.
2. Use the dropdown menu to select a category (Breakfast, Lunch, Dinner, Snacks, Exercise).
3. Click "Add Entry" to add inputs for food or exercise.
4. Enter the **name** and **calories** of each entry.
5. Click "Calculate Remaining Calories" to see results.

## Technologies

- **HTML5** - structure of the app
- **CSS3** - modern styling, gradients, hover effects
- **JavaScript (ES6)** - dynamic addition of inputs and calculation logic

## Code Structure

- `index.html` - main HTML file  
- `styles.css` - styling for layout, colors, and animations  
- `script.js` - contains all JavaScript functions:
  - `addEntry()` → dynamically adds input fields  
  - `calculateCalories()` → calculates remaining calories  
  - `getCaloriesFromInputs()` → parses user input and handles errors  
  - `clearForm()` → resets form and output  

## Contributing

Contributions are welcome! You can help by:

- Adding new UI themes
- Enhancing validation logic
- Improving accessibility

## License

MIT License © 2026
