# Classificador de Nível de Herói

Este projeto é um sistema simples em Java para classificar o nível de um herói com base na quantidade de experiência (XP) acumulada. Dependendo da quantidade de XP, o herói é classificado em diferentes níveis.

## Funcionalidades

- Solicita o nome do herói.
- Solicita a quantidade de experiência (XP) do herói.
- Classifica o herói em um dos seguintes níveis com base no XP:
  - Ferro: XP < 1000
  - Bronze: 1001 ≤ XP ≤ 2000
  - Prata: 2001 ≤ XP ≤ 5000
  - Ouro: 5001 ≤ XP ≤ 7000
  - Platina: 7001 ≤ XP ≤ 8000
  - Ascendente: 8001 ≤ XP ≤ 9000
  - Imortal: 9001 ≤ XP ≤ 10000
  - Radiante: XP ≥ 10001
- Exibe a mensagem final com o nome do herói e seu nível.

## Como Executar

### Pré-requisitos

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) instalado.

### Passos para Compilar e Executar

1. **Clone o repositório**:

   git clone https://github.com/IOVASCON/Nivel_Heroi.git

2. Navegue até o diretório do projeto:

    cd Nivel_Heroi/NivelHeroi/src

3. Compile o arquivo Java:

    javac ClassificadorHeroi.java

4. Execute o programa:

    java ClassificadorHeroi

## Exemplo de Uso

Digite o nome do herói: Nhengo
Digite a quantidade de experiência (XP) do herói: 1000
O Herói de nome Nhengo está no nível de Radiante

## Estrutura do Projeto

NivelHeroi/
├── README.md
├── src/
│   └── ClassificadorHeroi.java
└── bin/

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

    Faça um fork do projeto.
    Crie uma nova branch (git checkout -b feature/nova-feature).
    Faça as alterações necessárias e adicione os commits (git commit -m 'Adiciona nova feature').
    Envie as mudanças para o seu repositório forkado (git push origin feature/nova-feature).
    Crie um novo Pull Request.

## Licença

Este projeto está licenciado sob a Licença .......