```markdown
# 📱 Phone Info Checker

Este script simples em Python permite extrair informações úteis de um número de telefone, como o **fuso horário**, a **operadora**, e a **localização aproximada**. Ideal para testes rápidos e para quem quer aprender mais sobre manipulação de dados com a biblioteca `phonenumbers`.

> Feito com carinho por **Yam Santos** para facilitar a vida dos usuários. 😊

## 🚀 Como usar

1. Certifique-se de ter o Python instalado (versão 3.x).
2. Instale a biblioteca necessária:
   ```bash
   pip install phonenumbers
   ```
3. Execute o script:
   ```bash
   python seu_script.py
   ```
4. Digite um número de telefone no formato internacional (ex: `+5511999998888`).
5. Veja na tela as informações extraídas:

- 📞 Número formatado
- 🌍 Fuso horário(s)
- 📡 Operadora
- 🗺️ Região geográfica

## 🧠 O que o código faz

- Recebe um número de telefone via `input`
- Usa a biblioteca `phonenumbers` para:
  - Verificar a validade e formatar
  - Identificar o fuso horário
  - Determinar a operadora
  - Detectar a região associada ao número
- Exibe todas essas informações no terminal

## 📚 Tecnologias utilizadas

- Python
- Biblioteca [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers)

---

