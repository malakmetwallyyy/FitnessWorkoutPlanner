# Fitness & Workout Planner 🏋️

A responsive web application designed to help users plan workout routines, log completed exercises, and track their fitness progress through a fitness dashboard.

## About the Project

The Fitness & Workout Planner aims to make workout management easier by helping users organize exercise routines, record workout activities, browse exercises, and monitor fitness progress.

This project is being developed as part of **SW 302 – User Interface Development Course** at Zewail City of Science, Technology and Innovation, Fall 2026.

## Planned Features

- **Workout Dashboard:** View workout statistics, activity summaries, and progress visualizations.
- **Exercise Library:** Browse, search, and filter exercises.
- **Exercise Details:** Explore exercise instructions, target muscles, and safety tips.
- **Routine Builder:** Create and organize personalized workout routines.
- **Workout Logging:** Record completed exercises, sets, repetitions, and workout duration.
- **User Profile:** View and edit personal information and fitness goals.
- **Progress Tracking:** Monitor workout consistency and fitness progress.
- **Responsive Design:** Access the application on desktop and mobile devices.
- **Accessible Interface:** Follow good accessibility practices using semantic HTML, appropriate labels, and keyboard-friendly controls.

## Technologies

- **HTML5** — Page structure and content.
- **Tailwind CSS v4** — Styling and responsive layouts.
- **JavaScript** — To be added where needed for interactive functionality.
- **React** — Planned for future development only if required by the project's implementation plan.

## Team Members

| Name | ID | Role |
|---|---|---|
| Malak Metwally | 202401538 | Team Representative |
| Mariam Sherif | 202401189 | Team Member |
| Osama Mohsen | 202401039 | Team Member |

## Project Structure

```text
FitnessWorkoutPlanner/
├── docs/                   # Project documentation and designs
├── frontend/               # Frontend pages and styling
│   ├── src/
│   │   ├── input.css       # Tailwind CSS input
│   │   └── output.css      # Generated CSS
│   ├── index.html          # Home page
│   ├── dashboard.html      # Fitness dashboard
│   ├── workout.html        # Workout page
│   ├── exercise-library.html
│   ├── exercise-details.html
│   ├── measurements.html
│   ├── profile.html
│   ├── edit-info.html      # Edit profile page
│   ├── login.html
│   └── register.html
├── backend/                # Planned backend and API integration
├── tests/                  # Testing documentation and test cases
└── deployment/              # Setup and deployment instructions
```

## Running the Frontend Locally

1. Clone the repository.
2. Open a terminal in the `frontend/` directory.
3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the Tailwind CSS development process:

   ```bash
   npm run dev
   ```

5. Open `frontend/index.html` using a local development server, such as the VS Code Live Server extension.

## Project Status

**Phase 2 — UI Design and Static HTML Prototype**

The project includes HTML pages for the main application sections and a shared Tailwind CSS setup. The team is developing a consistent visual design system and responsive page layouts.

The current prototype focuses on the user interface. Features such as saving workout data, authentication, and persistent profile updates may require additional JavaScript and backend implementation.

## UI/UX Design

The UI/UX design and wireframes for the Fitness & Workout Planner were created using Figma.

[View Figma Design](https://www.figma.com/make/bKcGDnDMRCkYMR5HI5lGav/Fitness-Workout-Planner-UI?p=f&t=FjZDvHs9df5HIZQs-0&preview-route=%2Flogin)

## Documentation

Project documentation, wireframes, mockups, design-system references, reports, and other deliverables are maintained in the `docs/` directory as they become available.
