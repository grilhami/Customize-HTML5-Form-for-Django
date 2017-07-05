# Customize-HTML5-Form-for-Django

This style is my own customize HTML 5 Form for my current Django Project. For now i'm still using the <style> tag for the styling.
But in the future, i will make sure to seperate it in an css file for better readibility.

# Using the <style> tag

To use it, you must add the following codes in your html file with the corresponding elements

```
<style>
form {
  margin: 0 auto;
  width: 300px;
  background-color: #EEBB16;
  padding: 10px 25%;
  border: 25px solid #555556;
  border-radius: 20px;
  color: #555556;
  font-family: 'Inconsolata', monospace;
}
h1 {
  font-family: 'Indie Flower', cursive;
  text-align: center;
  font-size: 200px;
  margin: 0 auto;
}
input[type=button], input[type=submit], input[type=reset] {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 16px 32px;
    text-decoration: none;
    margin: 4px 2px;
    cursor: pointer;
}
</style>
```
Hope you enjoy it! :)
