# CSV2Supabase
## A Colab notebook for importing CSV files into Supabase tables. 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mansueli/CSV2Supabase/blob/main/Import_CSV_into_Supabase_with_APIs.ipynb)

Supabase doesn't allow importing CSV files after the table was created in TableEditor, which can be tricky for no/low code developers to use. 
Here we present an approach that you can use to import your CSV files just by editing the notebook and uploading the CSV file.


## Instructions:

You need to change the Colab notebook and prepare the CSV file to import it. But you should be able to import with minimal changes and you won't have to install anything in your computer to get this working.

### Example:

Sample table definition
<img width="963" alt="image" src="https://user-images.githubusercontent.com/5036432/212911262-1e848e03-2d73-4c5a-91ba-b9fa8f593dc9.png">

### Sample of CSV to import (with headers):
````
name,place,location
John,Av 1,colorado 
Paul,St 1783,New York
Batman,Batcave,Gotham
````

>**Note** 
>: Headers on the CSV is mandatory here for this to work. 
