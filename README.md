# HTML-BUTTONS

Creating buttons in HTML can be done in various ways depending on your needs. Here are some of the most common methods:

#### 1. Basic HTML Button:

    <button>Click Me</button>

#### 2. Button with a <type="Attribute">:

    <button type="button">Click Me</button>
    <button type="submit">Submit</button>
    <button type="reset">Reset</button>
    
#### 3. Link Styled as a Button:

    <a href="https://example.com" class="button">Visit Example</a>
css
/* CSS */
.button {
  display: inline-block;
  padding: 10px 20px;
  text-align: center;
  color: white;
  background-color: #007BFF;
  border-radius: 5px;
  text-decoration: none;
}
.button:hover {
  background-color: #0056b3;
}

#### 4. Input Element Styled as a Button:

    <input type="button" value="Click Me">
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
#### 5. Button with an Icon:

    <button>
      <img src="icon.png" alt="Icon" style="width: 16px; height: 16px; vertical-align: middle;">
      Click Me
    </button>
    
#### 6. Customized Button with CSS:

    <button class="custom-button">Click Me</button>
css
/* CSS */
.custom-button {
  padding: 10px 20px;
  background-color: #28a745;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

.custom-button:hover {
  background-color: #218838;
}

#### 7. Button with JavaScript:

    <button onclick="myFunction()">Click Me</button>

<script>
  function myFunction() {
    alert("Button was clicked!");
  }
</script>

Each method serves different purposes depending on the functionality and styling the button.
