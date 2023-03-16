# ILT Cloud 2 Bangkit Demo

## Simple RESTFul API

Create the simple RESTFul API using Node.js Natively and Hapi Framework with the specification:

| Method | Path          | Response Code | Body | Description         |
| ------ |---------------| ------------- | ---- |---------------------|
| POST   | /contacts     | 201 | JSON | Create new contacts |
| GET    | /contacts     | 200 | JSON | List of contacts    |
| DELETE | /contacts/:id | 200 | JSON | Delete contacts     |

User data structure:

```json
{
  "id": "1",
  "name": "Rony Setyawan",
  "email": "rony.setyawan@telkom.co.id",
  "phone": "082124606606"
}
```
Server options:
 - `port`: 3000
 - `host`: localhost


