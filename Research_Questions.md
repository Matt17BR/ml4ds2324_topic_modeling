1. What AI techniques are most commonly used in assessing injury risks and predicting performance in team sports?
    - Refer to AI_Usage diagram.

2. What are the limitations and challenges identified in the use of AI for sports analytics?
    - From exploring the research paper, it remains unclear if these approaches will hold effective for individual sports, in the very near future.
    
3. What recommendations can be offered for future research in this area?
    - One key aspect that needs to be developed, lies in applying AI models that can comprehensively integrate various related factors for assessing injury risk and predicting performance.

4. When conducting a database search what keywords are efficient in identifying relevant papers?
    - We discovered that the words and phrases most commonly identified from topic modeling along with their aliases gave significant enough results to get matches with the original dataset. Refer to `keyword_search.ipynb`.

5. How can automated methods be utilized for efficiently accessing and analyzing numerous academic paper titles and abstracts?
    - Accessing a large collection of papers at a time can be quite challenging especially if the websites you're accessing don't have a public API. We found a workaround for PubMed, by accessing the official API with an email. Refer to `reference_list.ipynb`.

6. In the context of textual analysis, which methodology yields the highest efficiency for the identification of recurrent words and phrases?
    - We made use of a basic word counter, stemming and lemmatization. To judge which method works best, it is important to understand what is the purpose of finding the most common words. From a linguistic analysis perspective, stemming and lemmatization are better equipped. What regards a search algorithm, exact word matches are key, so a basic counter could be useful. In our case, we made use of all 3 techniques to fully understand the pattern in recurring words and phrases. Refer to `topic_modeling.ipynb`.

7. How can an automated search algorithm be optimized to accurately retrieve specific known papers from online databases (i.e. PubMed) using predefined keywords?
    - By identifying efficient keywords to utilize in the search. This can be done in a multitude of ways: applying NLP preprocessing techniques for identifying common phrases, and using aliases of such found words, additionally performing manual tweaking where needed.

8. Are there specific sports where AI has proven to be more effective and how so?
    - From exploring the research paper, we can note that not all sports are easily adaptable to AI analysis. Refer to example in paper: in one study the use of eccentric hamstring strength, age, and previous hamstring strain injury was not able to predict the risk of injury. Also the Bayesian network was applied in professional Australian football players with the area under the curve (AUC) of 54% being classified as a poor performance metric.

9. What are the optimal strategies for efficiently organizing a large collection of research papers into categories based on a
a specific variable?   
    - In our analysis, we sorted the methodology papers from the research papers and also then sorted the papers according to 4 variables as seen in `sports_ai_techniques.ipynb`. We found that the most efficient ways to divide the papers according to these 4 variables was using alias dictionaries for each term as explained in the answer of question 7.     

10. What factors influence the effectiveness of AI in predicting long-term athlete performance and injury risks, based on current sports science research?
    - From exploring the research paper, we can find that the factors that play a significant role are data quantity and quality, the possibility of developing an AI model to capture the intricacies of the sport as that cannot be done in all cases, and integrating knowledge from all fields related to sports science to improve the comprehensiveness of AI predictions.

11.  What AI techniques are most commonly used in which sports?
      - Refer to the `AI_Sports.png` diagram.
