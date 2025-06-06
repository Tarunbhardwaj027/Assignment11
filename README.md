# Search Dashboard with Debouncing & Throttling

## 🚀 Overview
This project is a search dashboard that optimizes user input handling using **debouncing** and **throttling** techniques. It features real-time search functionality, a scroll-based "Back to Top" button, and a keystroke statistics tracker.

## 📋 Features
- **Real-time Search**: Search within a large list of names.
- **Debounced Input (1s delay)**: Optimizes search queries for better performance.
- **Throttled Scroll Listener (500ms)**: Ensures efficient event handling for UI updates.
- **"Back to Top" Button**: Appears when scrolling down 200px.
- **Typing Statistics**: Tracks total keystrokes and debounced searches.
- **Bonus Enhancements**:
  - Loading indicator during debounce delay.
  - "No results found" message for unmatched queries.
  - Highlighted search matches.

## 🛠 Technologies Used
- HTML, CSS, JavaScript
- Debouncing (`setTimeout`)
- Throttling (`setTimeout` technique)
- Event Listeners (input & scroll)

## 🔧 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name


📂 Project Structure

/project-folder
│── index.html      # Main HTML structure
│── styles.css      # Basic styling
│── script.js       # Core functionality (debouncing, throttling, search)
│── README.md       # Project documentation
