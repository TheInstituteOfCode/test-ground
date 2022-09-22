---
layout: default
---
# test
``` html
<section class="bob" id="bob">
    <h1>dave</h1>
</section>
{% raw %}
{% for thing in place %}
<section class="bob" >
    <h1>dave</h1>
    <input name="non" required>
</section>
{% endfor %}
{% endraw %}
```


``` css
body #about .class {
    background-image: url('www.bob.com/bob.jpg');
    background-size: cover;
    background-position: 50% 50%;
    color: rgba(0,0,0)
}
a{
    color: red;
}

/* Dark Mode Toggle  */

.dark-mode {
  text-align: right;
}

.dark-mode p {
  margin-bottom: 0.3rem;
  font-size: 0.9rem;
}

.toggle-container {
  background-color: lightblue;
  height: 2rem;
  width: 4rem;
  padding: 0.2rem;
  display: inline-block;
  border-radius: 3rem;
  text-align: left;
}

.toggle-ball {
  background-color: white;
  height: 1.6rem;
  width: 1.6rem;
  display: inline-block;
  border-radius: 2rem;
}

.toggle-container.dark-mode-active {
  background-color: #ade6d8;
  text-align: right;
}
```



<script src="/prism.js" defer></script>