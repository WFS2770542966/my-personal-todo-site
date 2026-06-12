# Wan Fangshuo — Personal Website & Todo App

## Student Info

| Field         | Value            |
|---------------|------------------|
| Name          | Wan Fangshuo     |
| Chinese Name  | 万方硕           |
| Student ID    | 20242227         |
| Hobby         | Reading          |
| Study Approach| Machine Learning |

![Photo](my-site/myphoto.png)

## URLs

| Application    | URL                          |
|----------------|------------------------------|
| Personal Site  | http://localhost:8080        |
| Todo App       | http://localhost:8000        |

## Tech Stack

- **Personal Site**: Static HTML + CSS, served by Nginx in Docker
- **Todo App**: [prologic/todo](https://github.com/prologic/todo) — lightweight Go-based todo app
- **CI/CD**: GitHub Actions → GitHub Container Registry
- **Orchestration**: Docker Compose

## Quick Start

```bash
# Start both services
docker-compose up -d

# View logs
docker-compose logs -f

# Stop
docker-compose down
```

## Project Structure

```
.
├── my-site/               # Personal website source
│   ├── index.html
│   ├── style.css
│   ├── myphoto.png
│   └── Dockerfile
├── .github/workflows/     # CI/CD pipeline
├── docker-compose.yml     # Service orchestration
└── README.md
```

---

*Academic Cooperation · School of Computer Science and Engineering, North Minzu University & Software Engineering, College of Arts, Media and Technology, Chiang Mai University · Academic Year 2024*
