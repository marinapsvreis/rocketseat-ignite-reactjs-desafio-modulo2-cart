## Rocketseat Ignite - Trilha REACT.JS 2021 - Modulo 2 - Desafio 1
### Implementando um carrinho de compras.

![Foto do Projeto Rocketshoes Home](https://i.imgur.com/rMKY2xZ.png)
![Foto do Projeto Rocketshoes Cart](https://i.imgur.com/tjGIFK5.png)

### Comandos para rodar o projeto:

Instalar dependencias: ```yarn```

Rodar o mock da API no JSON Server: ```yarn server```

Rodar o front: ```yarn start```

Rodar os testes: ```yarn test```

### O projeto deve passar nos seguintes testes:


#### Teste components/Header/index.tsx

- Deve ser possivel renderizar o total de produtos diferentes adicionados no carrinho:
```should be able to render the amount of products added to cart```

#### Testes pages/Home/index.tsx

- Deve ser possivel renderizar a quantidade de cada produto adicionada ao carrinho:
```should be able to render each product quantity added to cart```
    
- Deve ser possivel adicionar um produto ao carrinho:    
```should be able to add a product to cart```

#### Testes pages/Cart/index.tsx

- Deve ser possivel aumentar e diminuir a quantidade de um produto no carrinho:
```should be able to increase/decrease a product amount```
    
- Não deve ser possível diminuir a quantidade de um produto no carrinho quando a quantidade for igual a 1:
```should not be able to decrease a product amount when value is 1```

- Deve ser possivel remover um produto do carrinho:

```shoud be able to remove a product```
    
#### Testes hooks/useCart.tsx

- Deve ser possivel preencher o contexto de cart com um valor armazenado no LocalStorage:
```should be able to initialize cart with localStorage value```
    
- Deve ser possivel adicionar um novo produto ao carrinho:
```should be able to add a new product```    
    
- Não deve ser possivel adicionar um produto que não exista ao carrinho:
```should not be able add a product that does not exist```  

- Deve ser possivel aumentar a quantidade de um produto no carrinho adicionando um produto já existente no carrinho:
```should be able to increase a product amount when adding a product that already exists on cart```
    
- Não deve ser possivel aumentar a quantidade de um produto no carrinho caso não tenha disponibilidade de estoque:
```should not be able to increase a product amount when running out of stock```
    
- Deve ser possivel remover um produto do carrinho:
```should be able to remove a product```

- Não deve ser possivel remover um produto que não esteja no carrinho ou não exista:
```should not be able to remove a product that does not exist```
    
- Deve ser possivel atualizar a quantidade de um produto no carrinho:
```should be able to update a product amount```
 
- Não deve ser possivel atualizar um produto que não está no carrinho ou não existe:
```should not be able to update a product that does not exist```
    
- Não deve ser possivel atualizar a quantidade um produto quando não tiver essa quantidade em estoque:
```should not be able to update a product amount when running out of stock```
    
- Não deve ser possivel atualizar a quantidade de um produto para um valor menor que 1:
```should not be able to update a product amount to a value smaller than 1```








