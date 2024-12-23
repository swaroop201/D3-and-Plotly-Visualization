# Global Terrorism Analysis Dashboard 🌍

An interactive data visualization project exploring global terrorism patterns through multiple visualization libraries including D3.js, Plotly, and Bokeh. This project provides comprehensive insights into terrorism incidents worldwide through various interactive visualizations.

## 📊 Features

### 1. Global Terrorism Heatmap (D3.js)
- Interactive world map showing terrorism incidents by country
- Dynamic year-based filtering through a slider
- Color-coded choropleth visualization
- Hover tooltips with detailed country statistics
- Responsive legend showing incident density

### 2. Top 10 Terrorist Groups Analysis (D3.js)
- Dynamic horizontal bar chart visualization
- Year-based filtering through dropdown menu
- Smooth animations for data transitions
- Interactive hover effects
- Color scaling based on incident counts
- Total incident count display for selected year

### 3. Attack Types Temporal Analysis (Plotly)
- Stacked area chart showing attack type distribution over time
- Toggle between different views:
  - Stacked
  - Grouped
  - 100% Stacked
- Interactive hover information
- Detailed legend for attack types

### 4. Target Types and Casualties Analysis (Bokeh)
- Interactive scatter plot visualization
- X-axis: Number of fatalities
- Y-axis: Number of wounded
- Point size indicates total casualties
- Color-coded by target type
- Year range slider for temporal filtering
- Hover tooltips with detailed information

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Node.js and npm
- Modern web browser

### Installation

1. Clone the repository
```bash
git clone https://github.com/swaroop201/global-terrorism-analysis.git
cd global-terrorism-analysis
```

2. Install Python dependencies
```bash
pip install pandas plotly bokeh
```

3. Install JavaScript dependencies
```bash
npm install d3
```

### Running the Application

For D3.js visualizations:
1. Install Visual Studio Code
2. Install the "Live Server" extension
3. Right-click on the HTML file and select "Open with Live Server"

For Python-based visualizations:
```bash
python plotly_visualization.py
python bokeh_visualization.py
```

## 📋 Technical Details

### Data Preparation
- Data preprocessing using Pandas
- Handling of missing values
- DateTime conversions for temporal analysis
- Aggregation for various visualization requirements

### Visualization Specifications

#### D3.js Implementations
- Custom color scales
- Interactive elements
- Responsive design
- Animated transitions

#### Plotly Features
- Multiple view options
- Custom styling
- Interactive legends
- Dynamic updates

#### Bokeh Components
- ColumnDataSource implementation
- Custom JavaScript callbacks
- Interactive tools (pan, zoom, reset)
- Advanced filtering capabilities

## 🎨 Design Choices

- **Color Schemes**: Carefully selected color palettes for optimal data representation
- **Layout**: Responsive design ensuring proper visualization across different screen sizes
- **Interactivity**: Rich interactive features for enhanced user engagement
- **Performance**: Optimized data handling for smooth user experience

## 🛠️ Built With

- [D3.js](https://d3js.org/) - For interactive map and bar chart visualizations
- [Plotly](https://plotly.com/) - For attack types temporal analysis
- [Bokeh](https://bokeh.org/) - For casualties and target types analysis
- [Python](https://www.python.org/) - Backend data processing
- [HTML/CSS/JavaScript] - Frontend implementation


## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ✨ Acknowledgments

- Global Terrorism Database for providing the dataset
- Various open-source visualization libraries and their communities
- Contributors and reviewers who helped improve this project
