# SC Weddings — Site Oficial

Produtora de Filmes & Fotos para Casamentos · Ceará

---

## 📁 Estrutura do Projeto

```
scweddings/
├── index.html          ← site completo (arquivo único)
├── data/
│   └── site.json       ← BANCO DE DADOS: todos os textos e nomes das imagens
└── resize/
    ├── SMM_1654.jpg
    ├── SMM_1676.jpg
    └── ... (13 fotos)
```

---

## 🚀 Publicar no GitHub Pages

1. Crie um repositório público no GitHub
2. Suba **todos os arquivos e pastas** (`index.html`, `data/`, `resize/`)
3. Vá em **Settings → Pages → Source: main / root**
4. Acesse `https://seuuser.github.io/scweddings/`

---

## ✏️ Como editar o site

### Textos, vídeos e configurações:

1. Abra o site → clique em **Admin** (senha: `admin123`)
2. Edite o que quiser nas abas
3. Vá na aba **💾 Exportar** → clique em **Baixar data/site.json**
4. Substitua o arquivo `data/site.json` no repositório GitHub
5. Faça commit → as alterações aparecem para todos os visitantes

### Trocar uma foto:

1. Coloque o novo arquivo na pasta `resize/` do repositório
2. No Admin → aba **📸 Imagens** → troque o nome do arquivo no campo correspondente
3. Exporte o `site.json` e faça commit

---

## 📸 Fotos disponíveis (pasta `resize/`)

| Arquivo | Usado como |
|---------|-----------|
| `SMM_1654.jpg` | Hero, Sobre |
| `SMM_1676.jpg` | Cap. 01 |
| `By@ericcorrea00-8036.jpg` | Cap. 02 |
| `_RNN5463.jpg` | Cap. 03 |
| `By@ericcorrea00-7990.jpg` | Cap. 04 |
| `By@ericcorrea00-7697-2.jpg` | Cap. 05 |
| `SMM_1951.jpg` | Cap. 06, Extra 8 |
| `IMG_8855.jpg` | Extra 1 |
| `IMG_8857.jpg` | Extra 2 |
| `SMM_1665.jpg` | Extra 3 |
| `By@ericcorrea00-7700.jpg` | Extra 4 |
| `By@ericcorrea00-7909.jpg` | Extra 5 |
| `close-up-...jpeg` | Extra 6 |
| `FLORES2.png` | Extra 7, Citação, CTA |

---

## 🔐 Credenciais Admin

| Campo | Padrão |
|-------|--------|
| Usuário | `admin` |
| Senha | `admin123` |

A senha fica salva apenas no navegador em que você fez o login.
Troque na aba **🔒 Senha** do Admin.

---

## 🗄️ Sobre o `data/site.json`

Este arquivo é o banco de dados do site. Ele contém:
- Todos os textos (hero, capítulos, sobre, depoimentos, CTA...)
- Os nomes dos arquivos de imagem usados
- Links do WhatsApp, Instagram, Facebook
- Configurações de visibilidade das seções
- Vídeos do YouTube

Ao editar no Admin e baixar o JSON, você está atualizando este banco de dados.
Ao fazer commit no GitHub, todos os visitantes verão as atualizações.
