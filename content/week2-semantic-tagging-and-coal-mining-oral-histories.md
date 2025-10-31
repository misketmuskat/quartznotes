Up: [[013_digital-oral-history]]
Prev: [[week1-introduction-digital-oral-history (missed class)]]
Next: [[week3-ontology-based-metadata-integration-for-oral-history-interviews]]

## Reading Notes:
Reading: brownshackel2023

- Focus on sentiment analysis
	- Understanding historic communities' everyday lives with the help of data science
- Sentiment analysis: Tagging terms based on their association with broader emotions, categories, sentiments
- The notion of **chronotope**:
	- The chronotope is how configurations of time and space are represented in language and discourse. The term, translated as ‘time-space’, was first used by Mikhail Bakhtin (1981) in 1937, when he described it as a central element in his theory of meaning in language and literature. He explains how literary genres operate with different configurations of time and space, giving each genre its particular narrative character.
	- As Peeren (2006, 69) points out, **‘subjects do not stand above a chronotope as its masters, but are within it or, indeed, of it’, indicating that chronotopes provide a frame that may enact limits on the kinds of identities that individuals may occupy.** This suggests that individuals may wish to challenge dominant representations of place and time to open up new possibilities for their identities.

## Lecture Notes:

##### History and Background of the Labor and the Antracite Region
- 1880's - southern and eastern europe immigration
- 1900 & 1902 - Anthracite Coal Strikes
- WWI era - 180.000 workers, 100 million tons
- 1921, 1923 - Immigration Restriction Acts
- dynamite > carts > break the coal
- A lot of the coal towns were segregated
- ##### Eastern and Southern European migration - begins in the 1880's
	- New immigrant
	- Racial hierarchies
	- Derogatory descriptions
		- invasion of hoards of uncivilized people
		- filthy
		- drunk
		- criminals
##### Current Conditions
- Some of the conditions still exist today
- Terkedilmiş binalar mevcut
- Rüzgarla birlikte coal dust şehri sarabiliyor
- Kimi bölgelerde terkedilmiş şehirler mevcut
- Yıkılmış, kırılmış yollar mevcut
- O gün yapılmış olan su kanalları, hala çevreyi etkilemeye devam ediyor. Aliminyum, magnezyum, ağır metaller taşıyan bu su kanallarından birinin pH derecesi 4.3 mesela
##### Memorialization of History
- 1973 - 26 oral histories from Scranton, Pennsylvania
- members of working-class
##### Goal of the authors
- To crate a new narrative of the region by using digital techniques like text mining
	- Before that: to understand How people perceive themselves, describe their identities, how do they narrate the history and collective memory
### Methodology
- Can we use **text mining and natural language processing** methods to work towards a new narrative?
- Requires converting transcripts from pdf to text and then cleaning the text
- Identifying themes
	- Term frequency
	- Bigram frequency
	- Sentiment analysis
	- Custom lexicon analysis
##### Data cleaning process
- **Standardize text inputs**
	- remove metadata, remove punctuation and extra characters, convert to lowercase, remove extra white spaces
- **Remove stopwords**
	- remove common words such as "it" "the" or "and" with standart stopword lists
- **Remove custom stopwords**
	- consider context-specific stopwords. For example, local or historic versions of stopwords (ain't, or thou)
- **Think about synonyms and plurality**
	- Combine different forms of the same word (run, running, ran). Also combine plural and singular forms of terms.
- ##### Word frequency
	- Family terms (people, father, mother, home)
	- Ethnic affiliation terms (english, irish, welsh)
	- Coal mining industry terms (mines, coal, company)
	- Labor unions and worker's livelihoods terms (company)
- We also should look at the bigrams in digitalized texts of oral histories (word combinations)
- Then try to see connections between words: Which words are associated with the word" coal". Give different 
##### Sentiment analysis and oral history
- Identifying themes in text with tagging libraries
- Can understand emotions, positive and negative affect and other dimesnions of the text
- Difficulty matching meaning and values of terms across contexts
- Preset tagging libraries and domain specific lexicons
	- We used Bing and AFINN
	- Also developed a custom tagging lexicon with the following themes
		- Family
		- Community
		- Work
- Some of the matching words do not really correspond to "negativity and positivity" diathomy
	- the word "pretty"? - second one in the positive side (Bing lexicon)
- Finding the top words — tagged by domain-specific themes in interviews
	- doing the same thing to "biagrams"
	- finding these commonly used words that we wouldn't really focus in the interviews, can give us a good ground to understand the everyday life in history,
		- By using quantitative analysis, we see what kind of things were important for people
##### Future directions for text mining and oral history
| Challenges                                        | Opportunities                                   |
| ------------------------------------------------- | ----------------------------------------------- |
| changing meaning of words                         | multilevel analysis                             |
| matching stopwords lists to oral history contexts | compatibility with qualititive research methods |
| loss of information in text                       | reproducible workflows                          |
| linking details with broad overviews              | addressing observer bias                        |
|                                                   | structured analysis of large volumes of text    |
- 
