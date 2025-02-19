# HTML-BUTTONS

Creating buttons in HTML can be done in various ways depending on your needs. Here are some of the most common methods:<br/>

#### 1. Basic HTML Button:

    <button>Click Me</button>

#### 2. Button with a <type="Attribute">:

    <button type="button">Click Me</button>
    <button type="submit">Submit</button>
    <button type="reset">Reset</button>
    
#### 3. Link Styled as a Button:

    <a href="https://example.com" class="button">Visit Example</a>
css<br/>
/* CSS */<br/>
.button {<br/>
  display: inline-block;<br/>
  padding: 10px 20px;<br/>
  text-align: center;<br/>
  color: white;<br/>
  background-color: #007BFF;<br/>
  border-radius: 5px;<br/>
  text-decoration: none;<br/>
}<br/>
.button:hover {<br/>
  background-color: #0056b3;<br/>
}<br/>

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
css<br/>
/* CSS */<br/>
.custom-button {<br/>
  padding: 10px 20px;<br/>
  background-color: #28a745;<br/>
  color: white;<br/>
  border: none;<br/>
  border-radius: 5px;<br/>
  cursor: pointer;<br/>
  font-size: 16px;<br/>
}<br/>

.custom-button:hover {<br/>
  background-color: #218838;<br/>
}<br/>

#### 7. Button with JavaScript:

    <button onclick="myFunction()">Click Me</button>

<script><br/>
  function myFunction() {<br/>
    alert("Button was clicked!");<br/>
  }<br/>
</script><br/>

Each method serves different purposes depending on the functionality and styling the button.<br/>
