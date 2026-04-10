

---

# Experiment 17: Basic Charts and Visual Encoding

---

### Aim: Basic Charts and Visual Encoding using Python

---

### Theory

Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

Visual encoding is the process of mapping data values to visual properties such as position, size, shape, and color. In this experiment, we explore how different types of charts—including line plots, bar charts, scatter plots, and box plots—can be used to represent various data distributions and relationships effectively.



---

### Library Descriptions

This experiment utilizes the two most prominent visualization libraries in the Python ecosystem:

* **Matplotlib (`matplotlib.pyplot`)**: A fundamental plotting library that provides a flexible, low-level interface for creating static, interactive, and animated visualizations. It is often used for fine-tuning the structural elements of a chart, such as axes, labels, and titles.
* **Seaborn (`sns`)**: A high-level data visualization library based on Matplotlib that provides a more aesthetically pleasing and statistically oriented interface. It simplifies the creation of complex plots like heatmaps and violin plots while integrating seamlessly with Pandas DataFrames.

---

### Command Descriptions

The following commands were used to generate and customize the visualizations:

| Command | One-Line Description |
| :--- | :--- |
| `plt.plot()` | Generates a line plot, ideal for showing trends over a period of time. |
| `plt.bar()` | Creates a bar chart to compare discrete categories or groups. |
| `plt.scatter()` | Produces a scatter plot to observe the relationship or correlation between two variables. |
| `plt.hist()` | Constructs a histogram to visualize the frequency distribution of a single numerical variable. |
| `plt.pie()` | Creates a pie chart to represent the proportions of a whole for different categories. |
| `plt.boxplot()` | Generates a box plot to show the distribution of data based on a five-number summary and identify outliers. |
| `sns.heatmap()` | Visualizes matrix-like data using a color-coded grid to show intensity or correlation. |
| `plt.xlabel()` / `plt.ylabel()` | Assigns descriptive titles to the horizontal and vertical axes of the chart. |
| `plt.title()` | Adds a main heading to the visualization to describe its purpose. |
| `plt.show()` | Renders and displays the final plot in the output cell. |

---

### Functions and Logic Used

#### Visual Encoding Logic
* **Position:** Mapping data to the X and Y coordinates to show relationships (e.g., Study Hours vs. Marks).
* **Color Mapping:** Using heatmaps to encode numerical values as colors, making high and low values instantly recognizable.

#### Chart Selection Logic
* **Trend Analysis:** Using line plots to show progress or changes over days.
* **Distribution Analysis:** Utilizing histograms and box plots to understand the spread and skewness of the data.
* **Categorical Comparison:** Applying bar charts and pie charts to compare different departments or categories.

---

### Conclusion

Through this experiment, I successfully implemented basic charts and visual encoding techniques using Matplotlib and Seaborn. I learned how to select the appropriate chart type based on the nature of the data and how to customize plots with labels and titles for better readability. These visualization skills are essential for storytelling with data and for communicating complex insights to stakeholders in a clear and effective manner.
