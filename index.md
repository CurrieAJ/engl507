# Miranda Marini's Log for English 507

## 3 March 2015: Abstract

**Abstract:**

It can be argued that Eden Robinson’s *Monkey Beach* acts as an ecological and environmental guide for a predominantly white readership; however, allowing a glimpse into Haisla understandings of plants and landscapes not only emphasizes the protagonist’s culturally geographic bond to plants but also an ecological awareness of plant degradation as a result of urbanized expansionism. While the protagonist, Lisamarie, gains a traditionalist appreciation of plants, other characters also interact with ecology but on varying levels of traditionalist and modernist beliefs; as if to illustrate this divide, the text’s domestic plant descriptions predominantly perpetuate a colonized plant ideology whereas Haisla tradition and language are equated with native plants. I would like to argue that the text yields different plant-based descriptions, contextualization, and character interactions, which are dependent on the author’s colonial or Haisla language choices.

To demonstrate this, I will employ a text analysis method, manually extracting relevant plant-based terminology (both domestic and wild) and isolating each instance within its context. Using *Microsoft Excel*, each instance will be documented according to page number, character(s) directly interacting with each occurrence, plant type, and plant categorization as sustenance, medicinal, spiritual, work-related, or decorative. Currently, I have extracted plant terms from the sections “Love Like the Ocean” and “the Song of Your Breath,” and from the thirty-two recorded instances, 68.8% of the plants were used as a food source. In addition, all domestically grown plants appeared in the first section of the text whereas the majority of wild plants appeared in the second section along with Haisla signifiers. Once I record the terms from the last to sections of the novel, I intend to use *RStudio*, extracting keywords from the contextualized sentences and phrases to determine the frequency of colonial or Haisla plant descriptions. 
Ultimately, I hope to answer the broader question of how Robinson articulates Haisla agricultural tradition in relation to hegemonic settler ideas of the non-human environment, but it will be interesting to determine varying familial interactions with ecology and to examine whether traditionalist or modernist belief systems affect those interactions.

**Scope:** While it would be interesting to note non-human interactions with the environment, I am primarily looking at human and plant interactions. Initially, I focused on the second section of the novel, “The Song of Your Breath,” hoping it would produce the results I intended; however, I have broadened my search to include the novel in its entirety, gaining a comprehensive examination of domestic and wild plants.

**Concerns:** My main concern is sentence/paragraph contextualization. At what point does a part of the text become irrelevant? Should the included context exclusively contain the term or should explicit or implicit descriptions be included? Also, how should the results be presented?

**Peer-Reviewed Academic Journal:** Interdisciplinary Studies in Literature and Environment

**Note:** the term ‘plant’ is used broadly as anything growing out of the soil (trees, shrubs, grass, etc.).

## 17 February 2015: Annotated Bibliography

**Primary Sources**

Robinson, Eden. *Monkey Beach.* 2000. Toronto: Vintage Canada Edition, 2001. Print.

**Secondary Sources**

Bisht, Raj Kishor, Garima Srivastava, H. S. Dhami. "Term Weighting Using Term Dependence." *International Journal of Computer Applications,* 3.11 (2010): 1-3. Web. 9 Feb. 2015.

Claims:
* Bisht et al. argue that ‘term weighting’ is an integral part of term extraction; they indicate that the ‘weight’ determines the relevance of a term to the document and, therefore, to the outcome.
* They propose a local weighting scheme for word pairs, which they argue can better describe a document and emphasize the importance of word combinations.

Relevance:
* Regardless if I use a text extraction tool or manually extract relevant terms, applying a non-logarithmic variant of ‘term weighting’ will help me determine the relevance of searching for words as culturally specific as oxasuli or as menial as tree. It could also help determine term and character relations.

Elson, David K., Nicholas Dames, and Kathleen R. McKeown. "Extracting Social Networks from Literary Fiction." *ACL '10.* Association for Computation Linguistics, 2009. 138-147. Web. 9 Feb. 2015.

Claims:
* The authors create a methodology in which they can extract instances of quoted dialogue from a text, and constructing a network will expose bilateral conversations and frequency and lengths of character exchanges.
* To support their methodology, Eslon et al. analyze related works on social networking, decide methods for extracting accurate dialogue, and finally implement their methods to create the project and to prove/disprove their hypotheses.

Relevance:
* This framework could be beneficial when I decide on a particular avenue for the information I intend to find.
* Upon extracting every instance of plants within *Monkey Beach*, I could construct an ecological social network that includes plant and character interactions, medicinal or edible purposes, recipes (if applicable), etc.
* Perhaps this exploration will make readers think differently about the inclusion of specific ecology in the text.

Fraser, David. “A ‘Practical’ Ethic for Animals.” *Journal of Agricultural and Environmental Ethics,* 25.5 (2012): 721-746. Web. 9 Feb. 2015.

Claims:
* Human activities affecting animals in four ways: domestication, slaughter, unintended harm, and habitat destruction.
* The continual destruction of ecosystems negatively affecting animal relations: geographic displacement, food sources, natural patterns of behaviour.
* Offers solutions on how to prevent or mend ethical concerns.

Relevance:
* The article draws upon the ethical concerns of indirect or unintentional animal maltreatment due to human interactions.
* These concerns relate to Robinson’s portrayal of animal displacement (bears) and disappearance (oolichan).
* It contextualizes otherwise unexplained human impacts on animals.

Hovy, Eduard, Zornista Kozareva, and Ellen M. Riloff. "Towards Completeness in Concept Extraction and Classification." *EMNLP.* Association for Computational Linguistics, 2009. Web. 9 Feb. 2015.

Claims:
* While an obvious contender for the algorithmic harvesting of terms, Hovy et al. believe that WordNet is deficient because “it is neither complete nor is its taxonomic structure inarguably perfect” (1). By using a single surface-level pattern, the authors construct an algorithm to extract more terms than WordNet and broaden their taxonomic categorization.

Relevance:
* As I look for methods to either extract key terms from *Monkey Beach* or a way to present my findings, determining an algorithm that will produce my expected yield is pertinent.
* After extracting the terms and contextualizing them, could I put the spreadsheet results into a WordNet-like algorithm to reveal emerging themes such as medicinal relevance, Westernized understandings, etc.

Johnson, Leslie Main. “Plants, Places, and the Storied Landscape: Looking at First Nations Perspectives on Plants and Land.” *BC Studies,* 179 (2013): 85-91, 93-99, 102-105, 255. Web. 9 Feb. 2015.

Claims:
* “Plants shape landscapes and are, in turn, responsive to the characteristics of the land” (85).
* Plants as mediating our interactions with place.
* By analyzing plant habitats, naming, and ethnographic stories from elders, Johnson intends to connect people and plants through relevant narratives.

Relevance:
* Johnson builds on and adds new plant and landscape-based understandings of First Nations cultures that Robinson addresses in her novel.
* Legitimizes plants names as cultural understanding.

Kundoque, Jacquie Green. “Reclaiming Haisla Ways: Remembering Oolichan Fishing.” *Canadian Journal of Native Education,* 31.1 (2008): 11-23, 319. Web. 9 Feb. 2015.

Claims:
* As an indigenous student and professor, Kundoque understands the importance of nurturing and cultivating oral tradition. She argues that Haisla narratives help discover cultural history and the relationship have with plants and animals (particularly the oolichan).

Relevance:
* She corroborates Robinson’s mentioning of the disappearance of the oolichan and further details human and interference in their habitats, spawning, and migration patterns.
* She lists the importance of oolichan to the Haisla for its sustenance, medicinal properties, and rate of exchange.

Park, Gyeong-Mi, Sung-Hwan Kim, Hye-Ryeon Hwang, and Hwan-Gue Cho. "Complex System Analysis of Social Networks Extracted from Literary Fictions." *International Journal of Machine Learning and Computing,* 3.1 (2013): 107-111. Web. 9 Feb. 2015.

Claims:
* Using lexical analysis, the authors construct a method to determine textual distances and social relationships between characters in a text.
* They establish that "mining the topological structure of [a textual] social graph" will allow them to measure the extent in which protagonists or protragonists and secondary characters interact.

Relevance:
* Similar to Elson et al.'s work, Park et al. provide a social network framework that could be manipulated to refelect an 'ecological' network of Eden Robinson's flora.

Ryan, Courtney. “Playing with Plants.” *Theatre Journal,* 65.3 (2013): 335-353. Web. 9 Feb. 2015.

Claims:
* Ryan develops ideas surrounding human and animal engagement by applying and implementing ecocritical analysis upon plant and people interdependency.
* She also determines that animals rely on geography for sustenance and shelter in similar ways that human rely on plants and animals.

Relevance:
* While she does not discuss what happens when geography is manipulated or destroyed, she does emphasize human, plant, and animal codependency.
* When extracting key terms of *Monkey Beach*, I could contextually analyze who interacts with particular plant/animals and how those interactions affect one’s understandings.

Soper-Jones, Ella. “The Fate of the Oolichan: Prospects of Eco-cultural Restoration in Eden Robinson’s *Monkey Beach.*” *Journal of Commonwealth Literature,* 44.2 (2009): 15-33. Web. 9 Feb. 2015.

Claims:
* Referring to the colonization and industrialization of the Kitamaat area, Soper-Jones discusses the ecological degradation of oolichan environments and the impact this degradation has on the ‘old ways’ of Haisla culture.
* “[Robinson] rejects the notion that a text has to be accessible to all readers and thus refuses, in Doris Sommer’s words, to “surrender cultural difference for the sake of universal meaning” (17).
* Cognitive maps, Soper-Jones argues, are dynamic models of one’s environmental understanding: landmarks, plant-life, etc.

Relevance:
* If Robinson admits to “rework[ing] stuff and ma[king] certain parts up,” how can we determine what is and is not real within the text? While some plants are explained in Westernized terms, others are not. Does this mean that those that have not been adapted for non-Haisla readers are actually Robinson’s fictional constructions? Is there a way to determine this within the text?
* Could a cognitive map of the plants be made based on Robinson’s geographical descriptions?

Turner, Nancy J., Douglas Deur, and Dana Lepofsky. “Plant Management Systems of British Columbia’s First Peoples.” *BC Studies,* 179 (2013): 107-133. Web. 9 Feb. 2015.

Claims:
* According to anthropologists and archaeologists, First Nations have been categorized as hunter/gatherer communities because of their reliance on their immediate surroundings.
* Turner et al. provide an overview of plant resource management strategies within British Columbian First Nations communities; for instance, practices to cultivate the continual growth of essential organisms.

Relevance:
* *Monkey Beach* perpetuates the idea of the hunter/gatherer society as both Mick and Ma-ma-oo participate in a culture of cultivation and ecological understanding of plant/animal resources.
* It would be interesting to see how Ma-ma-oo participates in her own cultural management of plants: leaving tobacco for tree spirits, etc.

## 03 February 2015: Revised Thought Piece

Darias-Beautell argues that “an ecocentric perspective on past and present forms of colonialism would push the traditional postcolonial anthropocentrism to the consideration of often-ignored biocentric issues” (89). For instance, Eden Robinson’s *Monkey Beach* (2000) indicates the significance of cultural, ecological insight as well as the importance of independent sustainability in rural settings; the novel also implicates the effects urbanized expansion has had on the environment. Emphasizing knowable geographical bonds, the protagonist defines her own sense of place through her environmental interactions while subtly expressing the degradation of plant and animal ecosystems. In her blending of aboriginal culture and Westernized ideology, how does Robinson articulate Haisla agricultural tradition in relation to hegemonic settler ideas of the non-human environment?

By extracting the non-human appearances of plants and animals within the text, I will systematically record each occurrence in a spreadsheet, indicating the page number, the context of the term, the physical description of the term (if applicable), and the Haisla and European translations of the term (if applicable). As I reread the text and further extract key terminology, I hope to generate more research questions regarding human interactions with a non-human environment. I will primarily use the Plants of Canada Database, Native Plant Database, and BC Species and Ecosystems Explorer. However, some limitations include unidentifiable Haisla terms and multi-specie analyses. Nonetheless, I hope to create an interactive, visual digital resource that explicitly argues the similarities and differences between Haisla and dominant understandings of ecology.

**Possible Research Questions:**
* To what extent does the text reveal women as having privileged knowledge of the natural environment?
* Why include plants and animals in the text? Cultural understanding? Environmental awareness? Is it for the character's or the reader's benefit?
* By implementing code-switching, does Robinson hope to resist a generic, Westernized categorization of her culture?

**Bibliography**

*BC Species and Ecosystems Explorer.* Ministry of Environment, n.d. Web. 31 Jan. 2015.

Darias-Beautell, Eva. "Where Has 'Real' Nature Gone, Anyway?: Ecocriticism, Canadian Writing and the Lures of the Virtual." *Revista Canaria de Estudios Ingleses* 56(2008): 81-98. Web. 31 Jan. 2015.

*Native Plant Database.* Evergreen, n.d. Web. 31 Jan. 2015.

*Plants of Canada Database.* Canada, Sept. 2011. Web. 31 Jan. 2015.

Robinson, Eden. *Monkey Beach.* 2000. Toronto: Vintage Canada Edition, 2001. Print.

## 27 January 2015: Thought Piece Review

### Bassam's Thought Piece

**Research:** a quantified comparison of Walker's illustrations in Thackeray's *The Adventure of Philip* to Thackeray's other novels and Walker's other illustrations.

**Points to Consider:**
* How unique are Walker’s illustrations? Do they humanize ethnic minorities? Are these illustrations representative of the time? Are they radical images?
* How do you intend to quantify the uniqueness of these comparisons?
* Type ideas: clothing, posture, facial expressions, settings, etc.
* Quantification ideas: context of the illustrations, ethnic individuals, clothing, social status, etc.
* Do you intned to counteract the narrative of the text?
* By comparing image and text, could you argue Walker and Thackeray’s stances on racial issues during this time period?
* How are you going to organize the images? What types do you intend to use?
* How can you limit your scope? Period? 
* Could you quantify the levels of racism within the text and/or illustrations?

It'll be very interesting to see what kinds research questions and arguments will emerge from your analyses!

### Lindsey's Thought Piece

**Research:** is Austen a representation of a social past or social future? Can class be proven to be static or modernist?

**Points to Consider:**
* Conceptualization of possible class and interpersonal relations
* Project can build on other possible research questions: narrative style, character relations, racism (if any), class stratification, etc.
* Could you make this project maliable for other projects? Could you trace the social past/future of all Austen’s novels then network each network together?
* Do the characters go beyond their social circles?
* Would you be able to focus on the protagonists specifically and secondary characters specifically? (For example: colour coding)
* Does class make you morally sound?

**Possible Readings:**
"Graph Visualization Software for Networks of Characters in Plays" by Amerlia Carolina Sparavigna and Roberto Marazzato

I think this project could become a point of reference for future Austen scholars!

### Alyssa's Thought Piece

**Research:** does Blake play into the language present in newspapers surrounding tigers/tygers? Does he challenge it?

**Points to Consider:**
* Could you argue the text as a piece on animal activism? Was there a particular intent using the language? Does it satirize or parody the language?
* What is your scope?
** 5-10 years leading up to the publication of “The Tyger”
** All London newspapers? Big news headlines?
* To what extent do each article discuss tigers? How sensationalized are the tigers in the articles?
* Could you look at tiger poems that are published in the articles in relation to Blake’s poem? What kind of language do they use?

Using Wordle will be very visually appealing (if you wanted to integrate the images into your research paper) and will help you quantify key terms! Good choice!

## 27 January 2015: Thought Piece

To challenge and highlight the effects urbanization has had on the environment, Eden Robinson's *Monkey Beach* (2000) indicates the significance of ecological insight as well as the importance of independent sustainability in rural settings; by familiarizing herself with her ecological surroundings, the protagonist forms transcendental geographical bonds as well as a sense of place through her environmental interactions. However, with the emergence of urbanization in traditionally rural areas, Robinson subtly expresses the exploitation of plant and wildlife habitats for personal and corporative gain. How, then, does Robinson's novel become an eco-critical analysis of Haisla agricultural tradition and Eurocentric ecological manipulation?

Deviating from traditional human coding, new media and computation could limit systematic and human errors, providing accurate quantifiable readings of environment-related instances within the text. In addition, utilizing a computational method may produce larger key term, formulaic sequence, and comparative ratio yields, and I believe that computation will not only apply to this research question specifically but also to the larger questions surrounding spatial awareness as historical, ecological, and cultural insight.

To produce these results, I would like to employ computer-aided text analysis to draw out these key terms and quantify their recurrence in the text. During the initial transcribing of the novel as a text file, active markdown would allow the tagging and searching of key terms specific to plants, animals, cultural sustainability, and destroyed ecosystems. By applying semantic occurrence and algorithmic equations, quantifications of particular environmental instances, related character interactions, and term context could define, for example, the interaction ratio between the Haisla, the settlers, and place.

In selecting this method, I hope quantifying the recurrence of key terms, people's interactions with place, and eco-critical implications will help me explore diverging place-based relationships between Haisla members and Eurocentric settlers.

Robinson, Eden. *Monkey Beach.* 2000. Toronto: Vintage Canada Edition, 2001. Print.

## 20 January 2015: After Hermes?

While grappling with Galloway's heavily theoretical and mythological interpretations of mediation, I wonder why "media threaten to render us speechless" (27) and why hermeneutics, iridescence, and infuriation seemingly are compelled to combat for dominance. Galloway describes hermeneutics as "critical tradition" (40) whereas iridescence is "a [parallel] secondary world" of expression (44); in opposition to these two modes of mediation, infuriation intends to "annihilate" critical tradition altogether (40). Even though he claims a new hegemony of negotiated dominance will emerge with the withering of hermeneutic interpretation and immanent iridescence, I am not entirely compelled or persuaded by Galloway's observations. I do, however, agree that new or adapted modes of mediation are pertinent in the development of critically understanding new media formats, technologies, and criticisms.

Regardless if Galloway is accurate in his assumptions, what effects would his claims have on a proposed readership or media-based demographic? Would the elimination of hermeneutics and iridescence deter people from critical discourse and/or thinking? Will there be a progression in literary and cultural criticism without these fundamental mediators? Will all future arguments circulate in a never-ending spiral of like-minded thought?

Perhaps, then, Galloway's analysis of a synthesized fourth middle promotes both "the exile into foreign land...[and] a return to a more somatic immediacy" (18). By incorporating various components of different communication, could we not create a new middle that does not dominate but rather coexists? With a multimodal communicative system, other modes of interpretation could emerge in the process of mediation; arguably, a new method could promote a non-linear and multi-dimensional understanding of critical interpretation.