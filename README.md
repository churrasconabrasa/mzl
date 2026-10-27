# Churrasco na Brasa — Fluxo de Caixa (PWA)

Aplicativo web instalável para Chrome e Microsoft Edge, com cache offline do aplicativo e dados mantidos no armazenamento local do navegador.

## Publicar usando GitHub Pages
1. Entre no GitHub e crie um repositório novo, por exemplo `churrasco-na-brasa`.
2. Extraia este ZIP no computador.
3. Envie **todos os arquivos e a pasta `icons`** para a raiz do repositório. O `index.html` precisa ficar na raiz.
4. No repositório, abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/(root)` e salve.
6. Aguarde a publicação e abra o endereço HTTPS mostrado pelo GitHub Pages.
7. No notebook, usando Chrome ou Edge, clique em **＋ Instalar app** no sistema ou use o menu do navegador para instalar o site como aplicativo. Confirme a instalação; ele aparecerá no menu Iniciar/Aplicativos e poderá ser fixado na área de trabalho ou barra de tarefas.

## Importante sobre os dados
- Para a instalação PWA, o site deve estar publicado em HTTPS; abrir o HTML diretamente pelo arquivo local não habilita instalação PWA completa.
- Os registros ficam no armazenamento do navegador e são específicos para o endereço publicado e o perfil do navegador. Dados existentes na versão antiga não migram automaticamente. Faça um **Backup** antes de mudar de versão ou endereço.
- O cache permite abrir a estrutura do app offline depois da primeira visita online. Para o uso inicial, abra o site com internet.
