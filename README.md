# SAT pharmaceutics database
 
In 2017 the Mexican fiscal authority *Sistema de Administración Tributaria* (SAT) published an extensive catalog of products and services (with over fifty two thousand entries).  By law, digital tax receipts ("CFDI's") need to include the codes contained in the catalog.

Due to its size and ad hoc nature, incorporating the catalog into an existing point of sale software is a challenge.  I used Wolfram Language data and text analysis capabilities to generate a database suitable for the pharmaceutics industry.

## Files

1. `SAT_database_explorer.nb` allows to explore the pharmaceutics part of the SAT Catalog using a dataset in Wolfram Language format.
2. `pharmaceutics_SAT.cfd` summarizes classes and subclasses of pharmaceutics according to the SAT Catalog.
3. `SAT_data_analysis.nb` logs the steps used to convert, analyze and generate a dataset in *Wolfram Language* format.

## Data

Directory `data` contains the relevant data in various formats.  The original catalog is `SAT_catalog.xls`.  The files with the `.wdx` extension store the datasets in *Wolfram Language* format.
