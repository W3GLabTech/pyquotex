# 🚀 PyQuotex

---
<p align="center">
  <a href="#">
    <img src="pyquotex.png" alt="pyquotex" width="350" height="auto" title="PyQuotex"/>
  </a>
</p>
<p align="center">
  <i>Unofficial Quotex Library API Client written in Python!</i>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/python-3.12%20%7C%203.13-green" alt="Python Versions"/>
</p>

---

## 📘 Sobre o projeto (PT-BR)

O **PyQuotex** nasceu como uma biblioteca open-source para facilitar a comunicação com a plataforma Quotex via WebSockets. Com o tempo e devido ao uso indevido, uma versão privada mais segura e robusta foi criada.

---

## 📘 About the Project (EN)

**PyQuotex** started as an open-source library to make it easier to communicate with the Quotex platform using WebSockets. Due to misuse, a more robust private version was later introduced.

---

## 📘 Sobre el Proyecto (ES)

**PyQuotex** nació como una biblioteca de código abierto para facilitar la comunicación con la plataforma Quotex a
través de WebSockets. Con el tiempo y debido al uso indebido, se creó una versión privada más segura y robusta.

---

## 🎯 Objetivo da Biblioteca / Library Goal / Objetivo

Prover ferramentas para desenvolvedores integrarem seus sistemas com a plataforma Quotex, permitindo operações automatizadas de forma segura e eficiente.

> ⚠️ Esta biblioteca **não é um robô de operações** e não toma decisões por conta própria.

---

# 📚 Documentação Completa


## 🏗 Arquitectura interna

- `pyquotex.stable_api.Quotex` — facade público (la API que usás).
- `pyquotex._api/*` — mixins por dominio (account, trading, history, realtime, assets).
- `pyquotex.cli/*` — entrada de comandos del CLI.
- `pyquotex.api.QuotexAPI` — cliente WebSocket subyacente.

La interfaz pública no cambia entre 1.0.x y 1.1.0.


