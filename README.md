# Surfs Up

### A Comparative Analysis between June and December Tempuratures in Oahu:

W. Avy needs more information about temperature trends before opening his surf shop. He wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable all year-round, versus just the summer months.
Calculating summary statistics for the temperatures of both months will allow for a deeper look into the type of business each month will experience in order to run a comparative analysis. It's possible that when temperatures start to drop, less people surf and eat ice cream.

#### Determine the Summary Statistics for June
In order to retrieve all the temperatures for the month of June, the date column of the Measurements table in the hawaii.sqlite database was filtered, using Python, Pandas functions and methods, and SQLAlchemy.
Those temperatures were converted to a list,then a Dataframe was created from the list, which allowed me to generate the summary statistics.
