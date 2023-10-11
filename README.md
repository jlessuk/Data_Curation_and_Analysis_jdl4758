# Data_Curation_and_Analysis_jdl4758
Data curation and analysis of Wikipedia page: "List of countries and dependencies by area"

Explanation/notes:

- BeautifulSoup is used to read teh wikipedia page and extract the data from the table on the page. 
 - The data from the table is placed into four lists.
 - The lists with numbers all have two values per cell: one in parentheses and one outside the parentheses. A for loop is used to remove the parentheses and the values inside them. The remianing numbers are placed into new "cleaned" lists. 
 - There were some cells on the wikipedia page that were missing a value. These empty cells are filled with "N/A."

- Pandas is used to place the lists in a dataframe. 

When it comes to analyzing the data, several forms of analysis are provided:
- info about the entire data set and its size
- A description of each column

I was difficult to provide a visual representation because the range of the data is so massive. I have provided a bar graph that chooses three randomn countires/dependencies and graphs their area. The main benefit of this graph is that it helps visualize the range of the data. Even with the random choice of countries, the graph's y-axis usually has a range in the 10s to 100s of thousands of km squared. 
