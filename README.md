# Copenhagen Building Renewal

## About this Project
This repository is part of a spatial project exploring the topic of building renewal in Copenhagen.

The script in this repository does the following:

1. Creates a map showing the buildings in Copenhagen which have undergone building renewal.
2. Transforms and combines two CSV files showing the number of buildings older than 1899 per district.
3. Combines this data with spatial data showing the different districts of Copenhagen. Makes an accompanying map.

## Data Used
* Københavns Kommunes Statistikbank. “KKBYG1.” Accessed August 8, 2023.
https://kk.statistikbank.dk/statbank5a/SelectVarVal/Define.asp?MainTable=KKBYG1&PLanguage=0&PXSId=0&wsid=cflist.
* Open Data DK. “Bydele.” Accessed August 8, 2023,
https://www.opendata.dk/city-of-copenhagen/bydele.
* Open Data DK. “Byfornyelse.” Accessed August 8, 2023. 
https://www.opendata.dk/city-of-copenhagen/byfornyelse#resource-byfornyelse.  
* Open Data DK. “Udsatte byområder.” Accessed August 8, 2023. 
https://www.opendata.dk/city-of-copenhagen/udsatte-byomrader.

| file name | description |
| --- | --- |
| `1850-1899.csv` | number of buildings made between 1850 and 1899 per district in Copenhagen. |
| `before_1850.csv` | number of buildings made before 1850 per district in Copenhagen. |
| `bydel.json` | vector data showing the different districts of Copenhagen. | 
| `byfornyelse_kk.json` | vector data showing buildings that have undergone renewal. | 
| `f_udsatte_byomraader.json` | vector data showing areas of Copenhagen considered socially vulnerable today. |

`1850-1899.csv` shows the number of buildings made between 1850 and 1899 per district in Copenhagen. 
Data have been provided by Copenhagen Municipality and can be accessed via this link:
https://kk.statistikbank.dk/statbank5a/SelectVarVal/Define.asp?MainTable=KKBYG1&PLanguage=0&PXSId=0&wsid=cflist


`before_1850.csv` shows the number of buildings made before 1850 per district in Copenhagen. 
Data have been provided by Copenhagen Municipality and can be accessed via this link:
https://kk.statistikbank.dk/statbank5a/SelectVarVal/Define.asp?MainTable=KKBYG1&PLanguage=0&PXSId=0&wsid=cflist


`bydel.json` vector data showing the different districts of Copenhagen. Data have been provided by Copenhagen Municipality and can be accessed via this link:
https://www.opendata.dk/city-of-copenhagen/bydele


`byfornyelse_kk.json` vector data showing buildings that have undergone renewal. Data have been provided by Copenhagen Municipality and can be accessed via this link:
https://www.opendata.dk/city-of-copenhagen/byfornyelse#resource-byfornyelse


`f_udsatte_byomraader.json` vector data showing areas of Copenhagen considered socially vulnerable today. Data have been provided by Copenhagen Municipality and can be accessed via this link:
https://www.opendata.dk/city-of-copenhagen/udsatte-byomrader

### Data License
Attribution 4.0 International (CC BY 4.0): 
https://creativecommons.org/licenses/by/4.0/
