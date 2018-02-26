# Web 6 React product list challenge

The goal is to list products and their categories. 
Use the supplied data files supplied. These files 
simulate data that you might get from an web API. 

## Import data

`inventory.js` exports inventory as default. This is
an array of objects. 

Each object looks like this:

```json
{
  "id":2,
  "name":"Trippledex",
  "description":"Ergonomic stable pricing structure",
  "price":"$8.45",
  "category":"Health"
}
```

`inventory.js` also exports a list of categories 
that appear in products. This is an array of Strings.

```JavaScript
["Home", "Beauty", "Food", "Animals", ... ]
```

You can use the ES6 Syntax:

`import inventory, { categories } from './inventory'`

## Components 

Think about the component structure you will use. 

My test project looked like this: 

![Example]()
