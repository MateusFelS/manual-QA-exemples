# Documento de Casos de Teste

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-001**        | Acessar a página inicial do Coffee Cart.    | 1. Entrar na página inicial.                                               | A mensagem promocional deve ser exibida após adicionar 3 itens. |  
|                    |                                            | 2. Adicionar 3 Café Expresso.                                              |                                                  |  
|                    |                                            | 3. Verificar se a mensagem promocional é exibida.                          |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-002**        | Acessar a página inicial do Coffee Cart.    | 1. Entrar na página inicial.                                               | A mensagem promocional não deve ser exibida ao adicionar menos de 3 itens. |  
|                    |                                            | 2. Adicionar apenas 2 Café Expresso.                                       |                                                  |  
|                    |                                            | 3. Verificar se a mensagem promocional não está disponível.                |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-003**        | Promoção configurada para 3 itens no carrinho. | 1. Entrar na página inicial.                                               | O item promocional deve continuar disponível mesmo com produtos diferentes. |  
|                    |                                            | 2. Adicionar 3 Café Expresso.                                              |                                                  |  
|                    |                                            | 3. Aceitar a promoção.                                                     |                                                  |  
|                    |                                            | 4. Navegar para a tela do carrinho.                                        |                                                  |  
|                    |                                            | 5. Remover todos os Café Expresso.                                         |                                                  |  
|                    |                                            | 6. Verificar se o item promocional permanece ativo.                        |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-004**        | Promoção configurada para limitar uma aplicação por usuário. | 1. Entrar na página inicial.                                               | A promoção deve ser acionada apenas uma vez por usuário. |  
|                    |                                            | 2. Adicionar 3 Café Expresso.                                              |                                                  |  
|                    |                                            | 3. Aceitar a promoção.                                                     |                                                  |  
|                    |                                            | 4. Adicionar 2 novos Café Expresso.                                        |                                                  |  
|                    |                                            | 5. Verificar se a promoção foi acionada novamente.                         |                                                  |  

---
