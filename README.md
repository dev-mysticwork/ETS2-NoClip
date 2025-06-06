# 🚛 Ativador de Câmera 0 (Noclip) – Euro Truck Simulator 2

Script em Python que ativa automaticamente a câmera 0 (noclip) no Euro Truck Simulator 2, editando o arquivo `config.cfg` localizado na pasta de Documentos. Não requer bibliotecas externas nem que o jogo esteja aberto.

## ✅ O que ele faz

- Localiza o diretório do ETS2 em `Documentos`.
- Modifica o arquivo `config.cfg` para ativar a câmera livre e o console.
- Funciona automaticamente ao executar o script.

## 📦 Requisitos

- Python 3.x
- Nenhuma biblioteca externa necessária

## ▶️ Como usar

1. Certifique-se de que o **ETS2 esteja fechado**.
2. Execute o script Python.
3. Abra o jogo normalmente — a câmera 0 já estará ativada.

> 📂 O script procura o arquivo em:
> `C:\Usuários\SEU_USUÁRIO\Documentos\Euro Truck Simulator 2\config.cfg`

## ⚙️ O que é alterado

O script define os seguintes parâmetros no `config.cfg`:

```cfg
uset g_developer "1"
uset g_console "1"
