# The National Sea Grant Library has closed 

## Background
The National Sea Grant Library (NSGL), which was housed on the Bay Campus of the University of Rhode Island, is no longer being funded and the entire collection is being deaccessioned. The collection consists of 2 print copies of each title published by every state Sea Grant program going back to the 1970's.  Subject areas include research, trade and popular material on the scientific, economic, political and social aspects of the coastal zones of the U.S., including the Great Lakes. Many of these titles have only a handful of libraries holding them or the NSG library is the only library.

> From the [National Sea Grant Library](https://nsgl.gso.uri.edu/) website (Dec. 2022):
>
> The NSGL was the digital library and official archive for NOAA’s Sea Grant documents from the 1960s through 2020.  Its catalogue remains a comprehensive and deeply searchable collection of Sea Grant-funded documents from the over 30 programs and projects across the United States and Territories.  This collection includes a wide variety of subjects including oceanography, marine education, aquaculture, fisheries, aquatic nuisance species, coastal hazards, seafood safety, limnology, coastal zone management, marine recreation, and law. 
>
>The online catalog provides global access to tens of thousands of full-text digital documents.  The Pell Library at the University of Rhode Island has become the archive for Sea Grant — preserving and enabling access to information-rich documents and publications from the 1960s through 2020.  For those documents that aren’t available electronically, anyone can request a PDF be created as part of the Digitization on Demand program. 

## Plan for the collection
The [NOAA Central Library](https://library.noaa.gov/) is taking existing digital copies of titles into the [NOAA Institutional Repository](https://repository.library.noaa.gov/), but the scans are not up to current standards. It is not clear how much of the collection has been scanned, but initial sampling indicates that it is less than half of the collection (excluding peer-reviewed articles in the analysis b/c they are available via other sources). 

There are 2 copies of each print title. As of now, Internet Archive will be taking the archival copy of the entire collection. The circulating copies have been offered in batches by state to any library willing to take them. Because of space limitations, URI will only be retaining the Rhode Island Sea Grant material. If no home is found for the 2nd copy of the items, they will go to the trash. 

The Harold A. Miller Library, a branch of the Stanford Libraries located at Hopkins Marine Station, has received shipment of the entire California Sea Grant Collection. According to the [National Sea Grant Catalog](https://eos.ucs.uri.edu/EOSWebOPAC/OPAC/Index.aspx), there are 4,398 CA items between the 'California Sea Grant' and 'Southern California Sea Grant' program, about 40 linear shelf feet according to the retiring NSGL Librarian. The librarian was unable to retrieve catalog records from Ye Olde Online Catalog, so this GH Repo is for code & files related to scraping the NSGL online catalog and processing the records.

## Outputs

De-duplicated catalog records for all three states can be found in one main file: 'nsgl-all-records.csv'.

Files for individual states can be found in ~/catalogRecords-raw as:
* 'nsgl-ca-records.csv' for California
* 'nsgl-or-records.csv' for Oregon
* 'nsgl-wa-records.csv' for Washington
