# YouTube-Data-Harvesting-and-Warehousing
To work on the project of YouTube data harvesting and warehousing, the first step is to extract information from a specific YouTube channel using the YouTube channel ID. Subsequently, this data can be analyzed in response to a set of user-provided questions. Python, Pandas,MongoDb,Build,Postgresql,Streamlit.

Overview
This project is designed to harvest and warehouse YouTube data using Python programming language, PostgreSQL, MongoDB, and Streamlit. The goal is to collect, store, and analyze YouTube data for various purposes such as content recommendation, trend analysis, and user behavior insights.

Tools Used
Python Programming Language:
Python is used for its versatility, ease of use, and a rich ecosystem of libraries, making it suitable for web scraping, data processing, and analysis.

Google API Client:
The googleapiclient library in Python facilitates the communication with different Google APIs. Its primary purpose in this project is to interact with YouTube's Data API v3, allowing the retrieval of essential information like channel details, video specifics, and comments. By utilizing googleapiclient, developers can easily access and manipulate YouTube's extensive data resources through code.

PostgreSQL:
PostgreSQL is employed as the relational database management system (RDBMS) to store structured data efficiently. It provides ACID compliance and supports complex queries.

MongoDB:
MongoDB is used as the NoSQL database to store semi-structured and unstructured data. Its flexible schema and scalability make it suitable for handling diverse types of data.

Streamlit:
Streamlit is utilized for building interactive and customizable web-based data dashboards. It allows for easy visualization of the harvested YouTube data.

Youtube Data Scrapping and its Ethical Perspective:
When engaging in the scraping of YouTube content, it is crucial to approach it ethically and responsibly. Respecting YouTube's terms and conditions, obtaining appropriate authorization, and adhering to data protection regulations are fundamental considerations. The collected data must be handled responsibly, ensuring privacy, confidentiality, and preventing any form of misuse or misrepresentation. Furthermore, it is important to take into account the potential impact on the platform and its community, striving for a fair and sustainable scraping process. By following these ethical guidelines, we can uphold integrity while extracting valuable insights from YouTube data.

Required Libraries
-> googleapiclient.discovery -> streamlit -> psycopg2 -> pymongo -> pandas

Packages required for Project to be installed:
-> Google Api Client :pip3 install google-client-api or python3 -m pip install google-client-api -> Pandas : pip install pandas -> MongoDB : pip install pymongo -> PostgreSql : pip install psycopg2 -> Streamlit : pip install streamlit
