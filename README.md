# 🏠 R.M Imobiliária - Sistema de Orçamento de Aluguel

Sistema simples em **Python** que calcula o orçamento de aluguel de imóveis com base em tipo, número de quartos, vagas de garagem e descontos aplicáveis.  
Também gera um arquivo **CSV** com os valores das 12 parcelas mensais do aluguel.

---

## 🚀 Funcionalidades

- Solicita informações do imóvel (tipo, quartos, vagas, etc.)
- Calcula o valor total do aluguel com possíveis descontos
- Exibe o resumo do orçamento e parcelamento do contrato
- Gera automaticamente um arquivo `orcamento_12_parcelas.csv` com as 12 parcelas mensais

---

## 🧮 Tipos de imóvel e valores base

| Tipo        | Valor Base | Observações |
|--------------|-------------|-------------|
| Apartamento  | R$ 700,00   | +R$ 200,00 se tiver 2 quartos |
| Casa         | R$ 900,00   | +R$ 250,00 se tiver 2 quartos |
| Estúdio      | R$ 1200,00  | +R$ 250,00 (2 vagas) +R$ 60,00 por vaga adicional |

💡 **Desconto:** Apartamentos sem crianças recebem **5% de desconto** no aluguel.

---

## 📦 Saída gerada

- **Arquivo:** `orcamento_12_parcelas.csv`  
- **Conteúdo:** Lista de 12 meses com o valor do aluguel mensal.

---

## 🖥️ Como executar

1. Certifique-se de ter o **Python 3** instalado.
2. Faça o clone do repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/orcamento-imobiliaria.git
