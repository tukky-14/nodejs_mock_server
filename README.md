# json-server

-   起動

    ```
    npm run json-server
    ```

-   GET

    ```
    curl http://localhost:3000/user
    ```

-   POST
    ```
    curl http://localhost:5000/user -X POST -H 'Content-Type: application/json' -d '{ "id": 1, "name": "たなかはなこ" }'
    ```
