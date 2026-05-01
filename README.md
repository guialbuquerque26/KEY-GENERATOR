# KEY-GENERATOR

Um gerador de senhas fortes em Python, projetado para criar senhas seguras a partir de uma palavra ou frase base fornecida pelo usuário.

## 🚀 Como funciona

O script `Senhas.py` recebe uma palavra ou frase de entrada e aplica diversas transformações para criar uma senha complexa e segura:

1. **Substituição de Espaços:** Troca todos os espaços da frase original por caracteres especiais aleatórios (`!@#$%&*_-+=`).
2. **Adição de Números:** Insere números aleatórios na senha.
3. **Adição de Caracteres Especiais:** Adiciona caracteres especiais extras.
4. **Variação de Caixa:** Alterna aleatoriamente entre letras maiúsculas e minúsculas.
5. **Embaralhamento:** Por fim, embaralha todos os caracteres para garantir máxima aleatoriedade e segurança.

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Bibliotecas nativas: `random` e `string`

## ⚙️ Como executar

1. Certifique-se de ter o Python instalado em seu sistema.
2. Clone ou baixe este repositório.
3. Abra o terminal e navegue até a pasta do projeto.
4. Execute o script:
   ```bash
   python Senhas.py
   ```
5. Digite uma palavra ou frase base quando solicitado e receba sua senha forte gerada na tela.

## 📝 Exemplo de Uso

```text
Digite uma palavra ou frase para base da senha: meu cachorro fofo
Sua senha forte é: f!Oo#C4rce_mhuA7%O&f
```