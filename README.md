Sistema Delivery de Pizzas em Python

## Descrição

Este é um projeto de um pequeno sistema de Delivery de Pizzas, utilizando estrutura de dados e listas encadeadas simples para armazenar o 
cadastro de clientes.

## Estrutura de Dados

O sistema utiliza listas encadeadas simples para guardar os clientes cadastrados. 
A classe Cliente recebe o cadastro, a classe ListaClientes será utilizada para adicionar, pesquisar e exibir os clientes.
A classe PedidoPizza recebe o pedido.

```bash
class Cliente:
  def __init__(self, nome, telefone, endereco):
    self.nome = nome
    self.telefone = telefone
    self.endereco = endereco
    self.proximo = None

class ListaClientes:
  def __init__(self):
    self.inicio = None

class PedidoPizza:
    def __init__(self, cliente, sabor, preco):
      self.cliente = cliente
      self.sabor = sabor
      self.preco = preco
```

## Requisitos

Verifique se o sitema está instalado o Python 3 ou superior


## Como utilizar o sistema

Execute o código Python.

Utilize o teclado para cadastrar os clientes e selecionar as opções apresentadas

O programa se encerra ao selecionar a opção "5 - Fechar Delivery"

## Autores

Vitor Amorim - 190118261@aluno.unb.br

## Referências
[Playlist 1](https://www.youtube.com/playlist?list=PL5TJqBvpXQv5Bb71AE5Cd_kB5rNsfU4Cp)

[Stack Overflow](https://pt.stackoverflow.com/questions/480020/cadastro-infinito-de-cliente)

[Link](https://awari.com.br/lista-encadeada-em-python-aprenda-a-estrutura-de-dados-essencial-para-programacao/?utm_source=blog&utm_campaign=projeto+blog&utm_medium=Lista%20Encadeada%20em%20Python:%20Aprenda%20a%20Estrutura%20de%20Dados%20Essencial%20para%20Programa%C3%A7%C3%A3o)

[Link](https://pt.stackoverflow.com/questions/533924/como-preencher-uma-linkedlist-listas-encadeadas-no-python-atrav%C3%A9s-das-entradas)


