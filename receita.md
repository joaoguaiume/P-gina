# Receitas On-line

[Receita Original](https://www.tudogostoso.com.br/receita/309779-bolo-de-chocolate-simples.html)

## Bolo de Chocolate Simples

![Bolo de Chocolate](https://static.itdg.com.br/images/640-400/3b03a942ab534200a0a80eb324828ccb/246606-postprocess-71802381-1893-4fbe-b302-726bfca18774.jpg)

### Ingredientes

#### Massa
- 2 xícaras de farinha de trigo
- 1 e 1/2 xícaras de açúcar
- 1 xícara de chocolate em pó
- 1 xícara de leite
- 1/2 xícara de óleo
- 3 ovos
- 1 colher (sopa) de fermento

#### Cobertura
- 1 lata de leite condensado
- 1/2 xícara de chocolate em pó
- 2 colheres (sopa) de manteiga
- 1 caixinha de creme de leite

---

## CSS (referência de estilo)

```css
:root {
    --bg: #eef1ff;
    --text: #2c2c44;
    --primary: #4b2e73;
    --card: #ffffff;
    --border: #e3e6f4;
}

* { box-sizing: border-box; }
body {
    margin: 0;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(180deg, #fff 0%, var(--bg) 100%);
    color: var(--text);
    padding: 1rem;
}

.page {
    max-width: 900px;
    margin: 0 auto;
}

.card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 14px;
    box-shadow: 0 10px 22px rgba(42, 44, 87, 0.12);
    padding: 1rem 1.2rem;
}

.card h1 { color: var(--primary); }
.card h2 { color: #30335f; font-size: 1.6rem; margin-bottom: 0.4rem; }
.card img { width: 100%; max-width: 500px; border-radius: 10px; border: 1px solid #e9ebfb; margin-bottom: 0.8rem; }
.recipe-link { display: inline-block; margin-top: 0.4rem; margin-bottom: 0.8rem; text-decoration: none; background: var(--primary); color: #fff; padding: 0.4rem 0.8rem; border-radius: 999px; font-size: 0.9rem; transition: transform 0.2s ease, background 0.2s ease; }
.recipe-link:hover { background: #3d235b; transform: translateY(-2px); }

.card h3, .card h4 { margin-bottom: 0.2rem; }
.card ul { margin: 0 0 1rem 1.2rem; padding: 0; color: #444b70; }

@media (max-width: 700px) {
    body { padding: 0.5rem; }
    .card { padding: 0.9rem; }
    .card h2 { font-size: 1.35rem; }
}
```
