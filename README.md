# Oracle Database Connection with Python

Este repositório contém um exemplo de como conectar-se a um banco de dados Oracle usando a biblioteca `cx_Oracle` em Python.

## Requisitos

- Python 3.x
- Oracle Client ou Oracle Instant Client
- Biblioteca `cx_Oracle`

## Instalação

1. **Instalar o Python:**
   
   Certifique-se de que o Python 3.x está instalado. Para verificar, execute:

   ```bash
   python --version
2. **Instalar Oracle Instant Client:**

O Oracle Client ou Oracle Instant Client é necessário para se conectar ao banco de dados Oracle. Você pode fazer o download do Oracle Instant Client.

Após o download, extraia os arquivos e defina as variáveis de ambiente necessárias, como LD_LIBRARY_PATH (para Linux) ou configure o caminho no Windows.

3. **Instalar a biblioteca cx_Oracle**:
pip install cx_Oracle

#Como usar: 
Conexão ao Banco de Dados Oracle

No arquivo oracle_connection.py, você encontrará uma função que estabelece uma conexão com o banco de dados Oracle.
Configuração da Conexão

    Host: Endereço IP ou nome do host do servidor Oracle 
    Porta: Porta do listener Oracle 
    Service Name: Nome do serviço 
    Usuário: Nome de usuário para autenticação no banco de dados 
    Senha: Defina sua senha na variável password


  
---

### Observações:
- **Variáveis de Ambiente**: Para sistemas como o Linux, você pode precisar configurar as variáveis de ambiente do Oracle Instant Client (como `LD_LIBRARY_PATH`) corretamente para que o `cx_Oracle` funcione.
- **Senha**: No código, a senha do usuário foi deixada em branco por questões de segurança. Certifique-se de inserir a senha correta para o usuário no seu ambiente de desenvolvimento ou produção.

Este README fornece todas as informações necessárias para executar e testar o código de conexão com Oracle.
