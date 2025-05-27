# Firestore Schema – Flowivity Smart Planner MVP

## Collection: planner_tasks

| Field       | Type      | Description                          |
|-------------|-----------|--------------------------------------|
| userId      | string    | Firebase Auth UID of the user        |
| task        | string    | Task title                           |
| category    | string    | One of: focus, goal, schedule        |
| duration    | number    | Time block length in minutes         |
| status      | string    | One of: incomplete, complete         |
| timestamp   | timestamp | Time of task creation                |
