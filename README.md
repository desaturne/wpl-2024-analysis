# Women's Premier League 2024 - Comprehensive Cricket Analytics

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive statistical analysis of the Women's Premier League (WPL) 2024 season, providing deep insights into team performances, individual player statistics, match dynamics, and venue-specific trends.

## 📊 Project Overview

This project delivers a complete analytical framework for understanding the WPL 2024 tournament through data-driven insights. The analysis covers every aspect of the tournament, from individual ball-by-ball data to season-wide patterns and strategic insights.

### Key Features

- **🏏 Complete Tournament Coverage**: Analysis of all WPL 2024 matches with ball-by-ball granularity
- **📈 Advanced Visualizations**: Professional charts and graphs using matplotlib and seaborn
- **🎯 Strategic Insights**: Toss impact, venue analysis, and match progression patterns
- **👥 Player Performance**: Top performers in batting and bowling with detailed statistics
- **🏟️ Venue Analysis**: Comparative study of playing conditions across different stadiums
- **📊 Team Rankings**: Comprehensive team performance metrics and comparisons

## 🗂️ Dataset Description

The analysis utilizes two primary datasets:

### 1. deliveries.csv
Ball-by-ball data containing:
- Match identification and metadata
- Batting and bowling team information
- Player actions (striker, bowler, fielders)
- Runs scored, wickets taken, extras conceded
- Over-by-over progression data
- Venue and match phase information

### 2. matches.csv
Match-level results including:
- Team information and player rosters
- Toss decisions and outcomes
- Match results (winner, margin)
- Venue details and match dates
- Player of the match awards
- Win conditions (runs/wickets)

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8+
Jupyter Notebook or JupyterLab
```

### Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/wpl-2024-analysis.git
cd wpl-2024-analysis
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook wpl-analysis.ipynb
```

## 📋 Analysis Sections

### 1. Data Import and Environment Setup
- Library imports and configuration
- Professional visualization styling
- Data loading and validation

### 2. Tournament Overview
- Season statistics and structure
- Data quality assessment
- Key performance indicators

### 3. Team Performance Analysis
- Win-loss records and percentages
- Batting and bowling statistics by team
- Team-wise strike rates and economy rates
- Performance rankings and comparisons

### 4. Individual Player Statistics
- **Top Batters**: Leading run scorers, highest strike rates
- **Top Bowlers**: Leading wicket takers, best economy rates
- Boundary analysis and scoring patterns
- Player performance visualizations

### 5. Venue Analysis
- Stadium-wise performance metrics
- Toss decision patterns by venue
- Scoring rates and match outcomes
- Venue-specific strategic insights

### 6. Match Progression Analysis
- Over-by-over scoring patterns
- Powerplay, middle overs, and death overs analysis
- Phase-wise performance metrics
- Match dynamics and momentum shifts

### 7. Advanced Cricket Analytics
- Boundary distribution analysis
- Dismissal type patterns
- Extras analysis and bowling discipline
- Strategic decision impact assessment

## 📊 Key Insights and Findings

### Tournament Highlights
- **Total Matches**: Complete season coverage with comprehensive statistics
- **Scoring Patterns**: Detailed analysis of run rates across different match phases
- **Strategic Decisions**: Impact of toss decisions on match outcomes
- **Venue Influence**: How different stadiums affected team strategies and results

### Performance Metrics
- Team performance rankings based on multiple criteria
- Individual player achievements and records
- Venue-specific performance variations
- Strategic pattern analysis

## 🔧 Technical Implementation

### Data Processing
- Pandas for data manipulation and analysis
- NumPy for numerical computations
- Professional error handling and data validation

### Visualization Framework
- Matplotlib for statistical plotting
- Seaborn for advanced statistical visualizations
- Custom color schemes and professional styling
- Consistent branding across all charts

### Analysis Methodology
- Statistical analysis with proper significance testing
- Comprehensive data validation and quality checks
- Professional documentation and code organization
- Modular analysis structure for easy extension

## 📁 File Structure

```
wpl-2024-analysis/
├── wpl-analysis.ipynb          # Main analysis notebook
├── deliveries.csv              # Ball-by-ball data
├── matches.csv                 # Match results data
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Women's Premier League for providing exciting cricket data
- Cricket analytics community for inspiration and methodologies
- Open source Python ecosystem for powerful analytical tools

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please feel free to reach out.

---

**Note**: This analysis is for educational and research purposes. All data used is publicly available cricket statistics.
