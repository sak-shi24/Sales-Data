# Data Analysis Project

# Python Data Analysis Project
This is a data analysis project written in Python 3, which explores and analyzes a Sales Dataset. The project uses various Python libraries, such as Pandas, Datetime and Matplotlib, to clean the date, to perform the analysis and visualization of the data. [View the notebook](https://github.com/Harish-coding/Sales-Data-Analysis/blob/master/src/Data%20Analysis%20Code.ipynb)

## Quicklinks
+ [Findings](#findings)
+ [Requirements](#requirements)
+ [How to Use](#how-to-use)
+ [Acknowledgement](#acknowledgements)
+ [Contributing](#contributing)
+ [License](#license)


## Requirements
To run this project, you need to have the following installed on your machine:

1. Python 3.x
2. Jupyter Notebook or another environment to run Python scripts
3. Pandas
4. Matplotlib
5. Pretty Table
6. Seaborn
7. Kaleido

## Findings
1. The code written does some preleminary cleaning of data. Some of the StockCodes had more than one descriptions attched to them. To rectify this error, the most commonly occuring description for each of the StockCode was found, and replaced, so that each StockCode will have only one Description
2. After cleaning, we carry out some preliminary analysis, of the number of customers, and then the number of customers from each country. Based on this the code plots a Chloropleth.
3. After printing out the values used to plat the chloropleth, it is observed that Hong Kong has 0 customers. This indicates that there are some missing customerIDs associated.
4. In Order to understand how to deal with this, the number of invoices without customerID from each country is found out and their proportion in each country. 2 bar graphs are plotted to represent the same. Based on the findings the notebook discusses the best possible ways to deal with it.
5. Following this is product analysis, where the code analyses the top 10 most sold products and top 10 least sold products. Bar graphs are plotted to present the findings.
6. Moving on, the code finds out the most and least sold products in each country along with theri exact aggregate quantities. 3 csv tables - 'Most Sold Products by Country', 'Least Sold Products by Country', Most and Least Sold Products by Country - are produced to tabulate the findings. The last table was produced by merging the previous 2 tables.
7. The code then analyses the data through invoices, finding out the value of each invoice and storing them in a csv file, while also calculating the average value of eacg invoice. 
8. Expanding the previous point, the code moves on to analyse the average invoice value in each country, and plots them in a horizontal bar graph.
9. Having done this, the code analyses the ratio of cancelled invoices in the dataset, and plots a horizontal bar graph to shows the same.
10. The Sales is then analysed the dataset to find - 'Highest Sales Month', 'Lowest Sales Month', 'Highest Sales Month in 2010', 'Lowest Sales Month in 2010', 'Highest Sales Month in 2011', 'Lowest Sales Month in 2011' - in a table, using PrettyTable and then converts the table into csv file.
11. The code then analyses invoice across the 2 year time period, and finds - the highest and lowest sales month for each country, followed by the the country which had the highest and lowest sales each month. These findings were saved in a csv file.
12. The code then prodces a pivot table of total sales in different months in different countries, which is stored as a csv file.
13. Finally, the code produced heatmaps of sales of Items in different countries and sales in different months in different countries. To further enhance the quality of the heatmap, they are reproduced again using LogNorm function.  The logNorm function applies a logarithmic transformation to the data values, which compresses the range of values. This has the effect of enhancing small differences in magnitude between cells, making it easier to distinguish between them.

## How To Use
+ Close the repo into your local machine.
+ Open the Notebook on VSCode for a friendly user interface.
+ Follow the instructions in the notebook to load the dataset and explore the data.
+ Perform the data analysis tasks and visualize the results using the provided code examples.
+ Modify the code to perform your own analysis tasks or add new visualizations.
+ Save the notebook or script with your changes and share your results with others.

## Acknowledgements
The Source Data used int his project was obtained from [F. Daniel](https://www.kaggle.com/code/fabiendaniel/customer-segmentation/notebook). 

## Contributing
Contributions to this project are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue on the GitHub repository.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.