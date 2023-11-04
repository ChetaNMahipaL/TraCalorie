# Tracalorie - Calorie Tracking Web Application

Tracalorie is a web application that allows users to track their daily calorie intake and workouts. It provides features for adding meals and workouts, setting calorie limits, tracking calorie consumption, and more. The application uses JavaScript and localStorage for data storage.

## Features

### 1. Calorie Tracking
   - **Add Meals**: Users can add meals with names and calorie counts.
   - **Add Workouts**: Users can add workouts with names and calorie counts.
   - **Remove Items**: Users can delete meals and workouts from their tracking list.
   - **Total Calorie Count**: The application keeps a running total of consumed and burned calories.
   - **Calorie Limit**: Users can set a daily calorie limit to track their progress.

### 2. Data Persistence
   - Data is stored locally using the browser's `localStorage` to ensure that user data is retained across sessions.
   - Data for meals, workouts, total calories, and calorie limit are stored and retrieved.

### 3. User Interface
   - The user interface displays the total calories consumed, total calories burned, remaining calories, and progress bar.
   - Items are displayed in separate sections for meals and workouts, making it easy for users to manage their calorie intake.

### 4. Filtering
   - Users can filter their meal and workout lists using a search input. This helps users find specific items quickly.

### 5. Reset
   - A reset feature is available to clear all tracking data, providing users with a fresh start.

## Usage

1. Open the Tracalorie web application in a browser.
2. Start tracking your daily meals and workouts:
   - Use the "Add Meal" form to enter meal details.
   - Use the "Add Workout" form to enter workout details.
   - Use the "Delete" button to remove items from your tracking list.
3. Set your daily calorie limit by using the "Set Limit" form.
4. Monitor your calorie consumption, calorie burn, and progress using the displayed statistics.
5. Use the search filters to find specific items in your tracking list.
6. To start over or clear all data, click the "Reset" button.

## Technologies Used

- HTML
- CSS
- JavaScript
- Bootstrap (for modals and UI components)

## Installation

1. Clone the repository or download the project files to your local machine.
2. Open the `index.html` file in a web browser.
