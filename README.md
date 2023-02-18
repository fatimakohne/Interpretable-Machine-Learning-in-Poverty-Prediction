The dataset ("ihs5\_consumption\_aggregate"), which comes from the Office of National Statistics (http://www.nsomalawi.mw/) or from the World Bank website 
(https://microdata.worldbank.org/index.php/catalog/381831) contains 11,434 observations and 73 variables. However, the column names are coded, but the 
reference is available in the methodological guidelines of the Living Standards Measurement Study (LSMS), which is an IHS5 study documentation in PDF 
pp. 1288-1297 (http://www.nsomalawi.mw/images/stories/data_on_line/economics/ihs/IHS5/Malawi_Poverty_Report_Final.pdf). Thus, each column is manually 
decoded according to these guidelines and then renamed. The new decoded and renamed dataset is then saved in a CSV file under the name "df_dec", whose 
codes are in Notebook 1 called "Code1_data_decoding_renaming".

It is with this decoded and renamed data ("df_dec") that the implementation is done in Notebook 2 called "Code2_IML_in_poverty_ prediction". 
