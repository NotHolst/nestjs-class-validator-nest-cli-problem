
# Repro for class-validator problem

This project was created with nest cli, and the user module was implemented using nest cli (nest g resource user)

After that i setup global validation pipe and swagger/openAPI docs in main.ts

I also added the "@nestjs/swagger" plugin to nest-cli.json

When calling the POST /user with the example body in swagger i get the following error

```
{
"statusCode": 400,
"message": [
"an unknown value was passed to the validate function"
],
"error": "Bad Request"
}

```