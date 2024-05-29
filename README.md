# Sistema de Gerenciamento de Estacionamento

## Sobre o Projeto
Este projeto nasce como um desafio da trilha .NET da DIO com o objetivo de colocar em prática os conhecimentos adquiridos no módulo Fundamentos de C#. Trata-se de sistema de gestão de estacionamento, que será usado para gerenciar os veículos estacionados e realizar suas operações, como por exemplo adicionar um veículo, remover um veículo (e exibir o valor cobrado durante o período) e listar os veículos.

## Visão Geral
O código do desafio veio incompleto justamente para que pudéssemos colocar em prática os fundamentos de C#.  Portanto para cumprir com os requisitos e completar o projeto, foi necessário terminar de implementar os três métodos:

* AdicionarVeiculo: Método responsável por receber uma placa digitada pelo usuário e guardar na variável veiculos.
* RemoverVeiculo: Método responsável por verificar se um determinado veículo está estacionado, e caso positivo, irá pedir a quantidade de horas que ele permaneceu no estacionamento. Após isso, realiza o seguinte cálculo: precoInicial * precoPorHora, exibindo para o usuário.
* ListarVeiculos: Lista todos os veículos presentes atualmente no estacionamento. Caso não haja nenhum, exibir a mensagem "Não há veículos estacionados".

Após finalizar os métodos acima, realizei uma pequena refatoração no código: 
* Apagados os comentários desnecessários.
* Trasnferência da lógica do Menu do Program.cs e colocá-la na classe Estacionamento com o objetivo de não expor regra de negócio no arquivo principal de inicialização do programa.
  
## Tecnologias Empregadas:
  <img alt="C#" src="https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white&style=for-the-badge" />
  <img alt=".NET" src="https://img.shields.io/badge/.NET-5C2D91?logo=.net&logoColor=white&style=for-the-badge" />  

## 📋 Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas antes de começar:
- .NET 8.0
- IDE de sua preferência: Visual Studio 2022 ou VS Code. 


## ⚙️ Rodando o projeto

```bash
# Clone o repositório:
git clone https://github.com/erasmobezerra/trilha-net-fundamentos-desafio

# Navegue no terminal até pasta raiz do projeto:
cd trilha-net-fundamentos-desafio/trilha-net-fundamentos-desafio/DesafioFundamentos

# Rode o projeto:
dotnet run

```


## 📧 Meus Contatos
E-mail: erasmo.ads.tech@gmail.com
Linkedin: https://www.linkedin.com/in/erasmobezerra/


## Agradecimentos

Quero agradecer de coração a Digital Innovation One que proporciana gratuita esse aprendizado. E claro também meu muito obrigado ao professor <a href="https://www.linkedin.com/in/leonardo-buta/">`Leonardo Buta`</a> pela excelente didática! 
