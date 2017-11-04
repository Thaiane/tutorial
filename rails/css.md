# Mexendo com CSS

Vamos adicionar um estilo a nossa tela? No arquivo `app/assets/stylesheets/application.css`, adicione esse código:

```css
body {
  margin: 10px;
}

.content {
    margin-left: 40px;
}

.date {
    float: right;
    color: #828282;
}

.post {
    margin-right: 15px;
    margin-bottom: 70px;
}
.post h2 {
    color: #2c0335;
    border-bottom: 1px dashed #550b84;
    padding-bottom: 10px;
}

.adicionar-post {
  float: right;
}
```

Esse código adiciona um estilo a cada um dos nossos posts, dizendo que os títulos serão roxos, assim como dá um estilo diferente para as datas.

Vamos ver como está ficando?

![Estilo final](..images/rails/estilo_final.png)

Para aprender um pouco mais sobre HTML e CSS para pode brincar e alterar cada vez mais o blog, indicamos esses sites:
- [http://www.w3schools.com/html/](http://www.w3schools.com/html/)

- [http://www.w3schools.com/css/](http://www.w3schools.com/css/)

- [https://www.codecademy.com/pt-BR/learn/web](https://www.codecademy.com/pt-BR/learn/web)

E não esqueça do Bootstrap:
- [http://getbootstrap.com/components/](http://getbootstrap.com/components/)
