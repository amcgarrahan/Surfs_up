# Surfs Up

### A Comparative Analysis between June and December Tempuratures in Oahu:

W. Avy needs more information about temperature trends before opening his surf shop. He wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable all year-round, versus just the summer months.
Calculating summary statistics for the temperatures of both months will allow for a deeper look into the type of business each month will experience in order to run a comparative analysis. It's possible that when temperatures start to drop, less people surf and eat ice cream.

#### Determine the Summary Statistics for June
In order to retrieve all the temperatures for the month of June, the date column of the Measurements table in the hawaii.sqlite database was filtered, using Python, Pandas functions and methods, and SQLAlchemy.
Those temperatures were converted to a list,then a Dataframe was created from the list, which allowed me to generate the summary statistics.
<img width="307" alt="JUNE" src="https://user-images.githubusercontent.com/110629852/215862214-4b07c2ec-7053-4750-8fe2-db4794acfc18.png">

#### Determine the Summary Statistics for December
In order to retrieve all the temperatures for the month of December, the date column of the Measurements table in the hawaii.sqlite database was filtered, using Python, Pandas functions and methods, and SQLAlchemy.
Those temperatures were converted to a list,then a Dataframe was created from the list, which allowed me to generate the summary statistics.
<img width="307" alt="dec" src="https://user-images.githubusercontent.com/110629852/215862857-34f47310-56a9-44ce-8496-46270cbe740e.png">
