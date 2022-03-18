# machine-translation
Machine translation is an application of RNN wherein the sentence is translated from one language to another, such as Google translate. The sentences are time-dependent, and the position of words in a sentence is of utmost importance. Two variants of Seq2Seq models are implemented, such as Vanilla and Attention Mechanism. Seq2Seq is a combination of Encoder & Decoder models. 

Further, three variants of Attention Mechanisms are implemented:
1. Dot (Luong)
2. General (Luong)
3. Concat (Bahdanau)

Dataset:
1. http://www.manythings.org/anki/ita-eng.zip

References:
1. https://arxiv.org/pdf/1508.04025.pdf
2. https://www.tensorflow.org/text/tutorials/nmt_with_attention#translate
3. https://stackoverflow.com/questions/44238154/what-is-the-difference-between-luong-attention-and-bahdanau-attention#:~:text=Luong%20attention%20used%20top%20hidden,hidden%20state%20at%20time%20t.
4. https://jalammar.github.io/visualizing-neural-machine-translation-mechanics-of-seq2seq-models-with-attention/
