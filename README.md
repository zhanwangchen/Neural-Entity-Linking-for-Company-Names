# Neural-Entity-Linking-for-Company-Names

Entity Linking is the task to link entity mentions in text with their corresponding entities
in a knowledge base. Entity Linking is essential in many NLP tasks such as improving the
performances of knowledge network construction, knowledge fusion, information retrieval,
and knowledge base population. A large percentage of the web data is in the form of natural
language, which is highly ambiguous, primarily the named entities. To make ambiguously
named entities mentioned in the web machine-readable, we need to link the named entities
to structured databases with clean semantics. A named entity referring to a company can
for instance occur in variations: a list of company names might contain "Dell Inc", but that
company might also be referred to as "DELL", "Dell Technologies". Furthermore, the named
entity "dell" may have different meanings depending on the context. Two different companies
may both be referred to by the word "dell". There is little research specifically on company
named entity linking.
In this work, we study the performance of neural networks for entity linking of company
names. We examine the impact of different neural components used in current neural entity
linking systems such as mention embedding, entity embedding, attention mechanism in candidate
ranking. We compare the effect of traditional static word embeddings like word2vec or
GloVe with the more recent contextual embedding such as ELMo and character embeddings.
Company name related entity linking methods will be analyzed, such as how to generate the
alias of the company name, how to measure the ambiguity of company named entities and
possible reasons for incorrect disambiguation of a company named entity.

German summary  
Zusammenfassung  
Entity Linking ist die Aufgabe, Erwähnungen von Entitäten in Text mit den entsprechenden
Entitäten in einer Datenbank zu verknüpfen. Entity Linking ist für viele NLP-Aufgaben
unerlässlich, so wie bei der Verbesserung der Leistung beim Aufbau von Wissensnetzwerken,
Knowledge Fusion, Information Retrieval und Knowledge Base Population. Ein großer Teil
der Daten im Web liegt in Form von natürlicher Sprache vor, die jedoch oft nicht eindeutig
ist. Dieses Problem betrifft auch Named Entities. Um mehrdeutige Named Entities maschinenlesbar
zu machen, müssen wir diese mit strukturierten Datenbanken verknüpfen, die eine
saubere Semantik vorweisen. Ein Firmenname kann beispielsweise in verschiedenen Variationen
vorkommen: Die Ausdrücke "Dell Inc", "DELL" und "Dell Technologies” können
die gleiche Entität bezeichnen. Außerdem kann die Erwähnung "dell" je nach Kontext verschiedene
Bedeutungen haben. Zwei verschiedene Firmen können beide als "dell" bezeichnet
werden. Bisher gibt es nur wenig Forschung zu Named Entity Linking von Firmennamen.
In dieser Arbeit untersuchen wir die Leistung neuronaler Netze für Entity Linking von
Firmennamen. Wir untersuchen die Auswirkungen verschiedener neuronaler Komponenten,
die in aktuellen neuronalen Entity-Linking-Systemen verwendet werden, z.B. Mention Embedding,
Entity Embedding und Attention Mechanismen im Candidate Ranking. Wir vergleichen
den Effekt der traditionellen statistischen Word Embeddings wie word2vec oder GloVe
mit neueren kontextbezogenen Embeddings wie ELMo und Character Embeddings. Es werden
Entity Linking Methoden für Firmennamen analysiert, wie z. B. Aliasgenerierung, das
Erfassen der Mehrdeutigkeit eines Firmennamen sowie mögliche Gründe einen Firmennamen
mit der falschen Entität zu verknüpfen.
