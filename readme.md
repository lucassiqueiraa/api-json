### Api com Json-Server

* Json-server

#### Criando projeto simpls

* cria um projeto node
```  
npm init -y
```

* instala um dependência json-server
```
npm install json-server
```

* criando um arquivo
```
banco.json
```

* modelo de estrutura
 ```
 {
    "categoria": [
        { "id": 1, "nome": "console" },
        { "id": 2, "nome": "jogos" }
    ]
 }
 ```

* rodar o projeto
```
npx json-server banco.json
```

#### Endpoint

* get
http://localhost:3000/categoria <br>
* id <br>
* title <br>

* post
http://localhost:3000/categoria <br>
body:{ <br>
    * id <br>
    * title <br>
}<br>

* put
http://localhost:3000/categoria/id
body:{
    * title
}

* delete
http://localhost:3000/categoria/id


http://localhost:3000/user
http://localhost:3000/cliente
