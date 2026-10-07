1) Telegram Research Chatbot - Chatbot embedded within the Telegram app which uses Tavily API to do up-to-date research on the enquiry.
<img width="1664" height="1224" alt="Telegram_Research_Chatbot" src="https://github.com/user-attachments/assets/27bd04c2-4974-4d7c-a25e-1f1b467d76f3" />
<img width="300" alt="Telegram_Research_Chatbot_Example" src="https://github.com/user-attachments/assets/b27ca952-3c52-4772-8d83-2c4a7250a31f" />

2) Content Repurposing Engine - User sends a link to a Youtube video into the Telegram chat, an AI tool then transcribes the video and feeds it to Gemini to advise on how to make short form content.
<img width="2316" height="1290" alt="Content_Repurposing_Engine" src="https://github.com/user-attachments/assets/561c8b3d-cb30-4305-9a87-e15b6cacd2fd" />
<img width="300" alt="Content_Repurposing_Engine_Example" src="https://github.com/user-attachments/assets/ad4b21e1-1c60-4729-9e75-83ba90c79e9d" />

3) AI Competitor Identifier - User sends a link to an Artificial Intelligence company website, Jina.AI then cleans the information into an LLM friendly markdown fed into Gemini to identify key information such as key features and pricing model before cleaning/formatting then sending it back to the user. 
<img width="3718" height="1626" alt="AI_Competitor-Identifier" src="https://github.com/user-attachments/assets/90574ce9-eb78-4501-8146-cc1493fec8da" />
<img width="300" alt="AI_Competitor-Identifier_Example" src="https://github.com/user-attachments/assets/76826521-c349-4a41-89ca-392c331522ad" />

4) Autonomous Job Opportunity Finder - Schedule trigger searches Hacker News (Y Combinator) every 59 minutes for new jobs, checks they have not been found before (up to 5), feeds it to Gemini which then rates it out of 10. Jobs with a high intent (score of 8 or high) are cleaned before being sent to user's Telegram, notifying the user.
<img width="4020" height="1576" alt="Autonomous_Job_Opportunity_Finder" src="https://github.com/user-attachments/assets/e6fa214e-b838-4a3e-afb1-6baa2a39a59a" />
<img width="300" alt="Autonomous_Job_Opportunity_Finder_Example" src="https://github.com/user-attachments/assets/18ad7df0-f690-4501-a037-5ed22275c51e" />

5) Voice-To-Action Agent - Activated after sending a voice message on Telegram to chatbot. Gemini transcription node transcribes the message (if not text already) before sending it to agent node which decides what actions to take. User can request multiple: to-do tasks to be added to their Microsoft To-Do app, notes to be written in a separate 'Personal notes' chat in the Telegram app and for events to be made on their Google Calendar, all within the same voice message. After doing all tasks requested, a confirmation message listing tasks performed is sent to user's Telegram app.
<img width="3060" height="1674" alt="Voice-To-Action_Agent" src="https://github.com/user-attachments/assets/36458495-be0f-4d57-9ab9-0ac6c8ecae1c" />
<img width="300" alt="Voice-To-Action_Example" src="https://github.com/user-attachments/assets/7f230883-6dbb-46a0-a80d-8cac4251e90e" />
