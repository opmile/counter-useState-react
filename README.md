# Contador Consciente — React + Tailwind

Este projeto é um exercício introdutório em **React** com foco em **componentização consciente**, **estado** e **fluxo de dados unidirecional**.

A aplicação consiste em um contador simples, com ações de incrementar, decrementar e resetar o valor exibido na tela.

---

## Objetivos do exercício

* Compreender o uso do hook `useState`
* Praticar separação de responsabilidades entre componentes
* Trabalhar com `props` e `children`
* Criar componentes reutilizáveis
* Aplicar estilização com Tailwind CSS

---

## Conceitos aplicados

* **Estado centralizado** no componente `App`
* **Atualização funcional de estado** (`setState(prev => ...)`)
* **Componentização** orientada à responsabilidade única
* **Composição com `children`**
* **Reutilização de UI** com um componente `Button`
* **Fluxo de dados top-down** (pai → filhos)

---

## Estrutura dos componentes

* **App**

  * Responsável pelo estado (`count`) e pela lógica de negócio
* **Container**

  * Componente de layout responsável por centralizar o conteúdo
* **Counter**

  * Responsável apenas por exibir o valor do contador
* **Control**

  * Agrupa os botões de ação e recebe handlers via props
* **Button**

  * Componente reutilizável de botão estilizado com Tailwind

---

## Funcionalidades

* Incrementar o contador em +1
* Decrementar o contador em -1
* Resetar o contador para 0

---

## Tecnologias utilizadas

* React
* JavaScript (ES6+)
* Tailwind CSS

---
