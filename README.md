API Links To Use:
Daily spot prices API link (First Link to input when Prompted)
https://api.eia.gov/v2/petroleum/pri/spt/data/?frequency=daily&data[0]=value&facets[product][]=EPCBRENT&facets[product][]=EPCWTI&start=2000-01-01&end=2025-01-03&sort[0][column]=period&sort[0][direction]=asc&offset=0&length=5000

Futures API Link (Second Link to input when Prompted)
https://api.eia.gov/v2/petroleum/pri/fut/data/?frequency=daily&data[0]=value&sort[0][column]=period&sort[0][direction]=asc&offset=0&length=5000

Supply and Disposition Link (Third Link to input when Prompted)
https://api.eia.gov/v2/petroleum/sum/crdsnd/data/?frequency=monthly&data[0]=value&facets[process][]=EEX&facets[process][]=FPF&facets[process][]=IM0&facets[process][]=SAE&facets[process][]=SCG&facets[process][]=SPC&facets[process][]=YIR&start=2000-01&end=2024-10&sort[0][column]=period&sort[0][direction]=asc&offset=0&length=5000

API Keys and Paste Locations:

As I am not able to share my personal API key, the user has to obtain the API key from the EIA website and from the FRED website:
•	https://www.eia.gov/opendata/
  o	Tap “Register” under the API Section

•	https://fred.stlouisfed.org/docs/api/api_key.html
  o	Create an account, and request for an API key

In the main() function and in the fred_api() function, paste your personal API key into the code , just look for the 
"PasteAPIKeysHere" Text
