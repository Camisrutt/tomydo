# Tomydo - Personal Todo App 

This is a personal todo app to manage various aspects of daily life. The app is divided into three sections:
1. **Big Overarching Goals** – Major, long-term objectives.
2. **Tasks** – Specific tasks that need to be completed.
3. **Things to Buy** – A shopping list where items can be marked with importance levels that prioritize them in the list.

## Features

### Core Features
- **Three-tab navigation**:
  - `Big Overarching Goals`: for long-term goals.
  - `Tasks`: for immediate or near-future tasks.
  - `Things to Buy`: a shopping list with priority ranking.
  
- **Task Management**:
  - Add, edit, and delete tasks, goals, or items.
  - Set deadlines or due dates for tasks and goals.
  
- **Importance Ranking** (for "Things to Buy"):
  - Items can be marked as `High`, `Medium`, or `Low` importance.
  - `High-importance` items automatically rise to the top of the list.
  
- **Prioritization and Sorting**:
  - Sort tasks by deadline or priority.
  - Items in "Things to Buy" are sorted by importance automatically.

- **Cross-Item Search**:
  - Quickly search across all tabs to find specific tasks, goals, or items.

- **Responsive UI**:
  - Mobile and desktop-friendly interface using modern web development technologies.

## Future Features
- **Notification Reminders**:
  - Set custom notifications for tasks and things to buy.
  
- **Progress Tracking**:
  - Visual progress bar for big overarching goals.

- **Cloud Sync**:
  - Sync data across multiple devices using a cloud storage service (optional feature).

## Project Plan

### Step 1: Set Up Project Structure
- Initialize project using `Vite` or similar frontend tooling.
- Set up folder structure:
  - `/src` for components, styles, and logic.
  - `/public` for static assets.
  
- Install necessary packages (e.g., React, TailwindCSS for UI, etc.)

### Step 2: UI Design and Layout
- Design three-tab layout.
- Create individual views for each tab:
  - `Big Overarching Goals` view.
  - `Tasks` view.
  - `Things to Buy` view with importance feature.
  
- Implement tab-switching functionality.

### Step 3: Implement Core Features
- **Adding/Editing/Deleting Items**:
  - Set up form to input tasks, goals, and items to buy.
  - Include validation (e.g., non-empty fields, character limits).

- **Importance Feature (Things to Buy)**:
  - Implement ranking system (high, medium, low).
  - Sort items by importance in real-time.

- **Search Functionality**:
  - Add global search input to find tasks/goals/items across all tabs.

### Step 4: Task Sorting & Prioritization
- Implement sorting by:
  - Deadline (Tasks and Goals).
  - Importance (Things to Buy).

### Step 5: Data Persistence
- Use local storage or an API for persisting tasks, goals, and things to buy across sessions.

### Step 6: Testing
- Conduct unit testing on task addition/editing/deletion.
- Test UI responsiveness across devices.
  
### Step 7: Documentation and Deployment
- Write comprehensive documentation on how to use the app.
- Deploy the app using GitHub Pages or Vercel.

## Todo List

### Initial Setup
- [ ] Initialize project with `Vite` or preferred tool.
- [ ] Set up basic folder structure.

### UI and Layout
- [ ] Design the layout for three tabs.
- [ ] Implement tab switching functionality.
- [ ] Create views for:
  - [ ] Big Overarching Goals.
  - [ ] Tasks.
  - [ ] Things to Buy.

### Core Functionality
- [ ] Implement form for adding, editing, and deleting items.
- [ ] Add importance level for things to buy.
- [ ] Enable sorting for:
  - [ ] Tasks by deadline.
  - [ ] Things to Buy by importance.
- [ ] Implement global search functionality.

### Data Management
- [ ] Use local storage to persist data.
- [ ] Optionally, set up cloud storage or an API.

### Testing & Deployment
- [ ] Test UI and functionality.
- [ ] Deploy app via GitHub Pages or Vercel.

## License
This project is licensed under the MIT License.
