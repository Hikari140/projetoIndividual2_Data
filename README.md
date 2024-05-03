# Projeto Indivual Módulo 2

Foi realizado um Diagrama para demonstrar um modelo de Banco de Dados com um tema proposto e com perguntas referente ao modelo.

## Descrição do Projeto

Você foi contratado para desenvolver um banco de dados que irá armazenar dados importantes que será utilizado pelo sistema RESILIADATA.

- O sistema irá auxiliar na avaliação de quais são as tecnologias que as empresas parceiras
estão utilizando e quem são seus colaboradores;
- Vamos ter o cadastro de empresas parceiras, cadastro de tecnologias com a opção de
selecionar a área (webdev, dados, marketing, etc.), uma tabela para registrar quais
tecnologias as empresas estão utilizando e uma tabela para cadastro de colaboradores.

Realizar essa modelagem e responder algumas perguntas com nosso modelo:

1. Quais são as entidades necessárias?;
2. Quais são os principais campos e seus respectivos tipos?;
3. Como essas entidades estão relacionadas?;
4. Simule 2 registros para cada entidade.

## Descrição do Modelo

### Entidades:

- Empresas Parceiras
- Colaboradores
- Tecnologias
- Tecnologias para Empresas

### Relacionamentos (Cardinalidades):

- Empresas Parceiras (1:N) Colaboradores
- Tecnologias (1:N) Tecnologias Para Empresas
- Empresas Parceiras (1:N) Tecnologias Para Empresas
- Tecnologias Para Empresas (N:1) Empresas Parceiras
