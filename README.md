# 🏕️ ABCL — Acampamento Bíblico Conselheiro Lafaiete

Site oficial do Acampamento Bíblico da Mocidade da Casa de Oração de Conselheiro Lafaiete/MG.

---

## 📁 Estrutura do projeto

```
abcl/
├── index.html          ← Página principal
├── css/
│   └── style.css       ← Todo o visual do site
├── js/
│   └── main.js         ← Interatividade (nav, countdown, FAQ, formulário)
├── assets/
│   └── logo-abcl.png   ← Logo principal
└── README.md
```

---

## 🔧 Como atualizar para a próxima edição

### 1. Dados principais (index.html)
No topo do `index.html` há um comentário com todos os dados da edição atual.
Atualize esse bloco e use-o como guia para editar o HTML:

```html
<!--
  Edição:      14º
  Ano:         2027
  Data:        XX a XX de Mês de 2027
  ...
-->
```

### 2. Countdown (js/main.js)
Altere a data no objeto `CONFIG`:

```js
const CONFIG = {
  DATA_ACAMPAMENTO: '2027-06-10T00:00:00',  // ← nova data
  WHATSAPP_NUM:     '5531988262599',
  FORMS_URL:        'https://forms.gle/...',  // ← novo link do Forms
};
```

### 3. Cores (css/style.css)
Para mudar a paleta inteira, edite apenas as variáveis no topo:

```css
:root {
  --verde:       #2D6A4F;
  --verde-mid:   #40916C;
  --verde-claro: #74C69D;
  /* ... */
}
```

### 4. Logo
Substitua o arquivo `assets/logo-abcl.png` pelo da nova edição
(mantenha o mesmo nome para não precisar editar o HTML).

---

## 🚀 Deploy

O projeto é HTML/CSS/JS puro — sem dependências, sem build.
Pode ser hospedado em qualquer lugar:

| Opção         | Como fazer |
|---------------|-----------|
| **GitHub Pages** | Suba a pasta no repositório → Settings → Pages → Branch main |
| **Netlify**      | Arraste a pasta no [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel**       | `vercel --prod` na pasta do projeto |
| **Hospedagem tradicional** | Envie os arquivos por FTP |

> **Atenção:** Mantenha a estrutura de pastas intacta ao fazer upload.

---

## 📞 Contatos da organização

- Haniel Soares
- Naasson Vieira
- Mauri Diniz

WhatsApp: **(31) 98826-2599**

Endereço: Rua Cônego João Pio, 60 — Lourdes, Conselheiro Lafaiete/MG
