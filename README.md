# COVID-Chat-Bot
A Q&amp;A Bot Utilizing TF-IDF and Cosine Similarity to Answer Non-Numerical Questions About COVID-19

My final capstone project. Faced with so much misinformation out there, and the myrid of locations in tying to find it, I wanted to design something where people could answers to any questions they had about COVID. The bot scrapes the CDC, WHO, ECDC, and FDA faq sites, scores the user input and compares it to the vectorized questions in the database. It then returns (3) possible question matches, since some are too similar to distiguish.
