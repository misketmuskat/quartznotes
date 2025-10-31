Up: [[013_digital-oral-history]]
Prev: [[week2-semantic-tagging-and-coal-mining-oral-histories]]
Next: [[week4-chatgpt-is-bullshit]]

## Reading Notes:
Reading: vrachliotou2022 

The main aim of the paper is to develop a metadata model for describing, managing, and retrieving oral history interviews. The authors propose a model that uses the EBUcore ontology and the CIDOC CRM to represent the information in oral history interviews in order to facilitate information exchange between different systems and improve the user search experience.
- ##### EBUcore
	- **Advantages:**
		- User-friendly, easy, flexible, and customizable: This makes it a good choice for curators of OH collections who may not have a lot of experience with ontologies.
		- Can handle multiple identifiers, titles, descriptions, and rights in different languages: This is important for OH interviews, which often have a lot of associated information.
		- Provides classes that are useful for describing OH interviews: For example, the Rating class can be used for parental or user ratings, the Publication History class can be used to describe when and how an interview is made public, and the Part class can be used to describe segments of an interview.
		- The Textline class allows for the synchronization of text transcripts or summaries with specific segments of an interview.
	- **Disadvantages:**
		- Not designed to describe historical or cultural heritage content: This can be a limitation for OH interviews, which often contain rich information about history, ethnography, and culture.
		- Cannot represent events and procedures that occur during the interview: This limits its ability to capture the full context of an interview.
		- Lacks a specific class for video recordings: While there is a class for audio recordings (ebucore: Audio Object), there is no equivalent class for video recordings after version 1.4.
		- Primarily focused on published content, making it less suitable for describing unpublished OH interviews, which are often treated as such by cultural institutions.
		- Limited in its ability to represent technical details about the digital files, such as versions, formats, codecs, and checksums.
- ##### CIDOC CRM
	- **Advantages:**
		- Formal ontology for cultural heritage information: This makes it well-suited for describing the rich historical and cultural content of OH interviews.
		- Can represent events and activities that occur in the lifecycle of an interview: This allows for a more complete representation of the context of an interview.
		- Flexible enough to represent both published and unpublished cultural heritage objects: This is important for OH interviews, which may or may not be made public.
	- **Disadvantages:**
		- Can be complex and difficult to use for those unfamiliar with ontologies.
		- Does not have the ability to describe digital objects in detail, such as technical attributes of audiovisual material.
		- Limited ability to define the temporal, spatial, or spatio-temporal locations within digital media.
- The authors propose a mapping between EBUcore and CIDOC CRM to leverage the strengths of both ontologies while mitigating their respective weaknesses. Using CIDOC CRM as the target schema offers a richer and more explicit semantic expression of the concepts found in OH interviews.
## Lecture Notes:
* Accessibility is the main focus, and Metadata of Oral History interviews
- How to make Oral History interviews more accessible
- **Metadata:** Data about data
	- In the library world, where cataloguing is important, 
- **The Oral History:** Is the process of conducting and recording an interview in order to collect information about the past. Is both the research methodology and 
- **Oral History Collections Characteristics:**
	- Not ameable to browsing.
	- Usually, in various forms.
	- Each interview is uniques.
	- It is neither published nor archival.
	- They might cover various topics in diverse periods of time.
	- Each interview may generate any o all of the following: audio/video file(s) in a number of formats (wav, mp3, mpeg-4, etc), transcripts, notebooks, text summaries and keywords, interview logs, the interviewer's questions and notes, various form, personal information about the interviewee and information about access restrictions, material donated by the interviewee (photos, notebooks, even 3D objects).
- **User characteristics:**
	- Instant access to various resources.
	- Avoid using different repositories.
	- In interviews they prefer to have access to exact points of interest.
	- Need for meaningful access.
- **The current situation of OH Collections:**
	- Diverse applied policies.
	- Closed repositories-without public access points.
	- Repositories that do not communicate & exchange information.
	- Numerous Private collections.
	- Still not considered a valid scientific resource.
	- With or without transcriptions.
	- Poor documentation and metadata.
- **Is there a solution?**
	- Rich metadata pre, during and post interview.
	- Indexing and segmenting interviews.
	- Creating models for the semantic representation of interviews using ontologies (the aim of the paper)
	- Collaboration between librarians, archivists, museologists, information and ICT professionals, oral historians, etc..
- **Oral History Metadata Synchronizer (1)**
	- Born in 2008 by the Louis
	- Compatible with CMS like OMEKA and CONTENTdm.
	- Influenced by PBcore in descriptive metadata.
	- Since 2023 in Aviary.
- **WarMemoirSampo**
	- Started in 2021.
	- Developed by the Semantic Computing Research Group.
	- Uses NER(Name Entity Recognition) tools to find entities from textual data (.csv) and categorize them with high precision in order to build light face ontologies.
	- Scope: to interconnect all portals and create a Web of Data
- **Modelling OH Interviews**
	- Stages of the interviewing process
		- Preparation
		- Interviewing
		- Preservation
		- Access
	- Stages of the model
		- Pre-interview-Preparatory
- **Why CIDOC CRM**
	- Is an event-centric model
	- It was developed as a reference conceptual medol for the integration and exchange of cultural heritage info
	- It can describe identification information, acquisition and ownership information, location and relocation information, physical characteristics
- **Why EBUCore?**
	- An ontology of audiovisoal content
	- The Dublin Core for media
	- User-friendly, easy, flexible, customizable and adaptable
	- Provides higher level of technical info
	- The rating class could be used for parental or user rating
	- The part class supports description of parts
	- Provides room for extensions
	- 