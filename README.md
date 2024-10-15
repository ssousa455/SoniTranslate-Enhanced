# SoniTranslate-Enhanced
Versão aprimorada do SoniTranslate com cópia automática para o Google Drive e melhorias de desempenho
# SoniTranslate-Enhanced

Este projeto é uma versão aprimorada do excelente [SoniTranslate](https://github.com/R3gm/SoniTranslate).  Ele mantém todas as funcionalidades originais, adicionando melhorias significativas para facilitar o uso e garantir a segurança dos seus arquivos dublados.

## Melhorias em relação ao SoniTranslate original:

* **Cópia automática para o Google Drive:** Os arquivos de áudio dublados são copiados automaticamente para a sua pasta "Dubbing" no Google Drive, mesmo se o processo for interrompido.  Isso elimina a preocupação com a perda de dados.
* **Melhorias de desempenho na instalação:** O código agora verifica a existência de pacotes antes de instalá-los, evitando reinstalações desnecessárias e reduzindo significativamente o tempo de configuração.  A instalação de dependências é agora mais robusta e eficiente.
* **Tratamento de interrupções:** O código inclui um bloco `try...except...finally` para garantir que os arquivos sejam copiados para o Google Drive mesmo se a execução for interrompida manualmente (por exemplo, com Ctrl+C) ou por um erro inesperado.


## 🚀 Acesso Rápido

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ssousa455/SoniTranslate-Enhanced/blob/main/untitled6.py)


## Funcionalidades:

* Todas as funcionalidades do SoniTranslate original (tradução de áudio de vídeo, síntese de voz, etc.).
* Cópia automática dos arquivos dublados para o Google Drive.
* Suporte a múltiplos idiomas de interface.
* Tratamento de erros aprimorado e mensagens de log mais informativas.


## Pré-requisitos:

* Python 3.7+
* Conta do Google Drive
* FFmpeg instalado no sistema
* Uma chave de acesso do Hugging Face (para acessar modelos de processamento de linguagem).
* [Potencialmente outras dependências, dependendo das opções de TTS e outras bibliotecas usadas]


## Instalação:

1. Clone o repositório: `git clone <seu_repositorio>`
2. Instale as dependências: `pip install -r requirements.txt` (crie um arquivo `requirements.txt` listando todas as dependências necessárias, incluindo as do SoniTranslate original e quaisquer outras adicionadas).
3. Configure sua chave de acesso do Hugging Face no ambiente (como descrito no código).
4. Autentique sua conta do Google Drive (se necessário).


## Como Usar:

1. Coloque o vídeo que deseja dublar na pasta `/content` do Google Colab.
2. Execute o notebook `untitled6.py` no Google Colab.
3. Forneça seu token do Hugging Face quando solicitado.
4. Selecione as opções de idioma e tema da interface.
5. Aguardar a conclusão do processo de dublagem. Os arquivos dublados serão salvos em `/content/SoniTranslate/outputs` e copiados para sua pasta "Dubbing" no Google Drive.


## Contribuições:

Contribuições são bem-vindas!  Abra issues ou envie pull requests.

## Licença:

[Especifique a licença do seu projeto.  MIT é uma boa opção.]

## Agradecimentos:

* R3gm pelo projeto original SoniTranslate.
* [Adicione outros agradecimentos, se aplicável]

**Dê uma estrela ⭐ para este projeto para mostrar seu apoio!**

## Agradecimentos:

* R3gm pelo projeto original SoniTranslate.
* [Adicione outros agradecimentos]

**Dê uma estrela ⭐ para este projeto para mostrar seu apoio!**
