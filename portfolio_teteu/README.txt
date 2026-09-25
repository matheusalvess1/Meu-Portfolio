# Portfólio de Matheus Alves

Site pessoal estático feito com HTML, CSS e JavaScript, com visual escuro moderno e responsivo.

## Abrir no VS Code

1. Extraia o arquivo ZIP para uma pasta do computador.
2. Abra o VS Code.
3. Vá em **File (Arquivo) → Open Folder (Abrir Pasta)** e selecione a pasta `portfolio_teteu`.
4. Abra `index.html`.
5. Para visualizar e atualizar a página automaticamente, instale a extensão **Live Server**:
   - Clique no ícone de Extensões na barra lateral do VS Code.
   - Pesquise `Live Server` e instale uma extensão Live Server conhecida.
   - Clique com o botão direito em `index.html` e selecione **Open with Live Server**.

Você também pode abrir `index.html` diretamente no navegador, mas o Live Server facilita a visualização durante a edição.

## Personalize antes de publicar

- Confira nome, curso, experiência e textos em `index.html`.
- Troque `SEUEMAIL@exemplo.com` pelo seu e-mail real no link `mailto:`.
- Nos links do GitHub e LinkedIn, coloque os endereços exatos dos seus perfis.
- Os projetos exibidos são ideias/modelos iniciais, não trabalhos concluídos. Atualize título, descrição, status e links quando tiver projetos reais.
- Só liste tecnologias e habilidades que você conhece; ajuste os textos conforme evoluir.

## Publicar gratuitamente com GitHub Pages

1. Entre no GitHub e crie um repositório público, por exemplo `meu-portfolio`.
2. No VS Code, abra o terminal (**Terminal → New Terminal**).
3. Confirme que o terminal está na pasta do projeto e execute:

   ```bash
   git init
   git add .
   git commit -m "Adiciona meu portfolio"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/meu-portfolio.git
   git push -u origin main
   ```

4. Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub. Se o Git solicitar autenticação, entre com o fluxo de login do navegador/Git Credential Manager; não use sua senha da conta como senha do Git.
5. No repositório do GitHub, abra **Settings → Pages**.
6. Em **Build and deployment**, escolha **Deploy from a branch**.
7. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
8. Aguarde a publicação. O GitHub Pages mostrará o endereço do site na área de Pages.

Para atualizar o site depois, salve as mudanças e execute:

```bash
git add .
git commit -m "Atualiza portfolio"
git push
```

## Estrutura

- `index.html` — conteúdo e seções do site.
- `style.css` — cores, layout, estilos e adaptação para celular.
- `script.js` — menu mobile e ano automático no rodapé.
