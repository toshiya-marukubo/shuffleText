# shuffleText
This is JavaScript file.  
When mouse over element shuffle texts in html.  
It is easy to use it for everyone.
## Update Infomation
If you make setting 'onload' 'true' execute when loaded.  
If you make setting 'delay' 'true' displayed in order from top.
## Demo
- [CodePen](https://codepen.io/toshiya-marukubo/pen/gOMqvvv)  
- [https://toshiya-marukubo.github.io/shuffleText/index.html](https://toshiya-marukubo.github.io/shuffleText/index.html)  
## License
MIT
## How to use
Add a class to the element you want to shuffle.  
You can change shuffle speed.  
In that case, pass over you like numbers to 'shuffleInit'.
```
// html element
<h1>Shuffle Text on mouseover.</h1>
<ul>
  <li><a href="#" class="shuffleText">HOME</a></li>
  <li><a href="#" class="shuffleText">ABOUT</a></li>
  <li><a href="#" class="shuffleText">NEWS</a></li>
  <li><a href="#" class="shuffleText">ACCESS</a></li>
  <li><a href="#" class="shuffleText">PRICE</a></li>
  <li><a href="#" class="shuffleText">CONTACT</a></li>
</ul>

// call file
<script src="./shuffleText.js"></script>

// settings
<script>
  shuffleInit({
    class_name: 'shuffleText', // input your favorite class name.
    onload: true, // shuffle when loaded.
    delay: true, // displayed in order from top.
    number_of_iterations: 100,
    iteration_speed: 5,
    displayed_speed: 80, 
  });
</script>
```
