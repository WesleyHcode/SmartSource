# SmartSource

A way to search, reference, and check sources through a background analysis. Uses both NewsAPI and GroqAPI in order to have news articles and an AI agent, respectively.
## How to use:  
Visit https://wesleyhcode.github.io/SmartSource/  
## Search:  
A text box. Type in any query and hit "Search" or "Clear" to clear results. 
## Ai Says:  
An AI report of at most three of the most relevant new stories found. 

## How I made it:
There is a front-end (HTML, CSS, JS) and a back-end (Python). I coded a really basic website with newspaper-y visuals using the HTML and CSS. The JS is able to save the user's articles in case they reload and format each article card. The Python is there to talk to each API. More can be detailed in my info sidebar.

## Sections:  
Title, description, link - self explanatory.  
Leanings - Left, lean left, lean right, right - AI detected biases.  
Author: The author of the work.  
Date: The date published.  
Perspective - Things the AI thinks is the best summary of the viewpoints found in the article.  
Ommitted Context - shows what the AI thought was left out.   

## APIS USED:  
newsapi  
groq, openai/gpt-oss-120b  

## Available features I'm thinking of inplementing or have inplemented:  
- AI can determine if a source supports Left or Right viewpoints (DONE!). 
- Author or organization's previous reporting (IN PROGRESS). 
- Comparison between different sources (IN PROGRESS). 
- Auto citing feature (IN PROGRESS). 

<img width="1043" height="522" alt="Screenshot 2026-11-01 at 10 55 17 PM" src="https://github.com/user-attachments/assets/3efa336f-9320-4c3c-8f5a-5acd95d95c6f" />
An example of a news article

## Bug fixing and other problems:
- AI is sometimes wrong, may need some more instruction

## Dangers:  
AI could mistake sourcing or make bogus analysis.  

Last updated: October 26th, 2026. 

