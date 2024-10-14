# Interactive Collapsible Tree

An interactive, web-based visualization of hierarchical data using a collapsible tree diagram.

## 🌐 Live Demo

[**View the Interactive Collapsible Tree**](https://dhruvpolaris.github.io/interactive_collapsible_tree/)

## ✨ Features

- **Collapsible Nodes**: Click to expand or collapse branches.
- **Search Functionality**: Autocomplete search bar to navigate directly to any node.
- **Dynamic Data Loading**: Builds the tree from a CSV file (`data.csv`).
- **Responsive Design**: Adjusts to different screen sizes.
- **Color-Coded Levels**: Nodes colored based on their depth.

## 🎯 Usage Instructions

- **Expand/Collapse Nodes**: Click on nodes.
- **Search Nodes**: Use the search bar to find and navigate to nodes.

## 🚀 Running Locally

To run the project locally on your machine, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/dhruvpolaris/interactive_collapsible_tree.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd interactive_collapsible_tree
    ```

3. **Start a Local Web Server** (recommended):

    - **Using Python 3**:

        ```bash
        python -m http.server 8000
        ```

    - **Using Live Server in VS Code**:

        - Open the project folder in VS Code.
        - Right-click on `index.html` and select **"Open with Live Server"**.

4. **Open in Browser**:

    - Visit `http://localhost:8000` in your web browser.

## 📊 Data Format

- **CSV Structure**: Each row represents a path from the root to a leaf node.
- **Columns**: Represent hierarchical levels (e.g., Level 1, Level 2, ..., Level N).

**Example**:

```csv
Level 1,Level 2,Level 3
Company,Division A,Department 1
Company,Division A,Department 2
Company,Division B,Department 3
 ```

## 🛠 Technologies Used

- **D3.js**: For creating the interactive tree diagram.
- **jQuery & jQuery UI**: For handling the autocomplete search functionality.
- **Bootstrap**: For responsive design and styling.
- **HTML5 & CSS3**: Markup and styling of the web page.
- **JavaScript**: For interactivity and data manipulation.

## 🙏 Acknowledgements

- **[D3.js](https://d3js.org/)**: Data-Driven Documents library used for the visualization.
- **[jQuery](https://jquery.com/)** and **[jQuery UI](https://jqueryui.com/)**: Used for DOM manipulation and UI components.
- **[Bootstrap](https://getbootstrap.com/)**: For responsive design and layout.


