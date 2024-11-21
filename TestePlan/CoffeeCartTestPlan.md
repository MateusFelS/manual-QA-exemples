# Plano de Teste para o Sistema de Carrinho do Coffee Cart

## Objetivo do Teste
- O objetivo deste plano de teste é validar o funcionamento do sistema de carrinho do Coffee Cart. Serão testados cenários em que o usuário adiciona, remove e modifica a quantidade de itens no carrinho, além de verificar a aplicação de promoções e a exibição de mensagens de status no carrinho.

## Versão do Plano de Testes
- Versão: 1.0
- Data de Criação: 20/11/2024
- Última Atualização: 20/11/2024
- Autor: Mateus Santos

## Escopo do Teste
- Testes de funcionalidade
- Testes de interface (UI/UX)
- Testes de compatibilidade (diferentes navegadores e dispositivos)

## Funcionalidades Testadas
- Adição e remoção de Produto ao Carrinho
- Exibição de Carrinho Vazio
- Aplicação de Desconto em Promoção
- Remoção de Item do Carrinho
- Atualização do Preço Total ao Alterar Quantidade de Itens

## Ambiente de Teste
- Navegador: Chrome e Brave.
- Sistema Operacional: Windows 10.
- Acesso ao Sistema: O sistema estará acessível através da URL fornecida.
- Ferramenta de Teste: Testes automatizados em Cypress.

## Critérios de Aceitação
- Todos os resultados esperados devem ser atendidos conforme descrito nos casos de teste.
- O carrinho deve permitir a adição, remoção e modificação de itens sem falhas.
- O sistema de promoções deve aplicar corretamente o desconto quando 3 Café Expresso são adicionados ao carrinho.
- As mensagens de erros devem ser claras e concisas.
- O preço total do carrinho deve ser atualizado corretamente conforme as mudanças na quantidade dos itens.
