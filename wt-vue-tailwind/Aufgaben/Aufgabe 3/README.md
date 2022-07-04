## Aufgabe 3 (20 Minuten)

In der Component `anmelden.vue` haben Sie einen schönen `<div> Content </div>` erstellt. Entwickeln Sie nun diesen Bereich als Beispiel für ein Anmeldeformular.

![Getting Started](./pic25.PNG)

Für diese Aufgabe versuchen sie auch mit index.css arbeiten, wie beispiel.

Vorher 
```sh
<form class="mb-0 mt-8 space-y-6" action="#" method="POST"></form>
```
index.css 

```sh
@layer components {
    .form {@apply mb-0 mt-8 space-y-6;}
}
```

Nachher
```sh
<form class="form" action="#" method="POST"></form>
```



