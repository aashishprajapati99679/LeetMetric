# LeetMetric

LeetMetric is a simple and responsive web application that allows users to check their LeetCode statistics by entering their username. The project fetches data from the LeetCode GraphQL API and displays solved problems, submission statistics, and progress indicators for Easy, Medium, and Hard questions.

## Live Demo

🔗 https://leet-metric-zeta-dun.vercel.app/

## Features

- Search LeetCode users
- Fetch real-time LeetCode statistics
- Circular progress indicators
- Responsive UI design
- Displays:
  - Easy solved questions
  - Medium solved questions
  - Hard solved questions
  - Overall submissions
  - Difficulty-wise submissions
- Username validation using Regex
- Error handling using try-catch

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- GraphQL API
- Fetch API

## Project Structure

```bash
LeetMetric/
│
├── index.html
├── style.css
├── index.js
└── README.md
```

## How It Works

1. User enters a LeetCode username.
2. JavaScript validates the username.
3. A GraphQL API request is sent to LeetCode.
4. User statistics are fetched and displayed dynamically.

## Example Username

You can test the project using:

```bash
lakshay
```

## API Used

LeetCode GraphQL API

```js
https://leetcode.com/graphql/
```

## Screenshots

Add your project screenshots here.

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/LeetMetric.git
```

2. Open the project folder

```bash
cd LeetMetric
```

3. Run the project

Simply open `index.html` in your browser.

## Future Improvements

- Dark/Light mode
- Ranking display
- User profile information
- Contest statistics
- Better animations
- Mobile optimization

## Author

Ashish Prajapati

## License

This project is open-source and free to use.
