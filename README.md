# Interactive Data Visaization using Diamonds dataset

This project explores how visualization design choices and interactive features influence the way users perceive patterns, relationships, skew, and distribution within a dataset. Through a series of interactive visualizations, it demonstrates how changes in scale, filtering, resolution, and transparency can alter interpretation and potentially shape conclusions.

## Objectives
- Create interactive visuals using Slider, Range Selectors and Toggle Buttons.
- Utlize both numerical and categorical variables in the dataset to depict important relationships
- Compare and contrast interactive versus non-interactive visualizations
- Analyze the effects of each interactivity feature including what it exaggerates, what it may conceal and how it can influence our perception


## Tools Used
-Plotly
- Matplotlib
- Jupyter Notebook

## Dataset
diamonds dataset from seaborn

## Results

Through a series of interactive visualizations, several key insights emerged regarding the relationship between diamond carat, price, and cut quality:

- The baseline scatterplot revealed a moderately positive relationship between carat and price, with higher-quality cuts generally associated with higher prices.
- Interactive zooming exposed local patterns that were not visible in the full dataset, including cases where diamonds with a "Good" cut were priced higher than diamonds of similar carat weight with a "Premium" cut.
- Applying a logarithmic scale to price reduced the impact of right skew, making the underlying relationship between carat and price appear more linear and easier to interpret.
- Histogram bin resolution significantly affected the perception of clustering and variability. Moderate bin counts provided the best balance between detail and readability.
- Adjusting point transparency reduced the effects of overplotting, revealing density patterns that were hidden when points were fully opaque.
- The project demonstrated that zooming and filtering have different interpretive consequences: zooming preserves the full dataset while changing perspective, whereas filtering removes observations and can alter perceived trends and distributions.
- Interactive controls improved exploratory analysis by allowing users to investigate data from multiple perspectives, but also highlighted the potential for selective interpretation and confirmation bias.
