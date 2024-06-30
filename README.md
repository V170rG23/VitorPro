Planejamento de Viagens em um Cruzeiro

## Descrição

Este é um projeto de planejamento de viagens em um cruzeiro, utilizando a estrutura de grafo que busca auxiliar na melhor rota entre dois lugares.

## Estrutura de Dados

O sistema utiliza grafo para demonstrar as rotas. 
A class Grafo armazena dados de estados, rotas e posições que são utilizadas ao longo do código. 
```bash
class Grafo:
    def __init__(self):
        self.estados = ["Fernando de Noronha", "Pernambuco","Fortaleza", "Bahia", "Rio de Janeiro", "São Paulo","Coritiba", "Santa Catarina"]
        self.rotas = {
            "Pernambuco": {"Bahia": (5, 300, 40), "Fernando de Noronha": (2, 150, 30)},
            "Fortaleza": {"Bahia": (5,275,45), "Fernando de Noronha":(4,170,40)},
            "Bahia": {"Pernambuco": (5, 300, 40), "Rio de Janeiro": (6, 350, 70), "Fortaleza":(5, 275, 45)},
            "Rio de Janeiro": {"Bahia": (6, 350, 70), "São Paulo": (3, 200, 50)},
            "São Paulo": {"Rio de Janeiro": (3, 200, 50), "Santa Catarina": (8, 400, 80), "Coritiba": (4, 250, 40)},
            "Santa Catarina": {"São Paulo": (8, 400, 80)},
            "Fernando de Noronha": {"Pernambuco": (2, 150, 30),"Fortaleza":(4, 170, 40)},
            "Coritiba": {"São Paulo": (4, 250, 40)},

        }
        self.posicoes = {
            "Fernando de Noronha": (890, 30),
            "Pernambuco": (910, 150),
            "Fortaleza": (1045,180),
            "Bahia": (970, 250),
            "Rio de Janeiro": (930, 350),
            "São Paulo": (900, 450),
            "Coritiba": (1050, 570),
            "Santa Catarina": (800, 630),
        }


```

## Requisitos

Verifique se o sistema está instalado o Python 3 ou superior.
Instalar pelo terminal: pip install pygame.

## Como utilizar o sistema

Execute o código Python.

Utilize o mouse para selecionar as opções apresentadas na interface.

O programa se encerra ao clicar no [X] da janela.

## Autores

Vitor Amorim - 190118261@aluno.unb.br

## Referências

[Link]https://www.youtube.com/watch?v=3vBx8GqlVT4  
[Link]https://www.youtube.com/watch?v=hsJBilAiZDY
[Link]https://www.freecodecamp.org/portuguese/news/algoritmo-de-caminho-de-custo-minimo-de-dijkstra-uma-introducao-detalhada-e-visual/
[Playlist]https://www.youtube.com/playlist?list=PLJ8PYFcmwFOxtJS4EZTGEPxMEo4YdbxdQ



