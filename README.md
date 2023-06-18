# Knowledge_Graph_Embedding


## GPT2_on_ConceptNet.ipynb:
First ConceptNet is downloaded and a portion of its edges with both ends in gpt2 tokenizer vocabs are considered. Then a GPT2 model is trained on sentences with structure: "{entity1} {edge} {entity2}".
The model can be then used to give you both embedding of words, or make similar knowledge based analogies, like, Person HasA hands.

Something significant is that the trained model shows both sexist and racist analogies, which makes me wonder why?!?
