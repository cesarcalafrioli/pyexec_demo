# pyexec_demo
Demonstração de um aplicativo executável desenvolvido na linguagem Python ( Somente Windows ).

Após desenvolver o script, digite o comando abaixo:

pyinstaller --onefile nome_do_script.py

O --onefile serve para que o executável seja criado sem haver dependência do diretório completo. Dessa forma,
executamos o aplicativo em qualquer lugar.

Veja o arquivo executável na pasta dist.

Ferramentas utilizadas:
- Python
- pyinstaller

Referências
https://www.blog.pythonlibrary.org/2021/05/27/pyinstaller-how-to-turn-your-python-code-into-an-exe-on-windows/
