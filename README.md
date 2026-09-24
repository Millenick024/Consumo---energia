# ⚡ Calculadora de Consumo de Energia

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Projeto-181717?style=for-the-badge&logo=github&logoColor=white)
![Energia](https://img.shields.io/badge/Consumo-Energia-F7C948?style=for-the-badge)

## 📌 Sobre o projeto

Este projeto é uma calculadora de consumo de energia elétrica desenvolvida em Python.

O programa permite informar o nome de um aparelho, sua potência em watts e o tempo médio de uso diário para calcular uma estimativa do consumo mensal em kWh.

Também é apresentado um custo mensal estimado, considerando o valor fixo de **R$ 0,75 por kWh**.

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a fórmula:

```text
consumoMensal = (potencia * horasDia * 30) / 1000