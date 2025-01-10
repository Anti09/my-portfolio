# my-portfolio

This application displays a list of stock holdings along with a collapsible portfolio summary view, as demonstrated in the provided screenshots.

**Features**
Holdings List: Displays the list of stocks in which the user has invested, including key details like stock name, quantity, last traded price (LTP), and average price.
Portfolio Summary: Collapsible and expandable UI to provide a high-level overview of the portfolio's valuation.
Responsive Design: Clean, constraint-free UI developed programmatically, ensuring a smooth and responsive user experience across devices.

**Points of Evaluation**
1. Architecture:
   Adopts MVVM with a modular structure to scale the app easily for additional features.
   Codebase is organized to separate responsibilities across models, view models, and views, ensuring reusability and maintainability.
3. Responsibility Segregation: Clearly defined layers/modules:
    - View: Handles UI and user interactions.
    - ViewModel: Manages UI logic and acts as a mediator between the View and Model.
    - Model: Represents data structures and entities.
4. iOS-Specific Implementation:
  - Programmatic UI eliminates dependency on Storyboards, providing:
      Flexibility in layout management.
      Reusability and easier code reviews.
  - Clean UI with a focus on:
      Proper alignment.
      Well-organized and readable code for styling.

**Screenshots**
![Simulator Screenshot - iPhone 15 Pro - 2025-01-10 at 11 14 30](https://github.com/user-attachments/assets/ff3c41ff-7ea5-4dfe-857c-2bec630004c3)
![Simulator Screenshot - iPhone 15 Pro - 2025-01-10 at 11 14 24](https://github.com/user-attachments/assets/e08115c2-bb36-4526-8c87-8c0ce28cec12)
