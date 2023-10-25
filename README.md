# First Level

Here I can write as much as I want. It renders automatically.

## Second Level

### Third Level

#### Fourth Level

<hr>

> This is a Quote

Styles:\
\
**Bold**\
_Italic_\
~~Strike~~\
**Bold com _Itálico_ dentro**\
**_Bold + Itálico_**\
Texto <sup>superscrito</sup>\
texto <sub>subsctrito</sub>\

### Third Level

<hr>

#### Fourth Level

<style>
    

    *{
        --primary: var(--primaryLight, var(--primaryDark));
        --accent: var(--accentLight, var(--accentDark));
    }

    :root{
        --primaryLight: blue;
        --accentLight: green;
    }
  
  @media (prefers-color-scheme: dark) {
    :root {
        --primaryDark: red;
        --accentDark: orange;
        }
    }

    h1{
        color:var(--primary);
    }
    hr{
        background-color:var(--accent);
    }

</style>
