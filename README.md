# python-data-visulaization
Python Data Visualization: Master Matplotlib and Seaborn

# Python Data Visualization: Master Matplotlib and Seaborn  

Welcome to the **Python Data Visualization** repository! This repository contains the source code, examples, and resources featured in the YouTube tutorial: **"How to Create Stunning Data Visualizations with Python: Master Matplotlib and Seaborn"**.  

## 🧑‍💻 **What You'll Learn**  
This tutorial covers the basics of **Matplotlib** and **Seaborn**, two essential Python libraries for creating impactful data visualizations.  

### Key Topics:  
1. **Matplotlib Basics**:  
   - Line plots, bar charts, and scatter plots.  
   - Customizing titles, axes, and legends.  

2. **Advanced Visualizations with Seaborn**:  
   - Histograms with density curves.  
   - Boxplots, violin plots, and pairplots.  

3. **Practical Examples**:  
   - Real-world use cases to visualize trends, distributions, and relationships in your datasets.  

## 🔧 **Getting Started**  

### Prerequisites:  
- Python 3.7+  
- Libraries:  
  ```bash
  pip install matplotlib seaborn

# 📄 Code Examples
## Matplotlib Example: Line Plot
   ```bash
      import matplotlib.pyplot as plt  

      x = [1, 2, 3, 4, 5]  
      y = [10, 20, 30, 40, 50]  

      plt.plot(x, y, label='Line Plot')  
      plt.title('Line Plot Example')  
      plt.xlabel('X-axis')  
      plt.ylabel('Y-axis')  
      plt.legend()  
      plt.show()  
