# Currículo HTML - Arthur Cassio Valadares de Oliveira

## 📌 Tag `<div>`
A tag `<div>` é usada como um container genérico para agrupar conteúdos em blocos. É muito utilizada para organizar a estrutura do HTML junto com o CSS.

**Uso no currículo:**  
Foi utilizada para agrupar todo o conteúdo principal dentro de uma `<div class="conteudo">`.

**Atributos possíveis:**
- `id`
- `class`
- `style`
- `title`
- `hidden` (e outros atributos globais)

---

## 📷 IMG - Unidades de Medida

As unidades de medida usadas para imagens e elementos são:

- `px`: Pixels – valor fixo, não responsivo.
- `em`: Relativo ao tamanho da fonte do elemento pai.
- `rem`: Relativo ao tamanho da fonte raiz (html).
- `cm`, `in`, `pt`: Usadas mais para impressão, não recomendadas para web responsiva.
- `%`: Proporcional ao tamanho do container.
- `vw`, `vh`: Porcentagem da largura/altura da viewport.

**Melhor prática:** usar unidades relativas como `em`, `rem`, `%`, `vw` para responsividade.

---

## 🎨 CSS

### O que é?
CSS (Cascading Style Sheets) é a linguagem usada para estilizar elementos HTML — cor, layout, fonte, espaçamento, bordas, etc.

### Formas de utilização:
- **Inline**: dentro do próprio elemento (evitar).
- **Interno**: dentro da tag `<style>` no `<head>`.
- **Externo**: via arquivo `.css` externo (mais recomendado).

### O que foi usado no currículo:
- CSS interno para fonte, cor, tamanho.
- Google Fonts (`Roboto`) para tipografia.
- Medidas relativas e borda arredondada para a foto.

---

## 🌐 Favicon

Favicon é o ícone exibido na aba do navegador.  
Adicionamos ele assim no `<head>`:

```html
<link rel="icon" href="imagens/favicon16.png" sizes="16x16" type="image/png">
<link rel="icon" href="imagens/favicon32.png" sizes="32x32" type="image/png">
