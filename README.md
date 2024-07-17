# Azure-ADF-Olymbics

Built a pipeline to extract olymbics data from HTTP source a github server/webpage and load it into azure synapse analytics

Prerequisites - basic knowledge on python, Azure student subscription, ETL.

1. Used copy data activity from ADF to extract data from HTTP server and load it into a raw zone in ADLS.
2. Used Azure Databricks to perform transformations and load it into ADLS, configured and used unity catalog for quering the unstructued CSV and Delta files/folders.
3. Created a lake database on synapse analytics pointiong out the ADLS transformed data, so BI can serve/fetch the data from synapse analytics.
