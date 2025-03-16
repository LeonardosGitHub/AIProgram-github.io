---
layout: post
author: Leonardo
tags: [cscc]
---

### [SurvivalOfTheBestFit - bias]

For this week, I completed the game here: [Survival of the Best Fit](https://www.survivalofthebestfit.com/.)

1. What was the motivating factor or factors during the game which resulted in the
integration of a Machine Learning model to evaluate job candidates through automated
resume review?
    - The game wanted to hire more talented employees in a shorter amount of time. The manual hiring process was going too slow so the idea of using Maching Learning was proposed.
2. What “good” situations existed in the game?
    - Good situations examples were that the company was growing and the need for talented employee's was needed.  Using ML to help find talented employees I think was a good idea.
3. What “bad” situations existed in the game?
    - Bad situations - not allowing enough time to evaluate new employees. Not providing enough non-bias'd data to the ML training. Not monitoring what the ML was doing and allowing it to make 100% of the decisions. 
4. How would you advise the business leader about when and how to implement a Machine Learning model to automate or improve the throughput of a hiring process?
    - I think using ML in a crawl, walk, run model would be best served; also some checks and balances put into place as the ML is put into production.
        - Crawl - provide data to the ML model to train the model. Compare manual hiring decisions with what the model would have proposed. Provide feedback into the model on the differences between manual and ML decisions.
            - Use another ML to find different aspects of each applicant to identify trends in your decisions to see if bias exists in the manual process
        - Walk - use ML to provide a recommendation of an applicant; review what the ML provided against a sampling of applicants. Provide feedback to the ML to retrain as needed
        - Run - you may never reach this point where you trust ML to make the decision 100%. I would recommend you always review the recommendations of the ML model. 