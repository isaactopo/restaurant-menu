# Quick and Easy Restaurant Menu Index

With the COVID-19 many of our clients in the catering sector have asked us for a quick solution for their restaurant menus. The QR is back in fashion, so no one touches the food menu and instead a QR code is scanned with the mobile that takes you to a menu index. The restaurants have menus in PDF/JPG format, those are the ones that we will link to this index and… Voilà!

You can see a demo [here ⟶](https://isaactopo.github.io/restaurant-menu/)

---

![Restaurant Menu Index](shot.jpg "Quick n' Dirty Restaurant Menu Index")


## Instructions

Download or clone the repo into an empty folder
```
git clone https://github.com/isaactopo/restaurant-menu.git restaurant-menu
```

On the ```index.html``` you will find a list with the links, I have left a directory ```downloads``` to include the food menus you need, the format is up to you [PDF, JPG ...]

```html
 <ul class="menu">
    <li>
        <a href="downloads/burgers.pdf">
            BURGERS
            <em>ESP / ENG</em>
        </a>
    </li>
</ul>
```

Each anchor has a label ```<em>` `` to indicate the language of the food menu which is linked to.
In ```assets/css/style.css``` you have the basic styles with some CSS variables to change the colors and adapt it to the branding of your restaurant. You can change them within


```css
:root {
    --heading: #112730;
    --background: #fbf7f0;
    --menu-text: #112730;
    --language-label: #e29261;
    --odd: #f7845f;
    --even: #60ba8e;
    --white: #fff;
    --soft-grey: #efefef;
}
````

You can see a demo [here](https://isaactopo.github.io/restaurant-menu/)
