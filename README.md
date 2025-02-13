# JavaScript Asynchronous Programming Assignment

## Overview
This assignment demonstrates various asynchronous programming techniques in JavaScript, including **Callbacks**, **Promises**, and **Async/Await**. Each technique is implemented with a simple button click event, data fetching from an external API, and proper UI/UX design using HTML and CSS.

---

## Table of Contents
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Features](#features)
  - [Callbacks](#callbacks)
  - [Promises](#promises)
  - [Async/Await](#asyncawait)
- [Installation and Usage](#installation-and-usage)
- [Screenshots and Recordings](#screenshots-and-recordings)
- [Credits](#credits)

---

## Project Structure
```
.
├── callbacks.html
├── promises.html
├── async-await.html
├── styles.css 
├── README.md
└── screenshots/ (folder for images and recordings)
```

---

## Technologies Used
- **HTML5**
- **CSS3**
- **JavaScript** (ES6+)

---

## Features

### Callbacks
- A button triggers a callback function with a 5-second delay.
- A loading animation is shown during the delay.
- After 5 seconds, the message "Callback executed after 5 seconds" is displayed.
- Data from [JSONPlaceholder API](https://dummyjson.com/posts) is fetched and displayed in a well-structured container.

### Promises
- A button initiates a Promise that resolves after 5 seconds.
- A loading animation and message are displayed while the Promise is pending.
- After 5 seconds, the fetched data from [JSONPlaceholder API](https://dummyjson.com/posts) is displayed.

### Async/Await
- A button triggers an asynchronous function using the `async/await` syntax.
- A loading animation and message are shown during data fetching.
- The fetched data is displayed in a formatted container once the data is received.

---

## Installation and Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/harshal1800/async-ass.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd async-ass
   ```

3. **Open the Files in a Browser:**
   - Open `callbacks.html`, `promises.html`, or `async-await.html` directly in any modern browser (e.g., Chrome, Firefox).

4. **Interact with the Buttons:**
   - Click the buttons to observe the respective asynchronous operations and data fetching in action.

---

## Screenshots and Recordings
### Screenshots
![Callbacks Screenshot]  ![ss](<ss and screen rec/callback ss1.png>) , ![ss](<ss and screen rec/callback ss2.png>)
![Promises Screenshot]   ![ss](<ss and screen rec/promises ss1.png>)  , ![ss](<ss and screen rec/promises ss2.png>)
![Async/Await Screenshot]  ![alt text](<ss and screen rec/aysnc-await ss.png>)

### Screen Recording
[Screen Recording of the Project](ss and screen rec/async sr1.mp4)

---

## Credits
- **Instructor/Guidance:** For providing the project requirements.
- **[JSONPlaceholder](https://dummyjson.com/posts):** Used for simulating API responses.
- **CSS Styling:** Default animations and button designs inspired by modern UI trends.

---

## License
This project is open-source and available under the MIT License.

---

## Feedback
Feel free to open issues or submit pull requests for improvements! 😊

