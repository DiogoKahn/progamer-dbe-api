# Projeto de estudo de Digital Business Enablement
Grupo:

Diogo Giarranti Kahn | RM: 92928
Pedro Chueiri | RM: 93939
Mateus da Costa Leme | RM: 93480

# Como utilizar
Cadastro de Perfil:
`POST` progamer/api/perfil

**Exemplo de Entrada** 
```js
{
    "name": "Joe Doe",
    "email": "test@mail.com",
    "profile": "Administrador",
    "password": "abcd1234"
}
``` 
Cadastro de Setup:
`POST` progamer/api/setups

**Exemplo de Entrada** 
```js
{
    "name": "test setup",
    "descricao": "RTX 3090, i9 10900k, 64gb ram, 2tb ssd",
    "games": "Cyberpunk 2077, Valorant, The Witcher 3",
    "price": 10000,
    "file": 'https://i.pravatar.cc/350'
}
``` 

### Retornar Perfils

`GET` progamer/api/profile/{id}

**Exemplo de Resposta** 
```js
{
    "name": "Joe Doe",
    "email": "test@mail.com",
    "profile": "Administrador",
    "password": "abcd1234"
}
```

### Retornar Setups

`GET` progamer/api/profile/{id}

**Exemplo de Resposta** 
```js
{
    "name": "test setup",
    "descricao": "RTX 3090, i9 10900k, 64gb ram, 2tb ssd",
    "games": "Cyberpunk 2077, Valorant, The Witcher 3",
    "price": 10000,
    "file": 'https://i.pravatar.cc/350'
}
```