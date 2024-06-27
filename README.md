# Critical Analysis of Lok Sabha Elections 2024 🇮🇳

![1](https://github.com/themihirmathur/Critical-Analysis-of-Lok-Sabha-Elections-2024/assets/92594107/718874f6-0692-4d24-9d40-d3c1b19e6609)

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Project Overview
The "Critical Analysis of Lok Sabha Elections 2024" project aims to provide a comprehensive analysis of the election results for the 2024 Lok Sabha elections in India. By leveraging data science techniques, this project explores various aspects of the election data, including constituency-level results, party performance, candidate analysis, and voting patterns.

![Screenshot 2024-06-27 at 2 58 49 PM](https://github.com/themihirmathur/Critical-Analysis-of-Lok-Sabha-Elections-2024/assets/92594107/24bf2851-53e0-4db5-8f6a-fb65b75eff0b)

## Features
- **Data Import and Cleaning**: Load and preprocess the election results data.
- **Exploratory Data Analysis (EDA)**: Visualize and analyze the data to identify trends and patterns.
- **Party Performance Analysis**: Evaluate the performance of major political parties across different constituencies.
- **Candidate Analysis**: Analyze the leading and trailing candidates in each constituency.
- **Margin of Victory**: Assess the margin of victory for winning candidates.
- **Status Reporting**: Report the status of election results for each constituency.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Technologies Used
- **Python**: The primary programming language used for data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For statistical data visualization.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Project Structure
1. **Import Libraries**
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
   ```

2. **Import Dataset**
   ```python
   data = pd.read_csv('election_results_2024.csv')
   ```

3. **Display DataFrame**
   ```python
   print(data.head())
   ```

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Data Description
The dataset `election_results_2024.csv` contains the following columns:
- **Constituency**: Name of the constituency.
- **Const. No.**: Constituency number.
- **Leading Candidate**: Name of the candidate leading in the constituency.
- **Leading Party**: Political party of the leading candidate.
- **Trailing Candidate**: Name of the candidate trailing in the constituency.
- **Trailing Party**: Political party of the trailing candidate.
- **Margin**: The margin of votes between the leading and trailing candidates.
- **Status**: Status of the election result (e.g., Result Declared).

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Analysis and Visualizations
1. **Constituency-Level Analysis**: Detailed analysis of each constituency's results.
2. **Party Performance**: Visualizations to compare the performance of different political parties.
3. **Candidate Performance**: Analysis of leading and trailing candidates across constituencies.
4. **Margin Analysis**: Visualization of the margin of victory for winning candidates.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

### Sample Code for Visualization
```python
# Plotting the performance of leading parties
plt.figure(figsize=(10, 6))
sns.countplot(y='Leading Party', data=data, order=data['Leading Party'].value_counts().index)
plt.title('Number of Seats Won by Each Party')
plt.xlabel('Number of Seats')
plt.ylabel('Party')
plt.show()
```

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Conclusion
This project provides valuable insights into the election results, helping to understand the performance of political parties and candidates across India. By utilizing data science tools and techniques, this project offers a detailed and visually appealing analysis of the election data.

<p align="left">
  <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" 
</p>

## Contact
For any queries or contributions, please free to contact.
