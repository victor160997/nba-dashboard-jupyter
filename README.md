# LINK DO DATASET UTILIZADO:
https://www.kaggle.com/datasets/wyattowalsh/basketball

-> Após clonar o projeto deve-se adicionar a pasta csv do dataset na raiz do projeto.


- instalar o venv
- ✅ O que é o venv?

venv é o módulo nativo do Python para criar ambientes virtuais, onde cada projeto pode ter suas próprias dependências, sem interferir no sistema.

Não precisa instalar nada extra — o venv já vem no Python 3.3+.

📌 1. Verificar se o Python está instalado
Windows

Abra o PowerShell e rode:
```
python --version
```

ou
```
py --version
```
Linux / Mac:

```
python3 --version
```

Se aparecer a versão (ex.: Python 3.11.6), está tudo certo.

📌 2. Criar o ambiente virtual (venv)

Escolha a pasta do seu projeto e execute:

Windows:
```
python -m venv .venv
```

ou
```
py -m venv .venv
```
Linux / macOS:
```
python3 -m venv .venv
```
Isso cria uma pasta chamada **"/.venv"** com tudo do ambiente virtual.

📌 3. Ativar o ambiente virtual

Windows (PowerShell)
``` PowerShell
.venv\Scripts\Activate.ps1
```

Se der erro de permissão, rode isso antes:
``` PowerShell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```
Windows (CMD):
```
.\.venv\Scripts\activate.bat
```
Linux / macOS:
```
source .venv/bin/activate
```

📌 4. Instalar pacotes dentro do venv

Agora tudo que você instalar vai apenas para esse ambiente:
``` 
pip install -r requirements.txt
``` 
📌 5. Desativar o ambiente virtual

Quando quiser sair:
``` 
deactivate
``` 
📌 6. Excluir o ambiente virtual

Só apagar a pasta:
``` 
rm -rf .venv
``` 
ou no Windows, só deletar a pasta normalmente.

🎉 Pronto!

Para rodar deve-se executar:
```
panel serve index.ipynb --show --autoreload 
``` 

Você agora sabe:

✓ Verificar o Python
✓ Criar um ambiente virtual
✓ Ativar e desativar
✓ Instalar dependências sem bagunçar seu sistema

Feito isso deve-se instalar as dependencia: 
``` 
pip install -r requirements.txt
``` 
para rodar o projeto: 
``` 
panel serve index.ipynb --show --autoreload
``` 
