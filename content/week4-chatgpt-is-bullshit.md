Up: [[013_digital-oral-history]]
Prev: [[week3-ontology-based-metadata-integration-for-oral-history-interviews]]
Next: [[week5-penetrating-historical-discourse-truth-matrix]]
# ChatGPT is Bullshit
## Reading Notes:
- AI’s don’t lie or hallucinate, they bullshit. They don’t "care" about the truth one way other, they just make stuff up.
	- That’s a problem because **they’re programmed to appear to care about truthfulness, even they don’t have any real notion of what that is.** They’ve been designed to mislead us.
 - It is trained to form logical sentences. It isn’t trained to actually understand it’s output, limitation and such.
	 - Actually, **they're trained to form probable sentences**. It's only because we usually write logically that logical sentences are probable.
- The term **"hallucinate" comes from vision model research**, where a model is trained to identify a certain kind of thing, say faces, and then it identifies a "face" in a shadow pattern, or maybe light poking through the leaves of a tree. The AI is constructing signal from a set of inputs that don't contain the thing it's supposed to find.
	- The term was adapted to language models to refer to an imprecise set of circumstances, such as factual incorrectness, fabricated information, task misalignment. **The term 'hallucinate', however, doesn't make much sense with respect to transformer-based generative models, because they always make up whatever they're tasked to output.**
	- If you read generative AI papers from a decade ago (the DeepDream era), they will use "hallucination" to mean all output, not just the "lies".
	- _Every_ ChatGPT responses is _equally_ hallucinatory; some responses are just better at fooling users that they are drawing on "knowledge" whatsoever.

"Bullshit" gets us closer because it centers the idea that the system is simply not concerned with the accuracy of its output at all.
- Hallucinations **aren’t some bug or error case,** but merely **the product of the exact same process that gave us accurate information**. But the magic of generative AI is that so often that bullshit does align with the truth.
	- That's also exactly why they targeted visual arts so quickly, because it's easier to hide flaws when so much of it is subjective.
- AI isn’t experiencing anything, so calling it hallucination didn’t make any sense to begin with. It’s like tech people just picked a random word out of a psychology textbook and were like, “yeah, let’s go with that.”
- There was an excellent guide to AI Microsoft put out that basically outlines this. They described it as AI “wants to please” which is why the WAY you ask it / prompt it matters. If your prompt has bias or assumptions baked into the question, AI tends to not want to contradict you. [Source](https://www.microsoft.com/en-us/security/blog/2024/06/04/ai-jailbreaks-what-they-are-and-how-they-can-be-mitigated/)
	- This has to do with the way **word embeddings in LLMs “cluster” around semantic meanings**, so when the AI attempts to retrieve a response it enters a vector space of words with similar semantic meaning for its “prediction” of the “correct response” the user wants.
## Possible Questions
- Would you say that "truthiness" is unique to ChatGPT, or does this concept apply to other mainstream media and information technologies as well? How does ChatGPT compare to those?
- We talked about how output is produced. But the illusion is also lies in the how it turns our input to an output. This gives the illusion of "understanding".

This was a very stimulating paper. It led me to dig deeper. I came across with an article on NYT, dated March 2023, co-written by Noam Chomsky. At the end of the article, they were describing moral stance/indifference of ChatGPT by borrowing a highly influential notion from Hannah Arendt, "the banality of evil". So this is what they wrote on the article:

> ChatGPT exhibits something like the banality of evil: plagiarism and apathy and obviation. It summarizes the standard arguments in the literature by a kind of super-autocomplete, refuses to take a stand on anything, pleads not merely ignorance but lack of intelligence and ultimately offers a “just following orders” defense, shifting responsibility to its creators.

So, your argument of "ChatGPT as a soft bullshitter" also has a related kind of indifference, but it is centered around truth rather than morality. So, there’s a moral difference between calling ChatGPT’s outputs “hallucinations” versus “bullshit,” but there's also another step from “bullshit” to “banality of evil” as a concept. Arendt’s “banality of evil” goes further morally.

I know these two are focusing two different problems: One is related to truth, the other is to morality. But still, I feel like they are connected. 
I am interested in hearing your thoughts on this. Do you think applying "the banality of evil" to LLM's exaggerates their role, or does it complement to your "bullshitting" argument? Can Arendt's concept is better to understand LLM's relationship to truth and accountability than "bullshitting", or do these ideas work best together?
## Lecture Notes:
- **How do LLMs work?**
	- LLMs are based on an architecture of machine learning called a 'transformer model' or 'foundation model'.
	- This is a form of machine learning. The model consists in a large number of connected probability functions.
		- This is a Bayes net.
	- These functions are fed a large amount of data typically text from the internet.
	- They use that data to construct a predictive probabilities of the texts. What word tokens are likely to appear together?
	- The model itself associates with each text with **two vectors** in high-dimensional spaces.
	- The first locates a word (token) in a high-dimensional space near other words, that appear in similar contexts.
		- We can think of this as representing the meaning of the word.
		- However, it only has **some** of what we associate with meaning: the similarity between a word and other words, not necessarily word-world connections or inferential connections.
	- The second locates the word's surroundings in a high-dimensional space.
		- We can think of this as representing the word's context.
		- However, it again only includes some of what we think of as context.
	- The model **selects randomly** among the likely next words in the given context.
- **Then they are trained with data.**
- **When it goes wrong?**
	- The probabilities that the model produces and uses **do not represent** the likelihood of proposition's being true.
	- They instead represent the likelihood of a word being used.
	- This is correlated with truth: words are more likely to feature in true sonetences, provided the training data is mostly true.
	- 