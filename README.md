# Whatsapp Chat Analysis
Deployed the app on Streamlit Cloud: https://whatsapp-chats-analysis-project.streamlit.app/
### Note: Please copy the app URL and paste it in a new tab for smooth functioning of the app.

This project provides tools for analyzing WhatsApp chat exports. Using Python, it can process chat logs to generate insightful statistics and visualizations. Features include top statistics, monthly timeline, daily timeline, activity maps, most busy users, wordcloud, most common words, emoji analysis, and conversation starters. Ideal for understanding communication patterns and extracting meaningful insights from WhatsApp conversations in both user level and group level.
### Note: Python version 3.7.0 has been used for this project.
### Note: Download the dataset from Whatsapp in AM/PM format.
## Top Statistics
WhatsApp Chat Analysis tool offers key statistics to help you understand your conversations better. It provides the total number of messages exchanged, the total word count, the number of media files shared, and the total links shared. These metrics give a comprehensive overview of chat activity and engagement in both user level and group level.
#### Top Statistics of a group chat
![w1](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/0f1f545d-c701-4ab1-a4c8-4f2e8d85a870)
## Monthly Timeline
The Monthly Timeline feature generates a line chart to visualize chat activity over time, displaying message frequencies on a month-by-month basis both user level and group level. This allows users to identify trends, peaks, and periods of high or low activity within the chat. By analyzing these patterns, users can gain insights into the dynamics and evolution of their WhatsApp conversations.
#### Monthly Timeline of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/8855ea75-7d2b-428b-8e1f-0f0eaaa4a24f)
## Daily Timeline
The Daily Timeline Analysis feature generates a line chart that visualizes message frequency on a day-by-day basis both user level and group level. This helps in identifying trends and patterns in chat activity over time. By analyzing daily fluctuations, users can gain insights into periods of high and low engagement within their WhatsApp conversations. This feature is essential for understanding temporal communication dynamics.
#### Daily Timeline of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/45718e83-3da6-492f-9f80-5e9827bf2408)
## Activity Map
The WhatsApp Chat Analysis project includes an Activity Map feature, providing visual insights into chat patterns. It features bar charts highlighting the busiest days and months, along with a heatmap showing user activity throughout the week both user level and group level. These visualizations help identify peak communication times and overall chat activity trends, offering a comprehensive view of chat dynamics.
#### Activity Maps of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/cbac612f-05ae-4708-a7ba-101eb9b60815)
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/862e6e55-14cc-470c-af90-9bdf795edc00)
## Most Busy Users
The "Most Busy Users" feature analyzes WhatsApp chat logs to identify the participants with the highest message counts in only group level. It generates a bar chart visualizing the top contributors by total message count and provides a detailed dataframe listing the busy percentage for each user. This helps in understanding the most active participants in the conversation.
#### Most Busy Users of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/d21dbc90-394b-4fb9-873c-8e4a0d13da9e)
## WordCloud
The WhatsApp Chat Analysis project includes a feature for generating word clouds both user level and group level, which visually represent the most frequently used words in a chat. By processing the chat logs, it highlights key terms and their prominence, offering an intuitive way to grasp the main topics and themes discussed. This feature is especially useful for quickly understanding the essence of conversations and identifying common words and phrases. Stop words and common phrases are filtered out to highlight meaningful content, providing a clearer understanding of communication patterns.
#### WordCloud of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/478f79a6-d5ef-4151-ae66-d4b511664eaf)
## Most Common Words
This feature analyzes the most frequently used words in a WhatsApp chat export and visualizes the results in a bar chart for both user level and group level. It helps identify common topics and recurring themes in conversations. Stop words and common phrases are filtered out to highlight meaningful content, providing a clearer understanding of communication patterns.
### Note: Please refer to `stop_hinglish.txt` file provided above for hinglish stopwords. You can edit this file to include more stopwords as per your convenience.
#### Most Common Words of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/6c22f223-8131-40d2-b2eb-0538e79ab036)
## Emoji Analysis
This module within the WhatsApp Chat Analysis project focuses on identifying and counting the emojis used in chat exports for both user level and group level. It generates a DataFrame displaying each emoji along with its frequency of use.`urlextract` library has been used for this purpose. This feature helps in understanding the emotional tone and expressiveness of the conversations, offering a unique perspective on communication patterns.
#### Emoji Analysis of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/d4f2d8d8-5338-40fd-ab7d-3b67ece6e2b7)
## Conversation Starters
This feature identifies conversation starters in WhatsApp chats, displaying a bar chart of users who initiated conversations within 30-minute gaps for only group level. The analysis highlights the frequency and count of these initiators, providing insights into user engagement and interaction dynamics. Ideal for understanding who drives conversations and overall chat activity.
#### Conversation Starters of a group chat
![image](https://github.com/Tejas320/Whatsapp_chat_analysis/assets/73283098/0d47d28f-b6ba-4a18-a31f-8e226efcb848)







