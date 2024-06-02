Agendamento de consultas e triagem médica

## Descrição

Este é um projeto de um agendamento de consultas, utilizando estrutura árvore binária de busca para auxiliar pacientes a realizar cadastro.

## Estrutura de Dados

O sistema utiliza árvore binária de busca para armazenas pacientes. 
A class Paciente recebe os dados para cadastro, a class Consulta e class Agendamento serve para inserir os pacientes.

```bash
class Paciente:
    def __init__(self, nome, idade, especialidade, horario, dia, estado_pulseira):
        self.nome = nome  
        self.idade = idade  
        self.especialidade = especialidade  
        self.horario = horario  
        self.dia = dia  
        self.estado_pulseira = estado_pulseira  

class Consulta:
    def __init__(self, paciente):
        self.paciente = paciente  
        self.esquerda = None  
        self.direita = None  

class Agendamento:
    def __init__(self):
        self.raiz = None  
        self.agendamentos = {}  
        self.paciente_anterior = None 
        self.lista_espera = []  
        self.arvore_emergencia = None 
```

## Requisitos

Verifique se o sistema está instalado o Python 3 ou superior.


## Como utilizar o sistema

Execute o código Python.

Utilize o teclado para selecionar as opções apresentadas.

O programa se encerra ao selecionar a opção "5 - Fechar clínica ".

## Autores

Vitor Amorim - 190118261@aluno.unb.br

## Referências
[Playlist 1]https://www.youtube.com/playlist?list=PL5TJqBvpXQv7ipm2exZbbqwpFZc-TZ80s

[Link](https://www.guru99.com/pt/binary-search-tree-data-structure.html)


