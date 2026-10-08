# Taxômetro 📱

> Compare taxas de máquinas de cartão e descubra a melhor opção para o seu negócio.

**App web progressivo (PWA) para lojistas brasileiros compararem taxas de adquirentes de pagamento — 100% offline, sem servidor, arquivo único.**

---

## 🌐 Acessar o app

👉 **[taxometro.github.io](https://SEU_USUARIO.github.io/taxometro)**

---

## ✅ Funcionalidades

- Comparar PIX, débito, crédito à vista e parcelado (1x–18x)
- Simulador de venda: valor líquido por adquirente
- Consultor Inteligente com faturamento exato e custo em R$/mês
- Análise IA com dados reais do mercado
- Modo Negociação: calcula economia se fechar nas taxas prometidas
- Taxas de mercado: compara com tabela pública atual
- Salvar comparações com versionamento automático
- Exportar PDF profissional
- Exportar para Google Sheets
- Histórico de evolução das taxas
- Modo claro/escuro
- 100% offline (Service Worker + IndexedDB)
- Dados criptografados com AES-256

---

## 🏗️ Estrutura

```
taxometro/
├── index.html              ← app completo (single file)
├── politica-de-privacidade.html
├── manifest.json           ← PWA manifest
├── sw.js                   ← Service Worker externo (opcional)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

---

## 📱 Instalar como app (PWA)

**Android (Chrome):**
1. Abra o link no Chrome
2. Toque nos 3 pontos → "Adicionar à tela inicial"

**iPhone (Safari):**
1. Abra o link no Safari
2. Toque em compartilhar → "Adicionar à Tela de Início"

---

## 🔒 Segurança

- Dados locais criptografados com **AES-256-GCM**
- API Anthropic protegida via **Cloudflare Worker** (proxy)
- Nenhum dado enviado a servidores externos

---

## 📄 Licença

Uso privado. Todos os direitos reservados.
