# FrasEsApi Docs Readme

**Bienvenidos a la documentación para FrasEsApi, una API de frases en español de uso libre y gratuito.**

La documentación en formato página web, fue desarrollada usando [htmx]("https://htmx.org/docs/") casi en su totalidad. La página está deployada en [GitHub Pages]("https://jesparzarom.github.io/FrasEsApi-Docs/") en:

 > *[FrasEsApi Docs]("https://jesparzarom.github.io/FrasEsApi-Docs/")*

Por favor, para mas detalles visita la página mencionada anteriormente.

<br>


## API ENDPOINTS

### Listas generales 
| DESCRIPCIÓN | ENDPOINT |
|-------------|------------|
| Lista de frases | `https://frasesapi.vercel.app/v1/frases/` |
| Lista de categorías | `https://frasesapi.vercel.app/v1/frases/categorias/` |
| Lista de autores | `https://frasesapi.vercel.app/v1/frases/autores/` |


<hr>


### Buscar frases
| DESCRIPCIÓN | ENDPOINT |
|-------------|------------|
| Lista de frases por autor | `https://frasesapi.vercel.app/v1/frases/buscar/?autor=<str:autor>` |
| Lista de frases por categoría | `https://frasesapi.vercel.app/v1/frases/buscar/?categoria=<str:categoria>` |
| Lista de frases por autor y categoría | `https://frasesapi.vercel.app/v1/frases/buscar/?autor=<str:autor>&categoria=<str:categoria>` |



<hr>


### Obtener frase aleatoria
| DESCRIPCIÓN | ENDPOINT |
|-------------|------------|
| Frase aleatoria | `https://frasesapi.vercel.app/v1/frases/aleatoria` |
| Frase aleatoria por autor | `https://frasesapi.vercel.app/v1/frases/aleatoria/?autor=<str:autor>` |
| Frase aleatoria por categoría | `https://frasesapi.vercel.app/v1/frases/aleatoria/?categoria=<str:categoria>` |
| Frase aleatoria por autor  y categoría| `https://frasesapi.vercel.app/v1/frases/aleatoria/?autor=<str:autor>&categoria=<str:categoria>` |


<hr>
 