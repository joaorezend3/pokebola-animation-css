# Pokébola Animation (Apenas por diversão)

## 🎥gif:

![img]()

## Sobre:

Este projeto é uma animação simples de uma Pokébola, criada apenas para diversão. Quando você clica na bola, ela gira infinitamente, e quando você clica novamente, ela para de girar.<br> A animação foi criada usando a diretiva @keyframes do CSS:

```css
@keyframes spin {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}
```

E ativada usando JavaScript:

```javascript
const element = document.querySelector(".bola");
element.addEventListener("click", () => {
  element.classList.toggle("girarClick");
});
```

## Tecnologias usadas

-    CSS
-    JavaScript
-    html5
