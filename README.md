## Overview
This project involves analyzing the Telegram chat history between myself and my boyfriend. The goal is to uncover interesting patterns, sentiments, and dynamics in our communication using various data analysis and machine learning techniques. This project is not only a fun exploration of our personal interaction but also an opportunity to apply and showcase data science skills.

## Data Description
The data used in this project is exported from Telegram in JSON format. It includes details such as message ID, date and time, sender information, and the message text itself. The data is structured as follows:

{
 "name": "Person's Name",
 "type": "personal_chat",
 "id": numeric_id,
 "messages": [
  {
   "id": message_id,
   "type": "message",
   "date": "YYYY-MM-DDTHH:MM:SS",
   "from": "Sender Name",
   "from_id": "user_id",
   "text": "Message Text"
  }
  ...
 ]
}

## Features of Analysis
Basic analysis including the total number of messages, the proportion of messages sent by each user, the line graph representing message frequency over time

Language detection: 2% of our conversations were in Eng, the rest in Russian. 

Message Frequency Analysis: Examines the frequency of messages to identify patterns over different time frames.

Word Cloud Generation: Creates visual representations of the most common words used in our conversations.

Emoji Analysis: Focuses on the usage patterns of emojis in our conversations.

Response Time Analysis: Calculates the average time taken by each of us to respond to the other's messages.

Message Length Analysis: Looks at the average length of messages sent by each participant.


## Tools and Technologies
Python for data processing and analysis.
Libraries such as Pandas for data manipulation.
Matplotlib, WordCloud for data visualization.
Langdetect for language detection.
Emoji library for emoji analysis.


## Ethical Considerations and privacy
All analysis respects the privacy and sensitivity of personal communication. The project is conducted with the consent of all parties involved, and findings are not shared publicly in a manner that compromises privacy. The exported_chat.json is not included here since it contains over 100000 private messages. 

## Limitations
I couldn't figure out how to work with natasha/dostoyevsky libraries for proper sentiment analysis in Russian. 
