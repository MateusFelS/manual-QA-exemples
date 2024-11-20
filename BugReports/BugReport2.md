# Cupom de desconto pode ser aplicado infinitamente para o mesmo usuário

## Descrição
- Um mesmo cupom de desconto pode ser aplicado várias vezes consecutivas para o mesmo usuário, mesmo após já ter sido utilizado. Isso permite que o usuário acumule descontos de forma ilimitada, resultando em uma potencial perda de receita e comprometendo a credibilidade da promoção.

Passos para Reproduzir:
- Acesse a aplicação "Coffee Cart".
- Adicione 3 cafés ao carrinho.
- Aceita o cupom de desconto.
- Repita o mesmo processo repetidamente.

## Resultado Esperado:
- Após o cupom ser utilizado uma vez, ele deve ser invalidado para o mesmo usuário e não pode ser reaplicado em novos pedidos.

## Resultado Atual:
- O cupom pode ser aplicado infinitamente para o mesmo usuário, sem restrição, acumulando descontos de forma indevida.

## Impacto:
- **Financeiro**: Perda de receita devido ao uso ilimitado do desconto.
- **Credibilidade**: Comprometimento da confiança dos usuários em futuras promoções, caso o problema seja percebido.

## Ambiente de Teste:
- **Navegadores**: Chrome e Brave
- **Sistema Operacional**: Windows 10

## Severidade: 
- Alta

## Prioridade: 
- Crítica

## Evidência
![image](https://github.com/user-attachments/assets/7500067e-a9de-44b0-871b-96bdd35f7645)
