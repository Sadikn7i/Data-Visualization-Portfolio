# Data Visualization Portfolio 

This repository is a comprehensive demonstration of skills in creating a wide array of insightful, modern, and interactive data visualizations using Python. The project uses a synthetically generated e-commerce dataset for a fictional company, "Quantum Gadgets," to explore and present data in over 70 unique ways.

The entire process, from data generation to the final plots, is documented in the main Jupyter Notebook. This project serves as a testament to the ability to handle data, ask the right questions, and tell compelling stories through visualization.

---

## ✨ Key Features

* **Extensive Library:** Over 70 distinct and advanced figures, ranging from statistical and time-series analyses to complex relational and geospatial plots.
* **Modern Tooling:** Primarily leverages **Plotly** for stunning, interactive, and dashboard-ready visuals, complemented by **Seaborn** and **Matplotlib** for statistical depth.
* **Interactive Dashboards:** Includes a fully interactive dashboard with cross-filtering capabilities built with `ipywidgets`, demonstrating skills in creating data exploration tools.
* **Advanced Charting:** Goes beyond standard plots to include Sankey diagrams, Pareto charts, horizon charts, network graphs, 3D plots, and modern designs like glassmorphism.
* **End-to-End Process:** The project starts with the programmatic generation of a rich, realistic dataset using `pandas` and `numpy`, showcasing a full data-to-insight workflow.

---

## 📊 Visualization Gallery

Here is a small selection of the diverse and modern visualizations created in this project.

| Glassmorphism KPI Dashboard                                    | Interactive Dashboard with Cross-Filtering                          | 3D Scatter on Categorical Axes                                    |
| -------------------------------------------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------------- |
|             |                |          |
| **Pareto Chart for Product Revenue** | **Streamgraph of Monthly Revenue** | **Product Co-occurrence Network Graph** |
|                         |                            |            |
| **Horizon Chart for Time-Series** | **Tornado Chart of Sales by Gender** | **Multi-Level Sankey Diagram of Revenue Flow** |
|                       |                               |                        |

---

## 🛠️ Technologies Used

This project was built using the following tools and libraries:

* **Language:** Python 3.x
* **Notebook:** Jupyter Notebook / JupyterLab
* **Data Manipulation:** Pandas, NumPy
* **Core Visualization:** Plotly, Seaborn, Matplotlib
* **Statistical Analysis:** Statsmodels, Scikit-learn
* **Interactivity:** ipywidgets
* **Specialized Plots:** bar_chart_race, calplot

---

## 🚀 How to Use

To explore the project on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```

2.  **Set up a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**
    ```bash
    pip install pandas numpy plotly seaborn matplotlib scikit-learn statsmodels ipywidgets bar_chart_race calplot
    ```

4.  **Install Jupyter Extensions (for full interactivity):**
    * For the interactive dashboard, `ipywidgets` needs a corresponding frontend extension. For the classic Notebook:
        ```bash
        jupyter nbextension enable --py widgetsnbextension
        ```
    * For JupyterLab:
        ```bash
        jupyter labextension install @jupyter-widgets/jupyterlab-manager
        ```

5.  **Install FFmpeg (for the animated racing bar chart):**
    * The `bar_chart_race` library requires FFmpeg. The easiest way to install it in a Conda environment is:
        ```bash
        conda install -c conda-forge ffmpeg
        ```

6.  **Launch Jupyter and open the notebook:**
    ```bash
    jupyter notebook
    ```
    Now you can run the cells in the notebook to generate the data and all the figures.

---

## 📈 Full List of Visualizations Created

To showcase the breadth of visualization techniques employed, here is a categorized list of the chart types created in this project.

#### Distribution Analysis
* Enhanced Histogram with KDE & Rug Plot
* Boxenplot & Violin Plot with Swarm Overlay
* 2D Density Plot & Joint Hexbin Plot
* Pair Plot with Hue
* ECDF Plot
* Raincloud Plot

#### Time-Series Analysis
* Time Series Decomposition Plot
* Line Chart with Rolling Average
* Monthly Sales Heatmap
* Cumulative Area Chart
* Candlestick Chart (Weekly & Monthly)
* Horizon Chart
* Calendar Heatmap (`calplot`)

#### Hierarchical & Proportional Data
* Treemap
* Sunburst Chart (Multi-Level)
* Icicle Chart
* Streamgraph
* Pareto Chart
* Donut Chart

#### Relational & Flow Analysis
* Correlation Heatmap
* Network Graph (Co-occurrence)
* Adjacency Matrix
* Sankey Diagram (Multi-Level Flow)
* Parallel Categories Plot (Parcats)

#### Geospatial Visuals
* Chorogit pleth Map (Sales & Rating)
* Geographic Heatmap (Hexbin Map)
* Animated Bubble Map

#### Dashboards & Specialized Plots
* Interactive Dashboard with Cross-Filtering (`ipywidgets`)
* Glassmorphism KPI Dashboard
* Bullet Charts
* Tornado Chart / Population Pyramid
* Slope Chart for Rank Changes
* 3D Scatter Plot (Categorical & Numerical Axes)
* Contour Plot
* 2D Histogram
* Interactive Table with Embedded Bar Charts

---

## 💡 Key Takeaways

* **The Power of Interactivity:** Using Plotly to create interactive charts provides a significantly deeper level of insight than static plots, allowing users to explore the data by hovering, zooming, and filtering.
* **Choosing the Right Chart:** The project emphasizes the importance of selecting the appropriate visualization for the question at hand, whether it's a Pareto chart for contribution analysis or a Sankey diagram for flow.
* **Robust Coding Practices:** The iterative debugging process highlighted the need for self-contained, robust code, especially handling edge cases like empty dataframes which can occur with randomly generated data.
* **Environment Matters:** Correctly setting up the Jupyter environment with necessary extensions (`ipywidgets`) and external dependencies (`ffmpeg`) is crucial for advanced visualization workflows.

---

## 👤 Contact

* **Author:** [Sadik Aden]
* **Email:** [Spritix98@gmail,com]

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
