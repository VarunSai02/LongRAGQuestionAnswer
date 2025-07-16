Exploring LongRAG’s Dual-Perspective Approach for Question Answering Systems with PubMedQA Dataset

This paper explores the implementation
 of LongRAG (Long-context Retrieval
Augmented Generation) in the medical do
main, focusing on its dual-perspective ap
proach that combines global document rep
resentation with localized passage analysis.
 We introduce a modified dual-perspective
 architecture where global views capture
 overall medical context from research ab
stracts, while local views focus on spe
cific medical details and terminology. Us
ing the PubMedQA dataset, we demon
strate how this dual-perspective mecha
nism effectively handles both broad medi
cal concepts and detailed clinical informa
tion. Our implementation leverages over
lapping document chunks for local under
standing while maintaining document-level
 coherence through global context vectors.
 Through this approach, we achieve an ini
tial accuracy of 55% on medical yes/no/
maybequestions, further improving to 57%
 after optimizing the interaction between
 global and local perspectives through fine
tuning.
