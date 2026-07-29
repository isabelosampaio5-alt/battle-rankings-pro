# Free Fire Manager Pro

# Prompt – Desenvolva um Sistema Completo de Gerenciamento de Xtreinos e Campeonatos de Free Fire



Desenvolva um projeto profissional, completo e pronto para produção utilizando **Python Django**.



## Requisitos Gerais



* Projeto completo em Django.

* Código limpo e organizado.

* Arquitetura MVC/MVT.

* Banco de dados SQLite (com opção fácil para MySQL).

* Interface moderna e responsiva.

* Compatível com desktop e celular.

* Tema escuro.

* Bootstrap 5.

* JavaScript moderno.

* CSS organizado.

* Sistema totalmente funcional.



## Login



Criar sistema de autenticação com:



* Login

* Logout

* Cadastro de administrador

* Recuperação de senha

* Controle de permissões



## Dashboard



Após o login mostrar:



* Quantidade de campeonatos

* Quantidade de equipes

* Partidas realizadas

* Ranking geral

* Últimos resultados

* Estatísticas

* Gráficos



## Campeonatos



Permitir:



* Criar campeonato

* Editar

* Excluir

* Encerrar

* Duplicar campeonato



Campos:



* Nome

* Data

* Quantidade de quedas

* Quantidade máxima de equipes

* Sistema de pontuação personalizado



## Equipes



Cadastrar:



* Nome

* Logo

* TAG

* Capitão

* Jogadores

* Observações



## Sistema de Pontuação



Permitir alterar os pontos de:



Booyah



1°



2°



3°



...



12°



Além disso:



Cada kill possui pontuação configurável.



Tudo deve ser editável pelo administrador.



## Rodadas



Cadastrar:



Queda 1



Queda 2



Queda 3



...



Até qualquer quantidade.



## Upload Automático



Na tela da rodada permitir enviar:



* 1 imagem

* 2 imagens

* 3 imagens



Formatos:



PNG



JPG



JPEG



## OCR Inteligente



Após enviar as imagens, utilizar OCR + IA para reconhecer automaticamente:



Nome da equipe



Posição



Kills



Booyah



Pontuação



Tudo automaticamente.



Se houver dúvida, destacar em amarelo para conferência manual.



## IA



Implementar reconhecimento utilizando:



Google Vision API



ou



OpenAI Vision



ou



Tesseract OCR



Criar interface para configurar API Key.



## Correção Manual



Após o OCR:



Mostrar tabela editável.



Administrador pode corrigir:



Equipe



Kills



Posição



Booyah



Salvar novamente.



## Ranking



Calcular automaticamente:



Pontos por posição



Kills



Total



Desempates



Mostrar:



Classificação



Total de kills



Total de booyahs



Total de pontos



## Tempo Real



Sempre que um resultado for salvo:



Atualizar automaticamente a classificação.



Sem precisar atualizar a página.



Utilizar WebSocket (Django Channels) ou AJAX.



## Histórico



Salvar:



Todas as rodadas



Todas as imagens enviadas



Todas as alterações



Quem editou



Data



Hora



## Exportação



Permitir exportar:



PDF



Excel



CSV



Imagem da classificação



## Compartilhamento



Gerar link público do campeonato.



Visitantes podem visualizar:



Tabela



Resultados



Ranking



Sem login.



## Interface



Criar páginas para:



Login



Dashboard



Campeonatos



Equipes



Rodadas



Upload



Resultados



Ranking



Configurações



Usuários



Perfil



## Banco de Dados



Criar todos os Models necessários.



Relacionamentos corretos.



Migrações prontas.



## API



Criar REST API completa usando Django REST Framework.



Endpoints para:



Campeonatos



Equipes



Resultados



Ranking



Uploads



## Segurança



CSRF



Proteção XSS



Proteção SQL Injection



Upload seguro



Validação completa



Permissões



## Organização



Separar:



apps/



templates/



static/



media/



services/



ocr/



api/



utils/



signals/



management/



## OCR



Criar módulo separado chamado:



ocr_service.py



Responsável por:



Receber imagem



Executar OCR



Identificar tabela do Free Fire



Extrair:



Equipe



Kills



Posição



Booyah



Retornar JSON estruturado.



## Front-end



Criar layout profissional semelhante a sistemas esportivos.



Utilizar:



Bootstrap 5



Cards



Tabelas responsivas



Modais



Toast



Loading



Dark Mode



Ícones Bootstrap.



## Instalação



Entregar tudo pronto para executar:



python -m venv venv



pip install -r requirements.txt



python manage.py migrate



python manage.py createsuperuser



python manage.py runserver



Sem qualquer erro.



## Extras



Adicionar:



Pesquisa de equipes



Filtros



Paginação



Logs



Backup do banco



Importação de equipes via Excel



Upload de logos



Sistema de notificações



Auto Save



Modo Offline (quando possível)



## Qualidade



Todo o projeto deve estar completo.



Sem código de exemplo.



Sem TODO.



Sem funções vazias.



Sem arquivos incompletos.



Gerar todos os arquivos d

o projeto, incluindo:



manage.py



requirements.txt



README.md



settings.py



urls.py



models.py



views.py



forms.py



admin.py



serializers.py



consumers.py



routing.py



signals.py



templates HTML



CSS



JavaScript



Migrações



Banco configurado



Projeto pronto para abrir no VS Code e executar imediatamente.



Ao final, entregue o projeto completo em uma estrutura de diretórios organizada, com todos os arquivos preenchidos e funcionais.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/8d663723-4758-4506-97a0-7d8116ab3ded).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
