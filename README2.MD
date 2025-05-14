Perguntas do Ulife

Imagens em CSS, temos várias unidades de medida que podem ser usadas para definir o tamanho de uma imagem.

 
(Pixels):
Representa o tamanho em pixels na tela.
Ideal para definir tamanhos fixos.
Quando usar: Para controle exato do tamanho da imagem, quando você precisa que a imagem tenha uma medida precisa e não dependa da resolução da tela.


(em) e rem (root em):
A unidade em é relativa ao tamanho da fonte do elemento pai, enquanto o rem é relativo ao tamanho da fonte do elemento raiz (html).
Quando usar: Para criar layouts mais responsivos e escaláveis, quando você deseja que o tamanho da imagem seja ajustado em função do tamanho da fonte. Usar rem pode ser mais previsível, pois sempre depende da raiz.


(Pontos):
Usado em impressão, onde 1 ponto é igual a 1/72 de polegada.
Quando usar: Para situações em que a visualização será feita em impressão, não tanto para design web.


(Cm) e (in):
Usadas para tamanhos físicos (centímetros e polegadas).
Quando usar: Para controlar o tamanho de imagens que precisam ser impressas ou visualizadas em dispositivos com dimensões físicas precisas.


CSS é uma linguagem usada para estilizar documentos HTML e XML. A função principal do CSS é controlar a aparência e o layout de um site, separando a estrutura (HTML) da apresentação (estilos).

Formas de utilização 

Inline CSS: Diretamente dentro de um elemento HTML utilizando o atributo style

Internal CSS: Dentro da tag <style> no cabeçalho do documento HTML

External CSS: Em um arquivo CSS separado, que é referenciado no HTML.

_________________________________________________________________________________________________________________________________________________________________________________________________________________

# Currículo HTML - Arthur Cassio Valadares de Oliveira

##  Tag `<div>`
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

##  IMG - Unidades de Medida

As unidades de medida usadas para imagens e elementos são:

- `px`: Pixels – valor fixo, não responsivo.
- `em`: Relativo ao tamanho da fonte do elemento pai.
- `rem`: Relativo ao tamanho da fonte raiz (html).
- `cm`, `in`, `pt`: Usadas mais para impressão, não recomendadas para web responsiva.
- `%`: Proporcional ao tamanho do container.
- `vw`, `vh`: Porcentagem da largura/altura da viewport.

**Melhor prática:** usar unidades relativas como `em`, `rem`, `%`, `vw` para responsividade.

---

## CSS

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

## Favicon

Favicon é o ícone exibido na aba do navegador.  
Adicionamos ele assim no `<head>`:

```html
<link rel="icon" href="imagens/favicon16.png" sizes="16x16" type="image/png">
<link rel="icon" href="imagens/favicon32.png" sizes="32x32" type="image/png">





