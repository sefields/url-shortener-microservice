# URL Shortener Microservice
### by Sam
### Endpoint: https://sam-shorten.glitch.me/ 
### Instructions / Code Samples:

> #### 1. Pass in a long URL using /new/

> $.getJSON('https://sam-shorten.glitch.me/new/https://i.pinimg.com/736x/97/c2/64/97c264aa837fca6c945cd7b0c16fe0dd--daisies-sunflowers.jpg', function(data) {
  /* do something with 'data' */
});
   

> #### 2. Receive an object with an original_url field, and a shiny new short_url field!

> {"original_url":"https://i.pinimg.com/736x/97/c2/64/97c264aa837fca6c945cd7b0c16fe0dd--daisies-sunflowers.jpg","short_url":"https://sam-shorten.glitch.me/0"}

> #### 3. Point your browser at the short_url to see the original_url's page:

> https://sam-shorten.glitch.me/0

> ![doggy](https://sam-shorten.glitch.me/0)

### Demo

#### Try for yourself [here](https://codepen.io/sefields/pen/qXeBER)!
