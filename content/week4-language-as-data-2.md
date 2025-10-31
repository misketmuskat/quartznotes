Up: [[011_data-and-disc-lect]]
Prev: [[week3-language-as-data-1]]
Next: [[week5-michel-foucault]]

**Weekly Readings:**
- [x] Greimas, Algirdas Julien. 1979. “About Games.” _SubStance_ 8(4): 31. doi:[10.2307/3684212](https://doi.org/10.2307/3684212).
- [x] Ducard, Dominique. 2017. “Language and the Game of Chess: Saussure, Hjelmslev, Wittgenstein and Greimas.” _Semiotica_ 2017(214): 199–217. doi:[10.1515/sem-2016-0201](https://doi.org/10.1515/sem-2016-0201).

## Online Lecture Notes:
- ##### Recap From Previous Lecture:
	- The concept of data includes linguistic utterances and physical objects (e.g., moon rocks)
	- Data is semiotically understood as interpreted phenomena extracted from complex contexts.
---
- ##### Structuralist Model of Language:
	- **Ferdinand de Saussure's Contributions:**
		- Language is a *system of oppositions* with *signs* consisting of two aspects:
			1. **Signifier** (form)
			2. **Signified** (meaning)
		- The *identity* of linguistic signs comes from their *relational opposition to other signs*.
		- **Saussure's analogy:** Language functions like a *chess game*, where relationships and rules matter more than the physical pieces.
	- **Critiques:**
		- The *structuralist model* focuses on abstract systems and *disregards material and social contexts*.
		- Limited applicability for empirical research in discourse studies.
- ##### Pierce's Semiotics and Its Relevance:
	- Pierce identifies three types of sign relationships:
		1. **Indexical:** A real connection (e.g., smoke indicates fire).
		2. **Iconic:** Resemblance (e.g., portrait of imitation).
		3. **Symbolic:** Arbitrary associations (e.g., words, traffic signs).
	- Pierce emphasizes the material and contextual dimensions of signs, providing a foundation for empirical approaches to language.
	- **Application to Linguistics:**
		- Words as material entities (e.g., sounds, written forms) are tied to specific contexts.
		- Indexicality bridges the material and semiotic dimensions, enabling empirical study of how language interacts with social reality.
			- **Örnek:** “Köpek” kelimesi yazılı olarak harflerden (k-ö-p-e-k) oluşur ya da sesli olarak ağızdan çıkan bir ses dizisiyle ifade edilir. Bu, kelimenin maddi (görsel ya da işitsel) varlığıdır.
			- Eğer biri “Köpek gibi çalışıyorum” derse, bu mecazi bir anlam taşır ve hayvanlarla doğrudan bir ilgisi yoktur.
		- Pierce’in göstergebilim anlayışı, dilin sadece bir soyut sistem (Saussure’un dediği gibi) olmadığını, aynı zamanda maddi bir varlığı olduğunu ve sosyal dünyayla sürekli bir etkileşim içinde olduğunu göstermemize yardımcı olur. Dil, bulunduğu sosyal bağlama göre sürekli yeniden şekillenir, farklı anlamlar kazanır.
- ##### Treating Language as Data:
	- **Combining Perspectives:**
		- Words are both material entities (objects to be measured) and signs (units with meaning).
		- This duality is crucial for analyzing how language functions in social practices.
	- **Data Collection and Preparation in Discourse Analysis:**
		- **Steps Involved:**
			1. **Data Cleaning:** Removing unnecessary elements (e.g., page numbers).
			2. **Markup:** Adding metadata using formats like XML and TEI (Text Encoding Initiative).
			3. **Segmentation:** Dividing text into units (e.g., sentences, words) for analysis.
			   - Tokenization (word level) and sentence splitting (sentence level)
			   - Each segmentation decision is interpretive and affects subsequent analysis.
			4. **Annotation:** Adding syntactic, semantic, or functional tags to text for deeper analysis.
	- **Challenges:**
		- Variability in annotation models and algorithms can lead to inconsistent results.
		- Interpretive decisions in segmentation and tagging can significantly influence findings.
- ##### Practical Example — Annotation and Tagging:
	- Differences between tagging algorithms (e.g., TreeTagger vs. Stanford NLP Tagger):
		- Tokenization and par-of-speech classifications can vary, impacting analysis.
	- Importance of understanding underlying data models and assumptions in automated tools.
- ##### Key Takeaways:
	- Treating language as data involves both theoretical and practical considerations.
	- Researchers must balance material properties (e.g., words as objects) with functional aspects (e.g., words as signs).
	- Awareness of segmentation, tagging, and annotation methods is crucial for valid and reliable results.
- ##### Closing Notes:
	- Language as data extents beyond text to include multimodal elements (e.g., images, sound).
	- Future analyses must critically engage with the material and interpretive dimensions of language.
---
## Reading Notes:
### Greimas - About Games
##### 1. Game and Language
- **Key Idea:** Many 20th-century thinkers (e.g., Husserl, Saussure, Wittgenstein) used 'game' as a metaphor to understand language and human life. *Chess*, in particular, is a popular model.
	- **Why Chess?** Because it represents *a structured system of rules and strategies,* much like language, where *meaning arises from interplay* of its components.
		- Dynamic view of meaning
	- **Philosophical Importance:** Greimas suggests this isn't coincidental. There's a deeper cultural and epistemic link in the 20th century between games and how we conceptualize meaning and communication.
- **Example:** Imagine chess as a language. *The moves (like words) only make sense in the context of the game's rules (grammar)*. A pawn by itself doesn't 'mean' anything, but its movements gains significance when placed on a board and in relation to other pieces.
##### 2. Constraint and Freedom
- **Key Idea:** Games embody a paradox of constraints and freedom. While they are rule-bound, they also offer a space for free expression within those rules.
	- Players freely choose to participate in a game, agreeing to its rules.
	- Once inside, the player is bound by the rules.
##### 3. Game as System
- **Key Idea:** Games, such as chess, serve as models for understanding systems of signs and interactions. Chess is a *figurative model* that helps us think about the nature of systems like language and society.
	- The value of piece isn't about what it *is*, but how it *funcitons within the system.*
	- Words in a language are like chess pieces, 'run' means different things depending on the sentence:
		- "The child can run fast"
		- "The engine will run smoothly"
		- "He had a run of bad luck"
	- *Each move* in chess shifts the entire system *into a new structural state*.
		- Greimas likens chess pieces to *individuals* within societal systems.
		- Some thinkers (structuralists) saw society as a depersonalized system, where individuals are manipulated by the 'rules' of the system.
		- Greimas celebrates the fall of structuralism as a freeing event.
##### 4. The Players' Game
- **Key Idea:** The focus shifts from the chessboard (the system) to the players (individual agents) and their mental strategies. The game becomes *more than just following rules*; it's a battle of wits and strategy between two cognitive agents.
	- Moves are not just mechanical. They represent complex cognitive processes: *past moves, anticipated moves, strategies*...
	- It is not just about following rules perfectly, but about creating and exploiting strategies.
		- Strategy includes *interpreting the opponent* and *manipulating the opponent* to make them act in a way that benefits your broader strategy.
	- *Players aren't abstract entities*; they bring their *personal histories*, psychological traits into the game.
		- *Semantic competence*
		- *Modal competence*
##### 5. Chess and Computers
- **Key Idea:** Computers, equipped with artificial intelligence, can simulate human play but are limited to surface-level strategies. They lack the ability to interpret deeper, second-degree strategies involving deceit or manipulation.
	- Computers struggle with strategies not directly aimed at victory or those involving deceit. *Misleading moves* designed to confuse an opponent are *beyond most AI's capabilities*.
		- Deception and counter-deception require an understanding of context and intent, which computers lack.
	- Human players have the ability to introduce *unpredictability* and *creativity*. This gives the *illusion of freedom* within the game, making the competition more dynamic and less mechanical.
		- Think about how LLM's achieve "creativity".
##### 6. Game and Communication
- **Key Idea:** Games are a form of communication between players. A strategy, a bluff, or an intent to dominate.
	- A chess player aims not just to win but to make their victory undeniable and acknowledged by their opponent.
	- **Communication / Games / Power Struggles:** Communication in games *reflects a clash of will and power.* It's less about sharing a common understanding and more ab out achieving efficacy — manipulating the opponent's knowledge and perception to your advantage.
	- Nature of communication as a *struggle for efficacy and power*, rather than an *exchange of truths.*
##### 7. Games and Play (Jeu et aisance)
- **Key Idea:** Beyond rules and structure, games have areas of flexibility or 'play' (jeu) that allow fro freedom and creativity. This 'play' is essential for creating a sense of ease (aisance) and emotional satisfaction in the game.
	- Every normative system (games, societies, etc.) consists of rules. However, there are always *'empty positions'* where the rules don't strictly apply. They provide room for creativity, experimentation and freedom.
		- **Contrast:** In strict systems such as binary political systems (authoritarian regimes), everything is either forbidden or mandotory, leaving no room for 'play'. 
	- **Language and freedom:** Greimas suggests that language, often seen as *prison*, also offers areas of *play*. These areas allow for creativity, such as in poetry or humor, where *meaning can stretch or shift* beyond strict grammatical rules.
### Ducard - Language and the Game of Chess
##### 1. Introduction
- **Main Analogy:** Chess and language are compared to explore *how systems function through rules, interactions, and value.* This analogy has a long tradition in linguistics and philosophy.
	- **Saussure:** Introduced the idea of language as a system of values.
	- **Hjelmslev:** Focused on formal structures in semiotics.
	- **Wittgenstein:** Emphasized the pragmatic, rule-bound nature of language use.
	- **Greimas:** Extended the analogy to focus on the players and their interactions, beyond the structuralist model.
##### 2. Thinkers in Detail
- ###### Ferdinand de Saussure
	- **Language = Chess game:** Both are systems of *values determined by relations*, not intrinsic properties.
		- Pieces derive value from their *position and opposition*, language units (words) do the same within a system.
	- **Synchronic Linguistics:** Studies a language system at a given moment (like chess position)
	- **Diachronic Linguistics:** Examines historical changes (like the sequence of moves in chess)
	- Language is a *system of pure values*, independent of natural data.
	- Speech acts occur within a synchronic state, emphasizing structure over intent.
	- Unlike chess (played intentionally), speech often operates unconsciously — suggesting the system's primacy over individual agency.
- ###### Louis Hjelmslev
	- Language is a **semiotic structure:** Form matters, substance does not (the material of chess pieces is irrelevant; their roles are fixed by the game).
	- **Semiotic vs. Symbolic Systems**
		- *Semiotics:* Two-plane systems (form + content), like language.
			- Semiotiğin temel özelliği, çift katmanlı bir yapıya sahip olmasıdır. Bu yapı, ifade (expression) ve içerik (content) katmanlarından oluşur. Örneğin, bir kelime hem bir ses ya da yazı formu (ifade) hem de bir anlam (içerik) taşır. İkisi arasındaki ilişki semiotiğin çalışma alanıdır.
		- *Symbol systems:* Single-plane, algebraic models, like pure chess rules without interpretation.
			- Sembolik sistemler tek katmanlıdır. Yalnızca biçime odaklanır ve içerikle bir ilişki kurmaz. Satranç bunun bir örneğidir. Taşların nasıl hareket edeceği kurallarla tanımlanır, ama bu hareketlerin bir anlamı yoktur. Bu yüzden Hjelmslev, satrancı ve matematik gibi sistemleri sembolik sistemler olarak adlandırır.
	- Focuses on the *form of the relationships* rather than content, aligning language with abstract, rule-based systems like chess.
		- Hjelmslev’in vurgusu, dilin bir **form sistemi** olduğu fikridir. Dil, yalnızca kurallara dayalı bir yapı olarak ele alınmalıdır; içerik ya da anlam ise bu formun etkileşimleri üzerinden anlaşılır. Bir dildeki kelimeler veya sesler kendi başlarına anlam taşımazlar; diğer kelimelerle olan ilişkileri içinde bir değer kazanırlar. Bu bakış açısıyla, semiyotiği evrensel bir teori olarak görür. Bir sistemde biçimsel kurallar varsa – ister dil olsun, ister satranç ya da matematik – bu sistem semiyotik yöntemle analiz edilebilir.
	- *Semiotics is universal:* Any rule-bound system (chess, language, mathematics) can be analyzed through its formal relations.
- ###### Ludwig Wittgenstein
	- **Chess as a metaphor for rules:**
		- Understanding a chess piece ("This is a King") requires *knowing the rules*, not just observing the piece.
			- Words acquire meaning through *use within rules*, not their isolated form.
			- “Bu bir şah” dediğimizde, karşımızdaki kişi bu taşın **nasıl oynandığını** bilmiyorsa bu bilgi onun için anlamsızdır. Anlam, taşın satranç kurallarındaki yerinden ve işlevinden gelir. Bir kelimenin anlamı, o kelimenin dilde nasıl kullanıldığına bağlıdır.
	- **Language Games:**
		- Different linguistic activities (commands, jokes, stories) function as *language games*, akin to the variety of games in chess.
			- Her dil oyunu, kendine özgü kurallara dayanır. Örneğin, emir verme dilinde doğruluk ya da yanlışlık tartışılmaz; sadece emrin yerine getirilip getirilmediği önemlidir.
		- Meaning arises within *practical contexts* and "forms of life" (human activities).
	- Language rules are *pragmatic:* They guide activity, shaped by interaction and purpose.
	- Language is *not static*; it evolves through use, much like a game adapts during play.
		- Bir satranç oyununda, sadece taşların kurallarına göre hareket etmek yetmez; rakibinizin stratejisini anlamaya çalışır ve ona göre hareket edersiniz. Aynı şekilde, bir sohbette, sadece kelimeleri söylemek değil, karşınızdaki kişinin ne anladığını ve nasıl bir tepki verdiğini de göz önünde bulundurmanız gerekir.
##### 3. Greimas's Contributions
- Greimas shifts focus from *systems and rules* (Saussure, Hjelmslev) to **players' actions and interactions**.
	- He views chess moves as intentional actions, guided by strategies like *persuasion, deception, manipulation*.
	- These strategies parallel human communication, where actions are shaped by intentions and goals.
- Communication is less about *"truth-telling"* and more about **influencing others**.
	- In chess, players might mislead their opponent through calculated moves; similarly, in language, people often use persuasive or figurative expressions.
	- Figurative language, like poetry, masks meaning beneath surface appearances.
	- So, language creates *layers of meaning* that are often deceptive or fictional, reflecting its use as a tool for influence rather than truth.
- Meaning is not just on the surface but in the *hidden layers* beneath.
	- This is inspired by Nietzche: Humans do not perceive reality directly; language mediates understanding through metaphors and symbolic forms.
##### 4. Concluding Remarks
- The chess **analogy is flipped.** Instead of chess explaining language, language and meaning reflect the *semiotic model of chess*.
	- Language, like chess, operates as a *system of relationships* with multiple layers of interpretation (strategies, moves, sequences).
- Semiotics does not reconstruct reality itself but focuses on the *signifier world* — how meaning is structured and represented through signs.
	- It examines the *conditions of possibility* for meaning rather than the essence of objects or phenomena.