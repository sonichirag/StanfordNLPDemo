
# StanfordNLPDemo
This program demonstrates comprehension reading and auto answer using StanfordNLP

This will help one who wants to use Stanford NLP in their programs, and this tiny module might be helpful hence adding.

Here is sample Program output :

### Question : What software languages Chirag know

### Program Output :

Reading POS tagger model from edu/stanford/nlp/models/pos-tagger/english-left3words/english-left3words-distsim.tagger ... done [1.4 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.all.3class.distsim.crf.ser.gz ... done [2.0 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.muc.7class.distsim.crf.ser.gz ... done [2.3 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.conll.4class.distsim.crf.ser.gz ... done [0.9 sec].
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/defs.sutime.txt
Nov 18, 2017 8:04:42 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 83 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.sutime.txt
Nov 18, 2017 8:04:44 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 267 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.holidays.sutime.txt
Nov 18, 2017 8:04:44 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 25 rules
done [0.4 sec].

Sentence Priority Order
Chirag knows various languages like Java , Python , R . : 4.142857142857142
Chirag is great software engineer . : 2.619047619047619
This example uses NLP library developed by Stanford University . : 0.7666666666666666

Possible Answer:various

Final Answer:various
Line:He knows various languages like Java , Python , R .



### Question: what does Chirag do

### Program Output :

Reading POS tagger model from edu/stanford/nlp/models/pos-tagger/english-left3words/english-left3words-distsim.tagger ... done [1.2 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.all.3class.distsim.crf.ser.gz ... done [1.7 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.muc.7class.distsim.crf.ser.gz ... done [1.9 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.conll.4class.distsim.crf.ser.gz ... done [0.8 sec].
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/defs.sutime.txt
Nov 18, 2017 8:05:47 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 83 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.sutime.txt
Nov 18, 2017 8:05:47 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 267 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.holidays.sutime.txt
Nov 18, 2017 8:05:47 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 25 rules
done [0.5 sec].

Sentence Priority Order
Chirag knows various languages like Java , Python , R . : 1.6666666666666665
Chirag is great software engineer . : 1.6666666666666665
This example uses NLP library developed by Stanford University . : 0.6666666666666666

Possible Answer:languages

Final Answer:languages
Line:He knows various languages like Java , Python , R .

Final Answer:software engineer
Line:Chirag is great software engineer .



### Question : Who developed the library of NLP used here

### Program Output :

Reading POS tagger model from edu/stanford/nlp/models/pos-tagger/english-left3words/english-left3words-distsim.tagger ... done [1.2 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.all.3class.distsim.crf.ser.gz ... done [2.0 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.muc.7class.distsim.crf.ser.gz ... done [2.0 sec].
Loading classifier from edu/stanford/nlp/models/ner/english.conll.4class.distsim.crf.ser.gz ... done [0.9 sec].
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/defs.sutime.txt
Nov 18, 2017 8:06:55 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 83 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.sutime.txt
Nov 18, 2017 8:06:56 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 267 rules
Reading TokensRegex rules from edu/stanford/nlp/models/sutime/english.holidays.sutime.txt
Nov 18, 2017 8:06:56 PM edu.stanford.nlp.ling.tokensregex.CoreMapExpressionExtractor appendRules
INFO: Read 25 rules
done [2.0 sec].

Sentence Priority Order
This example uses NLP library developed by Stanford University . : 5.142857142857142
Chirag knows various languages like Java , Python , R . : 1.158008658008658
Chirag is great software engineer . : 1.125

Possible Answer:Stanford University

Final Answer:Stanford University
Line:This example uses NLP library developed by Stanford University .

