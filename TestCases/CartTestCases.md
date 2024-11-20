# Documento de Casos de Teste

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-001**        | Acessar a página inicial do Coffee Cart.    | 1. Entrar na página inicial.                                               | O carrinho deve exibir o produto adicionado.     |  
|                                                                  2. Adicionar um Café Expresso.                                                                                                |  
|                                                                  3. Navegar para a tela do carrinho.                                                                                           |  
|                                                                  4. Verificar se existe algum produto no carrinho.                                                                             |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-002**        | Nenhum item deve estar no carrinho.         | 1. Entrar na página inicial.                                               | A mensagem "No coffee, go add some." deve ser exibida. |  
|                    |                                            | 2. Navegar para a tela do carrinho.                                        |                                                  |  
|                    |                                            | 3. Verificar se a mensagem *"No coffee, go add some."* é exibida.          |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-003**        | A promoção deve estar configurada para 3 cafés. | 1. Entrar na página inicial.                                               | O item promocional deve aparecer com o desconto no carrinho. |  
|                    |                                            | 2. Adicionar 3 Café Expresso ao carrinho.                                  |                                                  |  
|                    |                                            | 3. Aceitar o item promocional.                                             |                                                  |  
|                    |                                            | 4. Navegar para a tela do carrinho.                                        |                                                  |  
|                    |                                            | 5. Verificar se o item promocional está com o desconto aplicado.           |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-004**        | O carrinho deve conter pelo menos um item.  | 1. Entrar na página inicial.                                               | O carrinho deve exibir a mensagem "No coffee, go add some." após a remoção. |  
|                    |                                            | 2. Adicionar um Café Expresso ao carrinho.                                 |                                                  |  
|                    |                                            | 3. Navegar para a tela do carrinho.                                        |                                                  |  
|                    |                                            | 4. Remover o item do carrinho.                                             |                                                  |  
|                    |                                            | 5. Verificar se o carrinho está vazio.                                     |                                                  |  

---

| **ID**            | **Pré-condições**                           | **Passos**                                                                 | **Resultado Esperado**                            |  
|--------------------|--------------------------------------------|----------------------------------------------------------------------------|--------------------------------------------------|  
| **CT-005**        | O carrinho deve conter pelo menos um item.  | 1. Entrar na página inicial.                                               | O preço total do carrinho deve ser atualizado para $20.00 ao aumentar a quantidade do item. |  
|                    |                                            | 2. Adicionar um Café Expresso ao carrinho.                                 |                                                  |  
|                    |                                            | 3. Navegar para a tela do carrinho.                                        |                                                  |  
|                    |                                            | 4. Aumentar a quantidade do item no carrinho.                              |                                                  |  
|                    |                                            | 5. Verificar se o preço total é atualizado corretamente.                   |                                                  |  

---
