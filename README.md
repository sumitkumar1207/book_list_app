# Pure JavaScript App

This project is in pure javascript, Playing with the Localstorage and much more things!

### Example
The best part is that how you would target a certain element? So you can perform the select or click operation on a particular item.

```javascript

 static deleteBook(el) {
        if (el.classList.contains('delete')) {
            el.parentElement.parentElement.remove();
        }
    }

```
Getting the unique data so that ambiguity will not accured.

```javascript

document.querySelector('#book-list').addEventListener('click', (e) => {
    console.log('e.target :', e.target);
//Do Something with your result

});
```

```javascript
 Store.removeBook(e.target.parentElement.previousElementSibling.textContent);

```
Here Store is pointing to the Localstorage of the browser

## Authors

[Sumit Kumar](https://github.com/sumitkumar1207)

