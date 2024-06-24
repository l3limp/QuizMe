# QuizMe - GenAI Quiz Generator
Website hosted [here](https://l3limp.github.io/QuizMe)

Backend [link](https://github.com/l3limp/quizme-backend)

## Upload a PDF to generate questions based on the content

## Tech used
### Frontend (Deployed on Github pages)
- Flutter web

### Backend (Deployed on render.com)
- Python
- CrewAI

## Challenges faced
### Prompts for the CrewAI agents
- Creating prompts for the [CrewAI](https://www.crewai.com/) agents to generate the appropriate response
- Sometimes the agents hallucinate and generate random questions
### Deploying the backend API service
- Initially I thought to deploy on AWS, but versioning constraints proved to be a blocker
- Finally hosted the backend on [render.com](https://render.com/)
- It needs time to warm up when not used for some time, and may cause timeouts

P.S. 
The quiz generation may not work initially, as the API service needs to warm up. In this case, you will have to request again to generate the quiz.
