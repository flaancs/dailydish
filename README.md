Wrap
Copy

# DailyDish

DailyDish is a simple yet powerful web application that generates personalized daily meal plans tailored to your available ingredients and desired calorie target. Whether you're aiming to hit a specific caloric goal or make the most of what’s in your pantry, DailyDish has you covered.

## Features

- **Ingredient Management**: Add, edit, and remove ingredients with a user-friendly interface. Ingredients are saved in `localStorage` for persistence.
- **Custom Calorie Target**: Set your desired daily calorie goal, stored locally and used to generate precise meal plans.
- **OpenAI Integration**: Utilizes the OpenAI `gpt-4o-mini` model to create balanced meal plans (proteins, fats, carbs) using only your specified ingredients.
- **API Key Input**: Securely input and store your OpenAI API key in `localStorage` for seamless API calls.
- **Last Plan Persistence**: The most recent meal plan is saved and displayed on page refresh.
- **Ingredient Validation**: Highlights any ingredients in the meal plan not matching your list, ensuring transparency.
- **User Experience**: Includes loading states, error messages in Spanish, and Enter key support for adding ingredients.
- **Responsive Design**: Clean, modern UI with a focus on usability, built with HTML and CSS.
