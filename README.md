D:\kapil\Adaptive_Test\
├── app/                 # Main code
│   ├── __init__.py
│   ├── main.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── question.py
│   │   └── session.py
│   ├── services/
│   │   ├── __init__.py
│   │   ├── db.py        # seed_questions yaha
│   │   ├── adaptive.py
│   │   └── llm.py
│   └── routes/
│       ├── __init__.py
│       └── test.py
├── data/                # JSON files
│   └── questions.json   # 20 questions yaha
├── seed.py              # <-- Yaha add kiya (root mein)
├── .env
├── .gitignore
└── requirements.txt
