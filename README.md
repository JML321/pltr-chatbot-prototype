## Project for Palantir and recruiting

Heavily based off this github: https://github.com/mayooear/gpt4-pdf-chatbot-langchain

Differences from that project:
1) used data scraped from a website (i.e. 95% of Palantir urls containing "docs" or "impact" in the url), not a pdf
2) used HNSWLib, not Pinecone
3) inferior model, not gpt-4 but gpt-3.5-turbo
4) when sources returned for an answer, the source name is a url to the part of the website where that information came from 
5) returns four sources intead of five

Use this link to see the project live: https://pltr-chatbot-1.herokuapp.com/
