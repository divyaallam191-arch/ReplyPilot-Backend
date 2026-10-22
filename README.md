# ReplyPilot Backend

The backend for ReplyPilot, an AI-powered email reply generator. It is built using Spring Boot and integrates Google's Gemini API to generate email replies based on the provided email content and selected tone.

## Features

- Generates email replies using the Gemini API.
- Accepts email content and a selected tone through a REST API.
- Returns the generated reply to the client.
- Connects the React frontend and browser extension to the AI service.

## Technologies Used

- Java
- Spring Boot
- REST API
- Google Gemini API
- Maven

## API Endpoint

**Generate Email Reply**

`POST /api/email/generate`

Accepts the email content and preferred tone, then returns the generated reply.

## Run Locally

Clone the repository:

```bash
git clone https://github.com/divyaallam191-arch/ReplyPilot-Backend
cd email-writer-sb
```

Configure the required Gemini API settings, then run the application on Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

The application runs on `http://localhost:8080` by default.

## Related Repositories

- [ReplyPilot Live Demo](https://replypilot-frontend.onrender.com)
- [Frontend Repo](https://github.com/divyaallam191-arch/ReplyPilot-Frontend)
- [Browser Extension Repo](https://github.com/divyaallam191-arch/ReplyPilot-Extension)
