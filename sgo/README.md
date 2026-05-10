# SGO - Sistema de Gestão das Olimpíadas

## Descrição

Sistema desenvolvido para coordenar os diferentes aspectos das Olimpíadas,
permitindo o gerenciamento de competições, inscrições de atletas, alocação
de locais para as provas e controle de resultados.

**Disciplina:** Projeto de Software — PUC Minas  
**Professor:** João Paulo Carneiro Aramuni  
**Período:** 4º — Engenharia de Software

---

## Histórias de Usuário

**US01** — Como **administrador**, quero **cadastrar uma competição** informando
modalidade, data, horário e local, para que os atletas possam se inscrever.

**US02** — Como **administrador**, quero **alocar um local para uma competição**,
verificando automaticamente se não há conflito de horário, para evitar
sobreposição de eventos.

**US03** — Como **atleta**, quero **me inscrever em uma competição**,
informando o país que represento naquela modalidade, para participar das Olimpíadas.

**US04** — Como **atleta**, quero **cancelar minha inscrição em uma competição**
até a data limite, para liberar minha vaga caso não possa participar.

**US05** — Como **atleta**, quero **consultar as competições disponíveis**
com data, horário e local, para planejar minha participação.

**US06** — Como **árbitro**, quero **registrar o resultado de uma competição**
informando o 1º, 2º e 3º lugares, para que as medalhas sejam atribuídas corretamente.

**US07** — Como **árbitro**, quero **consultar as competições do dia** com
os atletas inscritos, para me preparar para cada prova.

**US08** — Como **administrador**, quero **gerar o relatório de medalhas por país**,
mostrando ouro, prata e bronze, para acompanhar o desempenho de cada delegação.

**US09** — Como **visitante**, quero **consultar o quadro de medalhas atualizado**
em tempo real, para acompanhar o desempenho dos países.

**US10** — Como **administrador**, quero **gerenciar o cadastro de atletas**,
incluindo seus dados e país de origem, para manter o sistema atualizado.

---

## Diagramas UML

### Diagrama de Caso de Uso

<img width="800px" src="https://github.com/GiulianoLBP/sistema-gestao-olimpiadas/blob/main/sgo/imagens/diagrama-de-caso-de-uso.png"/>

---

### Diagrama de Classes

<img width="800px" src="https://github.com/GiulianoLBP/sistema-gestao-olimpiadas/blob/main/sgo/imagens/diagrama-de-classes.png"/>

---

### Diagrama de Pacotes

<img width="800px" src="https://github.com/GiulianoLBP/sistema-gestao-olimpiadas/blob/main/sgo/imagens/diagrama-de-pacotes.png"/>

---

### Diagrama de Componentes

<img width="800px" src="https://github.com/GiulianoLBP/sistema-gestao-olimpiadas/blob/main/sgo/imagens/diagrama-de-componentes.png"/>

---

### Diagrama de Implantação

<img width="800px" src="https://github.com/GiulianoLBP/sistema-gestao-olimpiadas/blob/main/sgo/imagens/diagrama-de-implantacao.png"/>

---

## Como renderizar os diagramas

1. Instale a extensão **PlantUML** no VS Code
2. Abra qualquer arquivo `.puml` da pasta `codigos/`
3. Pressione `Alt+D` para visualizar o diagrama
4. Clique com botão direito → **Export Current Diagram** para salvar como PNG

Ou acesse [plantuml.com/plantuml](https://www.plantuml.com/plantuml/uml/) e cole o código diretamente.
