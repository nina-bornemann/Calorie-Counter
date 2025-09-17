## 💥 Calorie Counter

A simple web application to track daily calories. Users can enter foods, snacks, and exercises, calculate remaining calories based on a daily budget, and see surplus or deficit.

---

### 🚀 Features

- Add multiple entries for:
  - Breakfast
  - Lunch
  - Dinner
  - Snacks
  - Exercise
- Dynamically add new entries via dropdown
- Calculate remaining calories based on:
  - Daily calorie budget
  - Consumed calories
  - Calories burned via exercise
- Shows Surplus (over budget) or Deficit (under budget)
- Clear all inputs to start over

---

### Usage

- Open index.html in your browser.
- Enter your daily calorie budget.
- Add foods and exercises using the dropdown and Add Entry button.
- Enter calories for each item.
- Click Calculate Remaining Calories to see the results.
- Click Clear to reset the form.

### 🍜 Example Output
- 1000 Calorie Deficit → under budget
- 200 Calorie Surplus → over budget
- Includes a breakdown of:
  - Budgeted calories
  - Consumed calories
  - Calories burned through exercise

---

### Technologies Used
- HTML5
- CSS3 (via calorie.css)
- JavaScript (calorie.js)
- DOM manipulation and event handling

  
### Notes
- Input validation checks for invalid scientific notation (e.g., 1e3).
- Dynamically adds new input fields without reloading the page.
- Uses simple in-browser memory, no backend or database required.
