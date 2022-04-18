# Citation-Function-Classification-Using-Ensemble
# Background to the Project
The citation work reveals the author's motivation for referencing a particular article. Furthermore, past research relied heavily on several machine learning approaches. To answer a major question, many citation function systems have been developed. Why does the author mention a research study with so many functions and granularity levels? However, quantitative measurements alone may be deceiving when it comes to a research's beneficial effect. A publication on a severely criticized work, for example, may receive a large number of citations. Systematic qualitative approach of articles is difficult since it necessitates the processing of all citing articles' textual content. 
However, many works on citation function classification have been done; the performance of existing studies does not satisfy the requirement of analysis on large data.  So, we choose an ensemble technique is a suitable technique to improve the performance. 
The categorization study of the citation function can help publishers to discover the relationships between publications or articles. It aids to improve the design citation indexers, and the long-term examination of a scientific work's overall argumentation framework. The performance results of this study will provide some information about the quality of models which will be used to improve the citation performance. This will also be helpful to future researchers to find the models for better performance.



# Project Objective 
Previously, A series of Deep learning models are trained for citation context analysis by experimenting with different ways of encoding features; observed different models performed differently using the same dataset, and no single model achieved high performance. We believed that we could investigate the differences between various Deep learning models and create ensemble techniques to out of proper analysis.

# Methodology 
In this report we choosen ensemble techniques to improve the performance. Because ensemble techniques 
are believed to be the best advanced approach for several machine learning problems. This method assists in the reduction of manual annotating time. By instructing many models and integrating their outputs, such strategies increase the forecasting performance of an individual model.

As part of this study, we performed three procedures. 
####	 Ensemble technique applied for best epochs of each model seed 
####	 Ensemble technique applied for all epochs of each model seed 
####	 Disagreement measure performed for respective model seeds to check the final accuracy

Ensemble learning's main concept is that by merging several models, the faults of an one inducer will most likely be compensated by the errors of other inducers.  The spread or dispersion of the forecasts and reliability of the model is reduced by using an ensemble.
 
A majority voting ensemble technique is applied to all epochs in each model seed. Each model will get ensemble result. Finally using these five model seed majority results once again ensemble will be performed to get the final performance. 

![image](https://user-images.githubusercontent.com/87181929/163737685-a73770bf-5f74-4409-b791-cfd7de8e17c7.png)
