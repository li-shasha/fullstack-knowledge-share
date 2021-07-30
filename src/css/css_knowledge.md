## css knowledge

1. what's the difference between [@import](https://developer.mozilla.org/en-US/docs/Web/CSS/@import) and [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) when import styles?

    use @import:
    ```html
   <head>
   ...
     <style>
            @import url(style.css);
        </style>
    </head>
   
    ```

    use link:
    ```html
   <head>
        <link rel="stylesheet" href="style.css">
   </head>
        
    ```

    a: link can be used as load other external resources,not only stylesheet,  @import only used to import css file
    
    b: load order: link import together when page loading, @import load after page loading. need verify?

    c: link prefered!


2.


