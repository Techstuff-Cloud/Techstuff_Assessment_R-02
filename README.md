# Techstuff Technical Assessment

## Overview

This project is a technical assessment designed to evaluate your skills in front-end development, including working with APIs, creating dynamic UI components, handling asynchronous data fetching, and managing errors. The assessment is structured into three levels, each with progressively complex requirements.

## Setup Instructions

1. **Install npm dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

## Requirements


### Wireframe

Below image represent the layout structure of what needs to be build.

These are **NOT ACTUAL DESIGN** and you are free to make it look good as per  your imagination.

![](https://github.com/Techstuff-Cloud/Techstuff_Assessment_R-02/blob/main/public/Wireframe_Assessment-2.jpg)

### Routing

1. **Create a Route**
   - You must use the `app` directory.
   - Create a route named `poke`.
   - Render everything at this route.

### Level 1: Basic Table with Pagination

1. **Create a Table UI:**
   - Implement a table to display a list of Pokémon.
   - Use the API `https://pokeapi.co/api/v2/pokemon` to fetch the Pokémon list.
   - Table columns should include:
     - **Sr. Number**
     - **Poke Name**

2. **Implement Pagination:**
   - Include pagination controls at the bottom of the table.
   - Show the total number of pages.
   - Disable the **Previous** button when on the first page.
   - Disable the **Next** button when on the last page.

3. **Handle Pagination Clicks:**
   - On clicking the pagination buttons, fetch and display data for the new page.

### Level 2: Detailed Information with Tabs

1. **Show Pokémon Details on Click:**
   - When a Pokémon name is clicked, fetch detailed information using the relevant API endpoint.
   - Display the Pokémon types as tabs on the right side of the table.

2. **Show Type-Specific Data:**
   - Below the tabs, display data related to the selected type.
   - Data to be displayed for each tab includes:
     - **Game Indices:** Length of `game_indices` array.
     - **Moves:** Length of `moves` array.

3. **Data Loading and Display:**
   - On selecting a tab, show the relevant data for the active type.

### Level 3: Error Handling and Loading States

1. **Handle Errors Gracefully:**
   - Implement error handling to manage API call failures.
   - Display user-friendly error messages.

2. **Show Loading Indicators:**
   - Display a loader while fetching data from the API.
   - Ensure the loader is visible until data is fully loaded.

## Assessment Criteria

1. **Correctness:**
   - Does the implementation meet the requirements specified in each level?
   - Are API calls made correctly, and is the data rendered accurately?
   - How to use component reusability and splitting features

2. **Complete all levels**


## Do's & Don't 

1. You can use Google.
2. You are free to use any library for UI/UX or functionality.
3. Artificial Intelligence(AI) not allowed, neighter in browser, nor in code editor.  We'll use [zerogpt](https://www.zerogpt.com) and you can be disqualified
4. Design not needed

---
## Good luck!
