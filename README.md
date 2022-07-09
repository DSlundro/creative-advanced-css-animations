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

## Transformazioni 2D
```scss
// esempi translate function (px, rem, %)
transform: translateX(100px);
transform: translateY(500px);
transform: translate(100px, 500px);
transform: translate(-30%, 2rem);

// esempi scale function
transform: scaleX(1.4);
transform: scaleY(.4);
transform: scale(2);

// esempi rotate function (0-360deg, 0-400grad, turn)
transform: rotate(90deg);
transform: rotate(-180deg);
transform: rotate(1turn);
transform: rotate(-0.5turn);

// esempi skew function (0-360deg)
transform: skewX(40deg);
transform: skewY(-30deg);
transform: skew(20deg, 50deg);

// transform-origin imposta l'origine per le trasformazioni di un elemento
transform-origin: 50px;
transform-origin: 20px top;
```

## Transformazioni 3D
```scss
// perspective determina la distanza tra il piano z=0 e l'utente per dare una prospettiva ad un elemento posizionato 3D
perspective: 500px;

// translateZ function
transform: translateZ(300px);

// rotate X and Y function
transform: rotateX(60deg);
transform: rotateY(40deg);
```