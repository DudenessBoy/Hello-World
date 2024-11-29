### CSS
A stylesheet language, heavily used for styling web pages.

|_Language_|CSS|
|-|-|
|_Developer_||
|_First appeared_||
|_Filename extension_|.css|

```HelloWorld.css
body * {
    display: none;
}

body::before {
    content: "Hello World";
    font-family: helvetica, monospace;
    font-size: 2.7rem;
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}