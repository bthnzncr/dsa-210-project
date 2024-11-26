# Generative AI Usage Analysis

This project focuses on analyzing the usage of generative AI tools, specifically selecting ChatGPT as the primary tool for analysis.

The data used in this project is acquired using the ChatGPT export tool. The exported data is in JSON format, which provides a structured representation of conversations, including metadata such as timestamps.

The primary objectives of this analysis include:
1. Categorizing the subjects discussed in the chats and identifying common themes or areas of focus.
2. Analyzing the distribution of queries over time.
3. Calculating the average number of queries per session.
4. Identifying sessions with unusually high or low activity.
5. Extracting and analyzing frequently used keywords or phrases.
6. Exploring possible alternative implementations to enhance analysis methods.

and some other possible implementations.

The tools and technologies used in this project include ChatGPT as the primary tool analyzed, programming languages such as Python for data analysis, libraries like pandas for data manipulation, matplotlib and seaborn for visualization, and the json module for parsing the exported data.

The structure of a single conversation is detailed in [example.json](example.json). Queries and responses are contained within the `parts` field, with roles identified as either `user` or `assistant`.
