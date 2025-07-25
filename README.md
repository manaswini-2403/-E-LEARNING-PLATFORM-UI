Below is a concise and professional `README.md` file description for your e-learning platform project, designed for uploading to GitHub. This version focuses solely on the project itself, omitting references to CODTECH IT Solutions or the internship context, as per your request. It describes the project’s purpose, features, and setup instructions based on the React-based `index.html` code with your specified modifications (light pink color scheme, "Codtech Solutions" name, six courses with Free/Paid labels, larger course cards, navbar animations, "Mark Complete" navigation, and "Continue" buttons in the dashboard).

---

# E-Learning Platform

This is a responsive e-learning platform named **Codtech Solutions**, built to provide an interactive and elegant interface for users to explore, enroll in, and track progress for online courses. The platform features a light pink color scheme, a modern design with hover animations, and a user-friendly experience, developed using React and embedded Tailwind CSS.

## Features
- **Course Listing**: Displays six courses (Python, React, Data Science, Machine Learning, JavaScript, SQL) with titles, descriptions, progress bars, and Free/Paid labels.
- **Progress Tracking**: Visual progress bars showing completion percentages (50%, 25%, 75%, 10%, 40%, 20%) for each course.
- **Video Embedding**: Embedded YouTube videos for course content in the course detail view.
- **Search Functionality**: Filter courses by title using a search bar.
- **Mock Authentication**: Login/logout toggle with a personalized welcome message for logged-in users.
- **Interactive Elements**:
  - "Enroll" button to toggle enrollment status, triggering a confirmation modal with a fade-in animation.
  - "Mark Complete" button in course details to set progress to 100% and return to the main page.
  - "Continue" button in the dashboard to resume courses easily.
- **Responsive Design**: Adapts to all screen sizes with a grid layout (1-4 columns based on screen width).
- **Elegant Styling**: Light pink color scheme (`#fce7f3`, `#f9a8d4`) with the `Inter` font and navbar link hover animations (scale-up effect).

## Technologies Used
- **React 18**: For dynamic, component-based UI rendering.
- **Tailwind CSS**: Embedded utility classes for styling.
- **Babel**: For in-browser JSX transformation.
- **JavaScript/HTML**: Core structure and interactivity.
- **Google Fonts**: `Inter` font for modern typography.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge).
- Internet connection (for CDNs and YouTube videos).
- Python 3.x (for running a local server).

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/manaswini-2403/elearning-platform.git
   cd elearning-platform
   ```

2. **Save the Code**:
   - Place the provided `index.html` file in the repository folder.

3. **Run a Local Server**:
   - Start a local server using Python:
     ```bash
     python -m http.server 8000
     ```
   - Open `http://localhost:8000` in your browser.

### Project Structure
```
elearning-platform/
├── index.html       # Main file containing React components and embedded CSS
└── README.md        # Project documentation
```

### Usage
- **Home Page**: Welcomes users to "Codtech Solutions" with a light pink background.
- **Courses Section**: Browse six courses with a search bar, enroll, and view options. Each course displays Free/Paid status.
- **Course Detail**: Watch course videos, track progress, and mark courses as complete (returns to the main page).
- **Dashboard**: View all courses with progress bars and "Continue" buttons to resume learning.
- **Login/Logout**: Toggle to simulate authentication and display a welcome message.
- **Search**: Filter courses by typing in the search bar.
- **Enrollment**: Enroll in courses with a confirmation modal.

## Screenshots
*(Add screenshots here for the home page, courses section, dashboard, course detail, and modal. Use tools like Snipping Tool or browser extensions to capture images.)*

## Troubleshooting
- **Blank Page**:
  - Open the browser console (F12 > Console) to check for errors.
  - Verify CDNs are loading:
    - https://unpkg.com/react@18.2.0/umd/react.production.min.js
    - https://unpkg.com/react-dom@18.2.0/umd/react-dom.production.min.js
    - https://unpkg.com/@babel/standalone@7.22.10/babel.min.js
  - Ensure an internet connection for CDNs and YouTube iframes.
  - Confirm `python -m http.server 8000` is running and port 8000 is open.
- **Styling Issues**: Check that the `<style>` block in `index.html` is intact.
- **YouTube Videos Not Loading**: Ensure browser security settings allow iframes.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss enhancements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Tailwind CSS for styling utilities.
- React for component-based architecture.
- Google Fonts for the `Inter` font.
