# Cupom de desconto pode ser aplicado infinitamente para o mesmo usuário

## Descrição
- Um mesmo item promocional pode ser aplicado várias vezes consecutivas para o mesmo usuário, mesmo após já ter sido adicionado.

Passos para Reproduzir:
- Acesse a aplicação "Coffee Cart".
- Adicione 3 cafés ao carrinho.
- Aceita o cupom de desconto.
- Repita o mesmo processo repetidamente.

## Resultado Esperado:
- Após o café promocional ser adicionado uma vez, ele deve ser invalidado para o mesmo usuário e não pode ser reaplicado em novos pedidos.

## Resultado Atual:
- O café promocional pode ser adicionado infinitamente para o mesmo usuário, sem restrição, acumulando descontos de forma indevida.

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
