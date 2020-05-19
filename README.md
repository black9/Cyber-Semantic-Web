# Cyber-Semantic-Web
In today’s era, microblogging platforms serve as the source for a plethora of sensitive and diverse information. We describe “Cyber Semantic Web” a system to discover and analyze cybersecurity intelligence on Twitter and serve as an intelligence source. Real-time information in the form of tweets is extracted about various cyber threats. The intelligence gathered will be represented by the semantic web and then extracted to be used for security analysis. In this implementation, we extract a vast amount of raw data from Twitter. After extraction of data, this data is preprocessed to a form that consists of only the tweet, the data, and the URL. The preprocessed data is then stored within a processed data store. The processed data store is then converted to a cross-platform independent data store that is fed to the Open Calais API created by Thomson Reuters. With the help of the Open Calais API, a series of categories are generated with the help of Natural Language Processing (NLP). We have now obtained data with context. This context can help inform users on a specific cybersecurity category in which a tweet may best fit. This procedure has proven to be a successful implementation which allows us to input a cybersecurity category, and a series of tweets which fall under the inputted category are retrieved. These retrieved tweets can now serve as tools for cyber security analysis and as a daily insight into the world of cybersecurity.
