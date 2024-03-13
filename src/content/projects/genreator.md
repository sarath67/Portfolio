---
title: 'Genreator'
description: 'Exploring a Discord bot that suggests movies based on users recent messages on discord.'
---



In this post, we will delve into a Discord bot project designed to recommend movies based on the sentiment of users recent messages. Utilizing natural language processing (NLP) techniques, the bot assesses the emotional tone of the text and suggests appropriate movie choices accordingly.



The Discord bot is built using Python and leverages the Discord API for communication. It incorporates the NLTK library for sentiment analysis and interacts with the OMDB API to fetch movie data. Lets break down the key components and functionalities:



The bot employs the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from NLTK. It evaluates the emotions expressed in users messages and categorizes them into five sentiment classes: Happy, Sad, Angry, Surprise, and Fear.



Based on the dominant sentiment detected, the bot selects a set of movies from predefined lists corresponding to different emotional states. For example, if a users messages convey happiness, the bot suggests movies known for eliciting joy. Similarly, it recommends appropriate movies for other emotional states like sadness, anger, surprise, or fear.



Upon receiving a specific command shini movie, the bot retrieves the users recent messages within the server. It then analyzes the sentiment of these messages and sends a direct message to the user with three movie recommendations matching their current mood.



By combining sentiment analysis with movie recommendations, this Discord bot offers an engaging and personalized experience for users. It demonstrates the potential of NLP techniques in understanding and responding to human emotions in digital interactions. This project not only showcases the power of Python libraries like NLTK and Discord.py but also highlights the creative applications of AI in enhancing user experiences within online communities.
