# Remarks for 2018

## Syllabus Brainstorm

- Intro:
	+ Supervised and unsupervised learning
	+ Classification vs. sequence classification
	+ Applications of Sequence Learning
	+ Exercises: set up your environment:
		* SSH key to tesla (--> SL container?)
		* Mosh/Tmux Tutorial
		* jstk
		* Languages? Java, Python
- 1/A basic auto-correct algorithm using DP
	We'll implement a basic auto-correct algorithm based on string edit distance (aka Levenshtein distance) and a word list
	+ Measuring differences in sequences: Levenshtein
	+ Baseline implementation (DP)
	+ Practical considerations: max-edit, partial results?
	+ Improved implementation: prefix trees, rx
- 2/Understanding states and cost functions.
	Understand how DP can abstract on states and cost functions, and how this can drive sequence classification for various applications
	+ auto-correct for different languages or keyboard layouts
	+ isolated word recognition
	+ DTMF sequence recognition
	+ phone sequence recognition (using mean values)
- 3/Modeling sequences: n-gram Models
	N-grams are a simple yet effective way to model sequences of discrete symbols.
	+ Estimating n-gram models
	+ Factored language model weights for improved auto-correct
	+ Predicting symbols based on n-gram models
	+ http://norvig.com/ngrams/
	+ http://norvig.com/spell-correct.html
- 4/Hidden Markov Models
	Learn how DTW is a (very) special case of an HMM and how it can be used to model sequences.
	+ Basic HMM evaluation (no training just yet)
	+ Alignment and Viterbi Algorithm
	+ EM/Baum-Welch training
	+ Viterbi training
	+ Isolated word recognition
- 5/Higher-level models and efficient decoding
	+ jump sequence detection
	+ basic word recognition
	+ TIMIT/word sequences?
- 7/nnets: feed-forward networs
	+ intro to python
	+ intro numpy and linalg
	+ basic feed-forward nets
	+ backprop
	+ Intro to Tensorflow (comp. graphs)
	+ https://www.jeremyjordan.me/neural-networks-training/
	+ https://medium.com/@karpathy/yes-you-should-understand-backprop-e2f06eab496b
- 8/nnets: recurrent nets, lstm
	+ basic RNN
	+ backprop through time (BPTT)
	+ larger Exercise? BPTT selber programmieren?
	+ LSTM --> move to 9/?
	+ BLSTM 
- 9/nnets: seq2seq
	+ loss functions
	+ seq2seq: CTC ausfuehrlicher naechstes mal!
	+ applications...advanced topologies?
		+ for stationary data
		+ speech recognition
		+ image captioning
- 10/Deep Learning Toolkits
	+ practical considerations: same-length outputs
	+ data processing: Pandas, Pickle, TFRecord genauer
	+ deployment: das war gut, sollte mehr sein, und mit Anwendung! Brainstorming aber gut
	+ => auf zwei Termine aufteilen?! Oder vielleicht "hausaufgabe" davor?
	+ Kurzvortraege zu den Toolkits durch Studis?

- GANs usw??


- better documentation for JSTK
- better documentation for exercises
- format:
	+ 3-hr sessions?
	+ 2-hr sessions with alternating lecture and assignments?
	+ homeworks? 4 blocks: DP, HMM, nnets, deeplearning (project)
