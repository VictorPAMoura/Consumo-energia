# ⚡ Calculadora de Consumo de Energia

Projeto desenvolvido em Python para calcular o consumo mensal estimado de energia elétrica de um aparelho.

## 🎯 Objetivo

O objetivo deste projeto é permitir que o usuário informe o nome do aparelho, sua potência em watts e o tempo médio de uso diário para calcular o consumo mensal de energia em kWh.

## 🐍 Tecnologia utilizada

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)

- Python 3

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

**Consumo mensal = (potência × horas por dia × 30) / 1000**

Onde:

- **Potência:** potência do aparelho em watts (W).
- **Horas por dia:** quantidade de horas que o aparelho é utilizado diariamente.
- **30:** quantidade aproximada de dias em um mês.
- **1000:** utilizado para converter Wh em kWh.

## ▶️ Como executar o programa

1. Tenha o Python 3 instalado no computador.
2. Baixe ou clone este repositório.
3. Abra a pasta do projeto no VS Code.
4. Abra o terminal.
5. Execute o seguinte comando:

```bash
python app.py
```

6. Informe o nome do aparelho, a potência em watts e o tempo médio de uso diário.
7. O programa exibirá o consumo mensal estimado em kWh.

## ⚡ Exemplo de uso

Exemplo utilizando uma geladeira de 100 W durante 15 horas por dia:

```text
Digite o nome do aparelho: Geladeira
Digite a potência do aparelho em watts (W): 100
Digite quantas horas por dia o aparelho é usado: 15

--- Consumo de Energia ---
Aparelho: Geladeira
Consumo estimado: 45.00 kWh/mês
```