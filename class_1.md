Tar Terms : https://www.fclr.org/fclr/articles/html/2010/grossman.pdf 

# Predictive Coding 1.0
- 2009
- Active Machine Learning
- Math: https://e-discoveryteam.com/2013/06/03/guest-blog-quick-peek-at-the-math-behind-the-black-box-of-predictive-coding/
    - DESI stands for Discovery of Electronically Stored Information
    - SVM (Support Vector Machine) https://en.wikipedia.org/wiki/Support-vector_machine
    - https://en.wikipedia.org/wiki/Curse_of_dimensionality
        - the higher dimensions the sparser (volume grows exponentially)
    - 'Dynamic Programming' https://en.wikipedia.org/wiki/Dynamic_programming
        - Lost term of art?
    - Rule 26(b) (US Fed rule civil procedure)
        - Keep running into this legal rule and subsections
        - ```“relevant information” need not be admissible at trial if discovery appears reasonably calculated to lead to the discovery of admissible evidence```
            - WTF? Is that a typo?  Seems backwards?
    - ```manual or linear review, i.e., “eyes-on” review of every document by a team of attorneys```
    - recall
        - ```the ratio of relevant documents obtained in a given search to the overall number of relevant documents in the repository subject to search```
    - precision
        - ```the ratio of relevant to irrelevant documents obtained in a given search```
    - Magic quote of Sedona Search Commentary
        - ```In many settings involving [ESI], reliance solely on a manual search process for the purpose of finding responsive documents may be infeasible or unwarranted. In such cases, the use of automated search methods should be viewed as reasonable, valuable, and even necessary.```
        - Pragmatic philosophy underpinning e-discovery?
    - requesting / responding party
    - 'data universe' is this accepted jargon?
    - what does 'cooperation' mean in the real world?
    - Predictive Coding definition: 
        - ```The term “predictive coding,” as one of many labels describing partially automated software assisted review processes using support vector machines or related algorithms, involves (i) a set of preserved data, representing the entirety of what has been captured during a legal hold or culled down using filters for date ranges, custodians, or general subject areas; (ii) use of a random sample of seed documents, and/or a judgmental sample of documents obtained through prior coding, keyword searching, or known documents of particular high relevance to a particular discovery, coupled with a human-in-the-loop strategy of manually coding whatever seed set exists for relevance or privilege; (iii) employing machine learning software, including most notably support vector machines, to categorize similar documents; and (iv) using some kind of QC process to check for coding consistency [12].```
    - `da Silva Moore`
        - US Federal key case that 'blessed' the use of PC
    - hyperplane
        - plane in higher dimensions (-1 of total dimensions)
    - kernel function
        - aka 'kernel trick'
        - Turn non-linear curved 'hyperplane' into linear (scalar?) value
        - ```x = (x1, x2, x3); y = (y1, y2, y3). Then for the function f(x) = (x1x1, x1x2, x1x3, x2x1, x2x2, x2x3, x3x1, x3x2, x3x3), the kernel is K(x, y ) = (<x, y>)².```
            - https://towardsdatascience.com/kernel-function-6f1d2be6091
        - Interesting that this sort of 'trick' works.
            - Why would arbitrary projection into a higher dimension do anything useful?
            - Is there solid theory on _why_ this works? (is this _purely_ a computation trick or is there more?)
- SME (Subject Matter Expert)
    - sr. lawyer in charge of case
- Losey believes control sets are illusory, is he right?

# Predictive Coding 2.0 
- combines train/review stages
- aka CAL (Continuous Active Learning) then CT (Continuous Training)

# Predictive Coding 3.0/4.0
- Removed use of 'secret control set'
- Random sampling ramined
- Losey seems to argue that control sets are worthless because there is no 'ground truth' that the truth of what 'responsive' is will change over time as more facts are known
    - Seems like a pretty solid point IMHO
    - Controversial?
    - ```The truth is rare. The truth is relative.```
    - ```Uncertainty is inherent to information retrieval in legal search. Get used to it. That is reality on many levels, including the law.Uncertainty is inherent to information retrieval in legal search. Get used to it. That is reality on many levels, including the law.Uncertainty is inherent to information retrieval in legal search. Get used to it. That is reality on many levels, including the law.```
    - starting to feel a bit ranty on the whole 'control sets are garbage thing'...
        - ah 3.0 and 4.0 are Losey constructed, he is making case for why
        - OMFG OK I GET IT CONTROL SETS == THE DEVIL
- ```large infrastructure and interconnection across many different computer systems in different locations```
    - I know of such a system....interesting....


# Random Thoughts
- Recall/precision have _legal_ meanings and are e-discovery jargon (not just mathematical)
- I sincerely hope that the remaining classes are less _preachy_ and more _informative_. There was a lot of (defense of) opinion in this first class.
    - Felt a bit more like a screed than a lecture


        
    
    

    
    






