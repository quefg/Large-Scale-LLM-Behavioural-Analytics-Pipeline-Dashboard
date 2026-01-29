# Large-Scale Behavioural Analytics Dashboard

## Project Overview
This project is an interactive analytics dashboard built with Python, Streamlit, and Plotly. It is designed to visualize and analyze complex behavioral patterns and stance evolution within large-scale datasets.

The application processes structured CSV collections, providing a powerful comparative interface to simulate and analyze demographic subgroups (Age, Gender, Region, Education). It features advanced visualization capabilities to track how stances evolve over multiple rounds of conversations (Sycophancy Analysis) and identify key behavioral trends.

## Skills & Technical Showcase

This project demonstrates core competencies in data engineering, full-stack analytics application development, and advanced visualization, directly addressing key requirements for Data Analyst and Engineering roles.

### 1. Interactive Web-Based Dashboarding (Streamlit)
*   **End-to-End Application**: Designed, built, and deployed a complex, multi-page analytical tool using Streamlit.
*   **Dynamic UI/UX**: Implemented responsive layouts with robust sidebar filters, collapsible expanders, and dynamic rendering based on user selection.
*   **Customization**: Utilized custom CSS injection to refine the frontend aesthetics beyond standard framework limitations, ensuring a professional and user-friendly interface.

### 2. Data Cleaning & Pipeline Management (Pandas & NumPy)
*   **Robust Data Ingestion**: Engineered the `load_data_raw` pipeline to systematically handle diverse CSV datasets, automatically correcting encoding issues, stripping whitespace, and managing varying column structures.
*   **Advanced Feature Engineering**:
    *   Implemented logic to normalize inconsistent categorical values (e.g., stance labels) across heterogeneous data sources.
    *   Utilized Pandas for high-performance data manipulation, including pivoting, grouping, and applying complex lambda functions for feature extraction.
*   **Data integrity**: Implemented automated handling of missing values (`NaN` processing) and type enforcement for critical analysis columns.

### 3. Advanced Data Visualization (Plotly)
*   **Complex Interactions**: Integrated Plotly Express and Graph Objects to create highly interactive charts that support deep-dive analysis.
    *   **Sankey Diagrams**: Visualized flow dynamics and state transitions across conversation rounds, allowing users to trace opinion shifts.
    *   **High-Resolution Heatmaps**: Created custom-scaled correlation matrices to identify significant trends in "Support" rates and demographic clustering.
    *   **Dynamic Bar Charts**: Implemented sorting logic and custom color maps to present clear, comparative categorical data.
*   **Design Consistency**: Enforced a global design system (`GLOBAL_COLOR_MAP`) to ensure semantic consistency (e.g., consistent color coding for specific metric states like "Support" vs "Oppose") across all visualization types.

### 4. Analysis & Trend Identification
*   **Comparative Analytics**: The dashboard architecture allows for side-by-side comparison of different datasets, facilitating the identification of key trends and anomalies in behavioral data.
*   **Demographic Segmentation**: Deep-dive analysis capabilities allowing users to slice data by Gender, Age, Region, and Education to uncover specific behavioral strata.

## Dictionary & Translation Layer
*   Includes a robust dictionary-based translation system (`CN_TO_EN`) to dynamically map raw data values to English presentation layers, ensuring the dashboard is accessible to a global audience without altering the underlying raw data.


