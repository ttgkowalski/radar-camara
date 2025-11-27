<template>
    <div>
        <slot />
    </div>
</template>

<style>
body, html {
    margin: 0;
    padding: 0;
}

div {
    margin: 0;
    padding: 0;
}

/* Remove margens de todos os cabeçalhos */
h1, h2, h3, h4, h5, h6 {
    margin: 0;
}

/* Remove margens de parágrafos */
p {
    margin: 0;
}

/* Remove margens e paddings de listas */
ul, ol {
    margin: 0;
    padding: 0;
}

li {
    margin: 0;
    padding: 0;
}

/* Remove margens de citações */
blockquote {
    margin: 0;
}

/* Remove margens de formulários */
form {
    margin: 0;
}
</style>