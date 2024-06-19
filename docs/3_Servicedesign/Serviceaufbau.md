---
layout: default
title: 3.2 Servicedesign
parent: 3. Service Design
nav_order: 1
---

# 3.2 Serviceaufbau


## Verzeichnisaufbau

```
project-root/

├── Dockerfile

├── README.md

├── app/

│   ├── __init__.py

│   ├── extensions.py

│   ├── config.py

│   ├── gallery/

│   │   ├── __init__.py

│   │   ├── models.py

│   │   ├── routes.py

│   │   └── utils.py

│   ├── image/

│   │   ├── __init__.py

│   │   ├── models.py

│   │   ├── routes.py

│   │   └── s3_utils.py

│   ├── face_recognition/

│   │   ├── __init__.py

│   │   ├── routes.py

│   │   └── recognition_utils.py

│   ├── auth/

│   │   ├── __init__.py

│   │   ├── models.py

│   │   ├── routes.py

│   │   └── auth_utils.py

│   └── models/

│       ├── user.py

│       ├── photo.py

│       └── event.py

├── compose.yaml

└── requirements.txt
```

