#Automação RPA Challenge
Este projeto foi desenvolvido para resolver o desafio do site [RPA Challenge](https://rpachallenge.com/).

## o que o script faz:
1. Lê uma lista de dados (Nome, Empresa, Enderenço, etc.) de um arquivo Excel usando a biblioteca 'openpyxl'.
2. Abre o navegador Google Chrome de forma automatizada usando 'Selenium'.
3. Preenche os campos do formulário web dinamicamente (mesmo que a posição dos campos mude a cada tentativa).
4. Clica no botão de enviar (Submit) para cada linha da planilha até concluir todos os cadastros.

## Tecnologias utilizadas
- Python
- Selenium (Automação Web)
- Openpyxl (Leitura de Excel)
- PyAutoGUI (Pausas de segurança)

## Como rodas:
Certifique-se de ter as bibliotecas instaladas ('pip install selenium openpyxl pyautogui')
