# Controle de Estoque

App de controle de estoque simples para pequenos negócios (mercadinho, lanchonete, salão, oficina, loja de roupas).
Funciona no celular como aplicativo instalado (PWA), **sem internet** e **sem cadastro**.

## O que ele faz

- **Painel:** dinheiro parado no estoque, total de produtos e alertas do que está acabando.
- **Produtos:** busca, categorias e botões **+** e **−** para mexer na quantidade com um toque.
- **Entrada, Saída e Ajuste:** com observação e validação (não deixa tirar mais do que existe).
- **Histórico:** tudo o que entrou e saiu, agrupado por dia, com filtro.
- **Lista de compras:** sugere repor até o dobro do mínimo e envia pelo WhatsApp do fornecedor.
- **Backup:** baixa e restaura os dados em um arquivo.
- Modo escuro automático e interface pensada para o toque no celular.

## Como usar

1. Abra o `index.html` (ou o link do site publicado) no celular.
2. Toque em **Configurações** (engrenagem) → **Apagar tudo** para sair dos dados de exemplo.
3. Cadastre os produtos em **Produtos → Novo produto**.
4. Para instalar: no Chrome, menu ⋮ → **Instalar app**; no iPhone, Compartilhar → **Adicionar à Tela de Início**.

## Publicar grátis no GitHub Pages

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`. Em 1 ou 2 minutos o link aparece.

## Tecnologia

HTML, CSS e JavaScript puros, sem build. Os dados ficam no `localStorage` do aparelho.
Service worker para funcionar offline (ao alterar arquivos, troque a versão em `sw.js`).

## Próximos passos

- Login e banco de dados online (Supabase) para vários aparelhos.
- Leitura de código de barras pela câmera.
- Baixa automática do estoque a cada venda no Meu Caixa.

---
Feito por **Luis Dev** · (12) 99249-8702 · [@luisrlq171](https://instagram.com/luisrlq171)
