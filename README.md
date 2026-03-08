# 🚗 Sistema de Cálculo de Multa de Trânsito

Projeto desenvolvido como atividade acadêmica da **Unifor**.

## 📌 Descrição

Este sistema verifica se um motorista recebeu **multa por excesso de velocidade** e determina qual penalidade deve ser aplicada de acordo com o valor excedido.

O programa solicita algumas informações do usuário, calcula o excesso de velocidade e exibe o tipo de multa correspondente.

---

## 📥 Dados de Entrada

O sistema solicita as seguintes informações:

* **Nome do motorista**
* **Velocidade máxima permitida na via (km/h)**
* **Velocidade registrada do veículo (km/h)**

---

## ⚙️ Regras de Cálculo

1. Calcular o **excesso de velocidade**:

```
excesso = velocidade_registrada - velocidade_maxima
```

2. Aplicar as regras abaixo:

| Excesso de velocidade | Tipo de multa | Valor |
| --------------------- | ------------- | ----- |
| Até o limite da via   | Sem multa     | R$0   |
| Até 10 km/h acima     | Multa leve    | R$50  |
| De 11 a 20 km/h acima | Multa média   | R$100 |
| Acima de 20 km/h      | Multa grave   | R$200 |

---

## 📊 Saída do Programa

Se houver multa, o sistema deverá mostrar:

* Nome do motorista
* Velocidade máxima da via
* Velocidade registrada
* Tipo de multa
* Valor da penalidade

Caso contrário, deverá exibir:

```
Motorista dentro do limite de velocidade.
```

---


---

## 🏫 Instituição

**Universidade de Fortaleza (Unifor)**

---
