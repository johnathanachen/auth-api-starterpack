# UPDATE Schedule

## Request

    PUT /api/v1/users/schedules/{schedule name}/edit

### Request Body
```json
{
    "programName": "Super"
}
```

## Response
```json
{
    "result": {
        "name": "Shredded",
        "programName": "5x5",
        "userId": "5bbae8977718cc8579986bed",
        "username": "johnny",
        "logs": []
    },
    "success": "Schedule added"
}
```
