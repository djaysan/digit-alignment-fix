# digit-alignment-fix
Fix font alignment with CSS

**🧩 Here's how to do it with CSS:**

Name a class something like: "yourclass"

Paste this code in your CSS:

````
.yourclass {
    -webkit-font-feature-settings: "lnum";
    -moz-font-feature-settings: "lnum";
    font-feature-settings: "lnum";
}
````
