# Interactive Kanban Board Application

## 📌 Project Overview

This project is an **Interactive Kanban Board Application** built using **React JS** that integrates with the Quicksell API from the following URL: [https://api.quicksell.co/v1/internal/frontend-assignment](https://api.quicksell.co/v1/internal/frontend-assignment). The application allows users to manage and group tickets dynamically based on various criteria and provides options for sorting them efficiently.

The Kanban board offers multiple functionalities, such as grouping by status, user, or priority, and sorting by priority or title. The board is also designed to be responsive and visually appealing, with a UI inspired by the provided design screenshots.

### Features

- **Dynamic Grouping Options**: 
  - Users can group tickets in three different ways:
    1. **By Status**: Tickets are grouped based on their current status.
    2. **By User**: Tickets are grouped according to the assigned user.
    3. **By Priority**: Tickets are grouped by their priority level.

- **Sorting Options**: 
  - Users can sort tickets in two ways:
    1. **By Priority**: Sort tickets in descending order of priority.
    2. **By Title**: Sort tickets in ascending order of their title.

- **Priority Levels**: 
  - The priority levels for the tickets are categorized as follows:

    | Priority Level  | Value |
    |-----------------|-------|
    | Urgent          | 4     |
    | High            | 3     |
    | Medium          | 2     |
    | Low             | 1     |
    | No priority     | 0     |

- **User Interaction**: 
  - When the user clicks the "Display" button and selects a grouping option, the Kanban board dynamically adjusts to reflect the user's choice.
  
- **Persistent View State**: 
  - The application saves the user's view state, so the selected grouping and sorting preferences are maintained even after a page reload.

### API Integration

The application communicates with the **Quicksell API** to retrieve the ticket data and dynamically updates the Kanban board based on the grouping and sorting preferences selected by the user.

### Responsive Design

The Kanban board is built with a responsive layout to ensure an optimal user experience across all devices, whether viewed on a desktop, tablet, or mobile.

## 🛠️ Technologies Used

- **React JS**: For building the interactive and dynamic user interface.
- **Axios or Fetch API**: For making API requests to the provided Quicksell API.
- **CSS/Styled Components**: For creating a visually appealing and responsive design.
- **LocalStorage**: To save and persist the user's view state across page reloads.
