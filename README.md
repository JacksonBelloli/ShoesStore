## Sobre e Autor
//

## INSTALAÇÃO
//

## ENDPOINTS
    ### Vendedores
        ### Modelo de Dado
            {
                nome : String,
                codigo : Number,
                cpf : Number,
                endereco : String,
                cidade : String,
                estado : String,
                cep : Number,
            }
        ### GET
            #### /vendedores
            #### Exemplo de resposta
                 {
                    "_id": "609d62b2bea4c22fde31734b",
                    "nome": "Roger",
                    "codigo": 5555,
                    "cpf": 78965412348,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-13T17:32:34.215Z",
                    "updatedAt": "2021-05-17T00:53:51.344Z",
                    "__v": 0
                }
            #### ?cpf
        ### POST
            #### /vendedores
            #### Exemplo de resposta
                {
                    "_id": "609d62b2bea4c22fde31734b",
                    "nome": "Roger",
                    "codigo": 5555,
                    "cpf": 78965412348,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-13T17:32:34.215Z",
                    "updatedAt": "2021-05-17T00:53:51.344Z",
                    "__v": 0
                }
        ### PUT
            #### /vendedores
            #### Exemplo de resposta
                {
                    "_id": "609d62b2bea4c22fde31734b",
                    "nome": "Roger",
                    "codigo": 5555,
                    "cpf": 78965412348,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-13T17:32:34.215Z",
                    "updatedAt": "2021-05-17T00:53:51.344Z",
                    "__v": 0
                }
        ### DELETE
            #### /vendedores
            #### Exemplo de resposta
                {
                    "_id": "609d62b2bea4c22fde31734b",
                    "nome": "Roger",
                    "codigo": 5555,
                    "cpf": 78965412348,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-13T17:32:34.215Z",
                    "updatedAt": "2021-05-17T00:53:51.344Z",
                    "__v": 0
                }
    ### Clientes
        ### Modelo de Dado
            {
                nome : String,
                data_nasc : Date,
                cpf : Number,    
                endereco : String,
                cidade : String,
                estado : String,
                cep : Number,
            }
        ### GET
            #### /clientes
            #### Exemplo de resposta
                 {
                    "_id": "60a1bf04688783423cc66e2b",
                    "nome": "Roger",
                    "data_nasc": "1999-02-23T00:00:00.000Z",
                    "cpf": 33365412378,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-17T00:55:32.606Z",
                    "updatedAt": "2021-05-17T00:57:16.607Z",
                    "__v": 0
                }
            #### ?cidade
        ### POST
            #### /clientes
            #### Exemplo de resposta
                {
                   "_id": "60a1bf04688783423cc66e2b",
                    "nome": "Roger",
                    "data_nasc": "1999-02-23T00:00:00.000Z",
                    "cpf": 33365412378,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-17T00:55:32.606Z",
                    "updatedAt": "2021-05-17T00:57:16.607Z",
                    "__v": 0
                }
        ### PUT
            #### /clientes
            #### Exemplo de resposta
                {
                    "_id": "60a1bf04688783423cc66e2b",
                    "nome": "Roger",
                    "data_nasc": "1999-02-23T00:00:00.000Z",
                    "cpf": 33365412378,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-17T00:55:32.606Z",
                    "updatedAt": "2021-05-17T00:57:16.607Z",
                    "__v": 0
                }
        ### DELETE
            #### /clientes
            #### Exemplo de resposta
                {
                    "_id": "60a1bf04688783423cc66e2b",
                    "nome": "Roger",
                    "data_nasc": "1999-02-23T00:00:00.000Z",
                    "cpf": 33365412378,
                    "endereco": "Rua dos atletas",
                    "cidade": "Criciuma",
                    "estado": "SC",
                    "cep": 88816510,
                    "createdAt": "2021-05-17T00:55:32.606Z",
                    "updatedAt": "2021-05-17T00:57:16.607Z",
                    "__v": 0
                }
    ### Calcados
        ### Modelo de Dado
            {
                modelo : String,
                marca : String,
                tamanho : Number,
                quantidade : Number,
            }
        ### GET
            #### /calcados
            #### Exemplo de resposta
                 {
                    "_id": "609efa8b7dd9452460cb9b87",
                    "modelo": "Shox",
                    "marca": "Nike",
                    "tamanho": 35,
                    "quantidade": 10,
                    "createdAt": "2021-05-14T22:32:43.618Z",
                    "updatedAt": "2021-05-14T22:32:43.618Z",
                    "__v": 0'
                }
            #### ?marca
        ### POST
            #### /calcados
            #### Exemplo de resposta
                {
                   "_id": "609efa8b7dd9452460cb9b87",
                    "modelo": "Shox",
                    "marca": "Nike",
                    "tamanho": 35,
                    "quantidade": 10,
                    "createdAt": "2021-05-14T22:32:43.618Z",
                    "updatedAt": "2021-05-14T22:32:43.618Z",
                    "__v": 0'
                }
        ### PUT
            #### /calcados
            #### Exemplo de resposta
                {
                    "_id": "609efa8b7dd9452460cb9b87",
                    "modelo": "Shox",
                    "marca": "Nike",
                    "tamanho": 35,
                    "quantidade": 10,
                    "createdAt": "2021-05-14T22:32:43.618Z",
                    "updatedAt": "2021-05-14T22:32:43.618Z",
                    "__v": 0'
                }
        ### DELETE
            #### /calcados
            #### Exemplo de resposta
                {
                    "_id": "609efa8b7dd9452460cb9b87",
                    "modelo": "Shox",
                    "marca": "Nike",
                    "tamanho": 35,
                    "quantidade": 10,
                    "createdAt": "2021-05-14T22:32:43.618Z",
                    "updatedAt": "2021-05-14T22:32:43.618Z",
                    "__v": 0'
                }