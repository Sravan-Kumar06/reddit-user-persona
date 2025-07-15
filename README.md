Reddit User Persona Generator - README Summary

1. **Project Description**
   - This project takes a Reddit user’s profile URL and generates a detailed user persona.
   - It analyzes posts and comments to identify traits such as:
     - Age range
     - Gender (if identifiable)
     - Occupation or hobbies
     - Interests and subreddits
     - Writing tone, cultural/political views, and personality traits
   - The output is saved as a `.txt` file with citations to specific Reddit content.

2. **Technologies & Tools Used**
   - **Platform**: Google Colab
   - **Programming Language**: Python 3
   - **Libraries**: praw, dotenv, os, re, requests
   - **LLM Provider**: [OpenRouter] (used as a free alternative to OpenAI, Since openai requires a paid subscription for the required project , I have researche and found a free alternative openrouter)

3. **API Key Handling & Security**
   - Environment variables are stored in a `.env` file (NOT pushed to GitHub).
   - Sensitive credentials like:
     - REDDIT_CLIENT_ID
     - REDDIT_CLIENT_SECRET
     - USER_AGENT
     - OPENROUTER_API_KEY
   - These must be added manually by each user.

4. **Output**
   - Each user profile produces a `.txt` file stored in the `sample persona output` folder.
   - File naming format: `<username>_persona.txt`
   - Outputs include analyzed traits with cited Reddit URLs.# reddit-user-persona
