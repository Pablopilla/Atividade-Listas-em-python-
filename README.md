```markdown
# 📦 Sistema Simples de Gerenciamento de Estoque em Python

Este é um projeto simples e prático desenvolvido em Python que simula um controle básico de estoque. O fluxo foi pensado utilizando o conceito de fila, onde novos itens são adicionados ao final da lista e o item mais antigo (primeiro da lista) é removido quando uma operação de saída é executada.

## 🚀 Funcionalidades

- **Visualização Inicial:** Exibe o catálogo de produtos disponíveis e seus respectivos preços.
- **Entrada de Dados Dinâmica:** Permite que o usuário cadastre um novo produto com nome e valor personalizado.
- **Fluxo FIFO (First In, First Out):** Demonstra a remoção automática do item mais antigo do estoque assim que o novo produto é adicionado.
- **Exibição Formatada:** Apresenta a lista final com formatação monetária padrão em Reais (`R$`).

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Conceitos de Estrutura de Dados:** Listas (`arrays`), manipulação de listas (`append` e `pop`) e iteração pareada com a função integrada `zip()`.

## 📝 Como Executar o Projeto

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-seu-repositorio.git
   ```
3. Navegue até a pasta do arquivo e execute:
   ```bash
   python nome_do_arquivo.py
   ```

## 💻 Exemplo Prático de Execução

Ao rodar o script, a interação no terminal ocorre desta forma:

```text
Camiseta Básica 49.9
Calça Jeans 129.9
Jaqueta Corta-Vento 219.9

Adicionar produto
Digite o nome do produto: Meia
Digite o valor do produto: 30.00

Calça Jeans - R$ 129.90
Jaqueta Corta-Vento - R$ 219.90
Meia - R$ 30.00
```
*(Note que o primeiro item "Camiseta Básica" foi removido automaticamente para dar entrada ao produto "Meia").*

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma *Issue* ou enviar um *Pull Request* para propor melhorias como:
- Implementação de um menu interativo de opções.
- Persistência de dados em arquivos JSON ou TXT.
- Interface gráfica ou CLI mais robusta.

---
Desenvolvido por [Seu Nome](https://github.com/seu-usuario) 😊
```
