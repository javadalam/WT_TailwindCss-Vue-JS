## Aufgabe 2 (20 Minuten)

Die Navigationsleiste mit den TailwindCSS Klassen erweitern.


Für die Entwicklung der Navigationsleiste benötigen Sie die Icons, die ich vorher im Icon-Ordner als SVG-Datei vorbereitet habe.

Sie können den folgenden Code als Beispiel schauen , um zu verstehen, wie man Icons in der Komponente verwendet.

```sh
<script>
import IconHome from "./icons/IconHome.vue"
export default {
    components:{
        IconHome,
     }
};
</script>
```

```sh
<a href="/" class="group ">
    <IconTeam />
        <span class="">Team</span>
</a>
```



![Getting Started](./pic2.PNG)
