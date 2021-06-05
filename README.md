## Covid Map
Generate a heatmap and a choropleth map using **Folium** via accessing the covid data API

### Takeaways from the project
1. An API (Application Programming Interface) is an interface that simplifies certain tasks, such as extracting subsets of data from a large repository or database.
2. Data is received from the API as one of the following formats:
+ Tabular Human-readable file: Tabular files that are organized into columns and rows. They have a “flat” structure rather than hierarchical. For example: CSV files (Comma Separated Values) , spreadsheets such as Microsoft Excel, etc. 
+ Structured Machine-readable files: Files that are hierarchical and structured in a way that optimizes machine readability.  They can be stored in a text format. For example:  JSON files.
3. An API request has three stages:
+ Data request: You try to access a URL in your browser that specifies a particular subset of data. It is possible to request the entire data but will use a lot of computational power.
+ Data processing: The web server uses the url you entered, to query a specified dataset.
+ Data response: The web server then returns a data file.
4. REST, or RESTful, API is a common type of API. A RESTfulAPI is a web API that uses URL arguments to specify what information you need.

5. Authentication is used to identify who you are. This includes a username and password, which is used to identify who you are.

6. An HTTP request uses a token for authentication, so the the user does not have to keep sending their username and password across the server.

7. A token has 3 components:
+ Header: Contains the type of algorithm used to create the signature.
+ Payload: Contains the data that you requested. 
+ Signature: Contains the encrypted part of the header and payload separated by a period.
8. "UTF-8" is a variable-width character encoding capable of encoding all 1,112,064 valid character code points in Unicode using one to four one-byte code units. The encoding is defined by the Unicode Standard, and was originally designed by Ken Thompson and Rob Pike.

9. A choropleth map has shaded or patterned regions corresponding to a statistical variable that represents an aggregate summary of a geographic characteristic within each area.

10. A heat map is a data visualization technique that shows magnitude of a phenomenon as two dimensional colors.

### Datasets
The data for this guided project is sourced from "COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University" and is updated daily.

Official Github repository: https://github.com/CSSEGISandData/COVID-19

The data for this project is accessed through an easy API developed by Kyle Redelinghuys.

Official site: https://covid19api.com/

The site is published at https://xxionias.github.io/covidmap/
![](images/map2.png)

