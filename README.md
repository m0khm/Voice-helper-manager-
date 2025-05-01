# Voice-helper-manager-
Voice helper(manager)

### Дерево проекта

voice-assistant/
│  .env.example
│  docker-compose.yml
│  Dockerfile
│  README.md
│  requirements.txt
├─app/
│  │  __init__.py
│  │  config.py
│  │  main.py          # точка входа aiogram
│  ├─db/
│  │     models.py
│  │     session.py
│  ├─handlers/
│  │     __init__.py
│  │     owner.py
│  │     visitor.py
│  ├─services/
│  │     __init__.py
│  │     calendar.py
│  │     nlu.py
│  │     stt.py
│  │     tts.py
│  └─web/
│        main.py        # FastAPI
│        templates/
│            index.html
│
└─tests/                # pytest-минимумы

