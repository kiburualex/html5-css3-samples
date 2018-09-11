## **Waving Penguin**
- This project contains a penguin made using html5 and css3.
- Demonstrates the user of css3 variables

### **Description**
``:root`` refers to the root element of the doc which is the html
```
    :root {
        --penguin-size: 300px;
        --penguin-skin: gray;
        --penguin-belly: white;
        --penguin-beak: orange;
    }
```
styling element, ``var(--penguin-size, 300px);`` the 300px is the fallback value if variable --penguin-size has no value
```
   .penguin {
        position: relative;
        margin: auto;
        display: block;
        margin-top: 5%;
        width: var(--penguin-size, 300px);
        height: var(--penguin-size, 300px);
    }
```

### **Screenshot**
![waving-penguin](https://user-images.githubusercontent.com/20510635/45343886-d8baf900-b5aa-11e8-95d2-3415f2c41db5.gif)
