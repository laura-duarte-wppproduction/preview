# 🚀 Preview de Ads (GitHub Pages)

Este repositório serve para visualizar banners HTML diretamente no browser através do GitHub Pages.

### 📁 Estrutura do Projeto

Cada formato deve estar dentro da sua própria pasta:
- /preview
- - /300x250
- - - /images
- - - index.html
- - - main.js
- - - backup-image.png

⚠️ O arquivo `index.html` é obrigatório dentro de cada pasta.

### 📤 Como subir novos banners

1. Acessar o repositório no GitHub  
2. Clicar em **Add file**  
3. Selecionar **Upload files**  
4. Arrastar a pasta do banner (ex: `160x600`)  
5. Scroll até o final  
6. Clicar em **Commit changes**

---

### 🌐 Como acessar o preview

Após o upload, o banner fica disponível no seguinte padrão:
- https://SEU-USUARIO.github.io/NOME-DO-REPO/NOME-DA-PASTA/

##### Exemplo real:

- 300x250 → https://laura-duarte-wppproduction.github.io/preview/300x250/
- 728x90 → https://laura-duarte-wppproduction.github.io/preview/728x90/

---

## ⚠️ Boas práticas (IMPORTANTE)

### 1. Caminhos relativos
Sempre usar caminhos relativos:
❌ Errado: /images/img.png
✅ Certo: images/img.png

### 2. Organização
- Uma pasta por formato
- Nomear corretamente (300x250, 728x90, etc)
- Manter arquivos organizados

### 3. Compatibilidade
- Funciona apenas com HTML, CSS e JS (front-end)
- Não suporta backend

### Dica extra
Criar um `index.html` na raiz com links para todos os formatos para facilitar a navegação:

Exemplo:
- 300x250
- 728x90
- 160x600
