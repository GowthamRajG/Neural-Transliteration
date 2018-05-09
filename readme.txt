The goal of the project is to perform transliteration, i.e. convert words (typically names) from one orthographic system to another.  
For instance, "Beijing" is the English transliteration of the Chinese name "北京". Transliteration is not a deterministic process.  
Rules are the product of conventions that vary over time, depend on the origin of words and other historical accidents. 
For instance "Peking" is sometimes also used as the transliteration of  "北京".  

Transliteration can be used as a component in machine translation, to provide a target language form for out-of-vocabulary source names. 
In this project, the focus is on transliteration from Bulgarian, which is written with the Cyrillic alphabet, into English. 
The project uses a sequence-to-sequence neural model. 
It will take as input a sequence of characters in the input language and produce a sequence of characters in the output language.

Run transliterate.py for 17600 iterations. (Model tends to overfit beyond that)

Necessary additional libraries - numpy, nltk, attention

The code is developed on Python 3.5