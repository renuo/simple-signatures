# Simple Signatures

Can we have simple HTML signatures that are built automatically?

## Instructions

1. Add an image of you already compressed with tinyPNG
2. Build your signature HTML fragment. You can simply-copy paste an existing one
3. Point to the correct image, set your name, role, number, social media links, etc...
4. Push to github
5. Open the Gmail settings 
6. Run the following script in the console: 

```js
    fetch('https://raw.githubusercontent.com/renuo/simple-signatures/main/alessandro.html').then(response => response.text()).then(body => document.querySelector('[aria-label="Signature"]').innerHTML = body)
```

7. Save the Settings
