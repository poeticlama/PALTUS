# Practicum Project  
PALTUS team. Report 6

## Links

- Deployment:
- Docs: [README.md](https://github.com/IU-Capstone-Project-2025/PALTUS/blob/main/README.md), [api docs]()
- Design: [Figma](https://www.figma.com/proto/rvNoC6oOC2Xe5y7yWIhLuN/Demo-visuals?node-id=0-1&t=DavTpLzLzLBFOWSe-1)
- Demo:
- Kaiten board: 
  

## Final deliverables

### Project overview
PALTUS is an AI-powered self-learning platform designed to change the way of personalized education. The platform addresses key challenges in modern e-learning by providing:

- Adaptive Learning: AI-driven personalization that adjusts content and pace based on user choices and preferences.
- Flexible Course Creation: Intuitive tools for educators and users to build, modify, and delete custom courses.
- Gamification: Reward systems, achievements, and daily streaks to maintain motivation and track progress.
- Knowledge Review Tools: Repetition and quizzes to enhance long-term retention of learned material.

By combining AI-powered recommendations with user-aimed design, PALTUS creates a learning experience that adapts to individual needs while keeping users engaged through interactive and gamified elements.
### Features
- Authorization
- Registration
- Add course
- Edit course
- Delete course
- Mark subtopics as done/undone
- Progress bar for course completion
- Add notes for subtopics
- Interaction with AI-model for questions and misundrstandings
- Learnt material revise through quizzes
- User experience level via achievements
- Awards for completing challenges
### Tech stack
**Frontend**

- Vue.js: Reactive framework for building intuitive interfaces
- Pinia: To mantain a global state of a frontend app
- Axios: For HTTP requests

**Backend**

- Spring Boot: Robust backend framework for RESTful APIs
- PostgreSQL: Relational database for structured data storage
### Setup instructions
Run project via `docker compose --profile front-dev up`. You should get [GigaChat API key](https://developers.sber.ru/portal/gigachat-and-api) to run the application. See [.env.example](https://github.com/IU-Capstone-Project-2025/PALTUS/tree/main/.env.example) for configuration.

## Presentation draft

[Google Presentation](https://docs.google.com/presentation/d/1lrC7sYqLeRxuk9y8BXHxn9HLMQ02L2u9C7xS4bjsmcU/edit?usp=sharing)

## Weekly commitments

### Individual contribution of each participant

- Sergey Knyazkin
  - d
  - 
- Ramazan Gizamov
  - Design finished - [Figma](https://www.figma.com/proto/rvNoC6oOC2Xe5y7yWIhLuN/Demo-visuals?node-id=0-1&t=DavTpLzLzLBFOWSe-1).
  - [Report for week 5](https://github.com/poeticlama/PALTUS/new/master/content/docs/2025/PALTUS/week5.md).
  - [Google Presentation](https://docs.google.com/presentation/d/1lrC7sYqLeRxuk9y8BXHxn9HLMQ02L2u9C7xS4bjsmcU/edit?usp=sharing).
- Aidar Sarvartdinov
  - d
  - 
- Igor Dubrovsky
  - d
  - 
- Amir Fayzullin
  - d
  - 

## Plan for Next Week

- Code cleaning
- Fix bugs
- Finish presentation
- Add adaptive layouts

## Confirmation of the code’s operability

We confirm that the code in the main branch:
Run via docker-compose.
