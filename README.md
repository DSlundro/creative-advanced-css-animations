## Documentazione completa in italiano su CSS
```link
https://runebook.dev/it/docs/css/-index-
```

## Appunti
```scss
// significa che la transizione verrà fatta solo sulla proprietà di background-color
transition-property: background-color;

// imposta il modo in cui vengono calcolati i valori intermedi per le proprietà CSS interessate da un effetto di transizione
transition-timing-function:  ease|linear|ease-in|ease-out|ease-in-out;

// specifica la durata di attesa prima di avviare l' effetto di transizione di una proprietà
transition-delay: 500ms;

// proprietà scorciatoia per transition-property, transition-duration, transition-timing-function, e transition-delay
transition-property: all;
transition-duration: 1s;
transition-timing-function: ease-in-out;
transition-delay: 400ms;

// è possibile scrivere multiple transizioni separandole con la virgola
transition: background-color 1s ease-in-out 400ms, color 2s ease-in 200ms, font-size 3s ease-out 300ms;

// oppure raccogliere tutto insieme con la proprietà all
transition: all 1s ease-in-out 400ms;







```