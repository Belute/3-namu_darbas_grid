

# Grid



This project is for **educational** porpuses only. 

Site published at: About
https://belute.github.io/Grid_Example/


## Project features

-   Github pages
-   CSS GRID


## Authors

Justinas: [Github](https://github.com/belute)

## Code sample

```html

    <div class="service">
        <p>Services</p>
        <div class="container">
            <p class="servi st"></p>
            <p class="servi"></p>
            <p class="servi"></p>
        </div>
    </div>
```

```css
    body {
    display: grid;
    grid-template-columns: 1fr 500px 1fr;
    gap: 15px 20px;
    justify-content: center;
    grid-template-areas: 
     ".head"
     ".hero"
     ".service"
     ".testi"
     ".freel"
     ".foot"
    
}
```

