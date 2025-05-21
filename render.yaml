services:
  - type: web
    name: plcc-tutoring
    env: python
    buildCommand: pip install -r requirements.txt
    startCommand: gunicorn --bind 0.0.0.0:$PORT main:app
    envVars:
      - key: PYTHON_VERSION
        value: 3.11.10
      - key: SESSION_SECRET
        generateValue: true
      - key: DATABASE_URL
        fromDatabase:
          name: plcc_db
          property: connectionString

databases:
  - name: plcc_db
    databaseName: plcc
    user: plcc_user
