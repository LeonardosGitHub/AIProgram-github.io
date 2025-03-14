---
layout: post
author: Leonardo
tags: [cscc]
---

### [Natural Language Processing - LLMs]

- This week was a little more free form compared to Q & A from last weeks
- Week 5 asked to download a text from [Project Gutenberg](https://www.gutenberg.org/) and use it as a basis to interact with a LLM
    - I chose [Adventures of Huckleberry Finn](https://www.gutenberg.org/ebooks/76) and used [ChatGPT LLM](https://chatgpt.com/)

- My text based problem: What are the top 5 words used in the text?
    - My assumption: The LLM would be able to readily find and preset this data quickly and easily
    - The LLM did respond quickly with the list below:
        - "and" – 6,439 times
        - "the" – 5,098 times
        - "I" – 3,607 times
        - "a" – 3,261 times
        - "to" – 3,023 times
    - What suprised me is after it gave the words above it then stated:
        - These are common function words. Let me know if you’d like a list of the most frequent meaningful words instead! ​​
    - I really hadn't thought about it but most common words are somewhat uninteresting, those will probably be among the top 5 words in any book or text.  I thought it would be good to know what the top 5 meaningful words are in the text, so I asked, and here's the result:
        - The top five most frequently used meaningful words in the uploaded text are:
            - "says" – 638 times
            - "got" – 611 times
            - "no" – 596 times
            - "now" – (previously miscounted as "t", filtering fixed)
            - "come" – (previously miscounted as "s", filtering fixed)
        - Let me refine this further to ensure accuracy and remove any non-words. ​​
        - The refined top five most frequently used meaningful words in the uploaded text are:
            - "says" – 638 times
            - "got" – 611 times
            - "no" – 596 times
            - "see" – 477 times
            - "well" – 409 times
        - Let me know if you need further analysis! ​
    - So the LLM actually gave me more meaningful words but then noticed a mistake it made and refined the list again.  I asked the LLM what it meant by "previously miscounted as "t", filtering fixed" because I wondered why it refined it's own list and this was the response:
        - Great question! When I first extracted the top five most frequently used meaningful words, the results included "t" and "s" as some of the most common words. However, these are not actual words in English; they likely appeared due to how contractions and possessives were tokenized in the text.
        For example, in Adventures of Huckleberry Finn, contractions like:
            "can't" → might have been split into "can" and "t"
            "it's" → might have been split into "it" and "s"
        This happens because when breaking down the text, apostrophes in contractions can cause issues where the trailing parts (like "t" from "can't") are treated as standalone words. Similarly, possessives like "Huck’s" might cause "s" to appear frequently.

            After noticing this, I applied a filter to remove single-character words, which corrected the issue. This allowed me to refine the list and ensure only meaningful words appeared in the final results.

            Let me know if you’d like a deeper dive into the text processing methods!
    - This concluded my interaction but what's somewhat impressive and surprising is that the LLM anticpated what my next questions might be and presented it the question after the answer.  I thought that the LLM correcting itself was also surprising, it came up with one answer but then figured out maybe they made a mistake and presented a new answer. Not all all what I expected to happen. 