# 🚀 Como Publicar o Taxômetro no GitHub Pages

Siga este guia passo a passo. Tempo estimado: **15 minutos**.

---

## PASSO 1 — Criar conta no GitHub

1. Acesse **https://github.com**
2. Clique em **Sign up** (é gratuito)
3. Escolha um nome de usuário — este nome aparecerá na URL do app
   - Ex: se escolher `henk`, a URL será `henk.github.io/taxometro`
4. Confirme o e-mail

---

## PASSO 2 — Criar o repositório

1. Após fazer login, clique no **+** (canto superior direito) → **New repository**
2. Preencha:
   - **Repository name:** `taxometro`
   - **Description:** Compare taxas de máquinas de cartão
   - Marque **Public** (obrigatório para GitHub Pages gratuito)
   - NÃO marque "Initialize this repository"
3. Clique em **Create repository**

---

## PASSO 3 — Fazer upload dos arquivos

Na página do repositório recém-criado:

1. Clique em **uploading an existing file** (link no centro da página)
2. Arraste TODOS os arquivos desta pasta para a área de upload:
   ```
   ✅ index.html
   ✅ manifest.json
   ✅ sw.js
   ✅ 404.html
   ✅ _config.yml
   ✅ politica-de-privacidade.html
   ✅ README.md
   ✅ pasta icons/ (com todos os ícones dentro)
   ```
3. Em **Commit changes**, escreva: `Publicação inicial do Taxômetro`
4. Clique em **Commit changes**

---

## PASSO 4 — Ativar o GitHub Pages

1. No repositório, clique em **Settings** (aba no topo)
2. No menu lateral esquerdo, clique em **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Em **Branch**, selecione **main** e pasta **/ (root)**
5. Clique em **Save**
6. Aguarde 1–3 minutos

---

## PASSO 5 — Acessar o app publicado

Após a publicação aparecer uma caixa verde com:

```
✅ Your site is live at https://SEU_USUARIO.github.io/taxometro
```

Abra esse link no celular e teste!

---

## PASSO 6 — Instalar como app no celular

**Android (Chrome):**
1. Abra o link no Chrome
2. Toque nos 3 pontos → "Adicionar à tela inicial"
3. Confirme — o Taxômetro aparece como app na tela inicial

**iPhone (Safari):**
1. Abra o link no Safari (não Chrome!)
2. Toque no ícone de compartilhar (quadrado com seta)
3. Role para baixo → "Adicionar à Tela de Início"
4. Confirme

---

## 📝 Como atualizar o app depois

Sempre que modificar o `index.html`:

1. Acesse seu repositório em **github.com/SEU_USUARIO/taxometro**
2. Clique no arquivo `index.html`
3. Clique no ícone de lápis (✏️ Edit)
4. Selecione tudo, apague e cole o novo conteúdo
5. Clique em **Commit changes**
6. Aguarde ~1 minuto e recarregue o app

**Alternativa mais fácil (arrastar e soltar):**
1. Na página do repositório, clique em **Add file → Upload files**
2. Arraste o novo `index.html` por cima do antigo
3. Commit — o arquivo é substituído automaticamente

---

## 🔗 Configurar URL personalizada (opcional)

Se tiver um domínio próprio (ex: taxometro.com.br):

1. Em **Settings → Pages → Custom domain**
2. Digite seu domínio e clique **Save**
3. No seu provedor de domínio, crie um registro CNAME:
   - Nome: `www`
   - Valor: `SEU_USUARIO.github.io`

---

## ❓ Problemas comuns

| Problema | Solução |
|---|---|
| Página em branco | Aguarde mais 2–3 minutos e recarregue |
| App não instala no celular | Certifique que o manifest.json foi enviado |
| Ícone não aparece | Verifique se a pasta icons/ foi enviada completa |
| Mudanças não aparecem | Force recarregamento: Ctrl+Shift+R (ou Cmd+Shift+R) |
| "404 not found" | Verifique se o arquivo se chama exatamente `index.html` |

---

## 🌐 URL final do seu app

```
https://SEU_USUARIO.github.io/taxometro
```

Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub.
