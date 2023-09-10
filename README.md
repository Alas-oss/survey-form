# buila-a-survey-form
** start of undefined **

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>English Language Learning Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1 id="title">English Language Learning Form</h1>
    <p id="description"><i>This form helps us personalize your lessons.</i></p>
  <form method="post" id="survey-form">
    <feildset>
      <label 
        for="name" id="name-label">Name<input id="name" name="name" type="text" placeholder="enter your name" required></label>
      <label
        for="email" id="email-label">Email <input id="email" name="email" type="email" placeholder="enter your email" required></label>
      <label   
        for="occupation">Occupation <input id="occupation=label" name="occupation" type="text"></label>
     <label
        for="age" id="number-label">Age <input id="number" name="age" class="age" type="number" min="4" max="99" placeholder="enter your age" ></label>
    </fieldset>
    <fieldset>
      <label
        for="level" class="level"> What is your current English level?<input id="level-0" type="radio" name="level1" class="level" value="no-knowledge"/> No Knowledge<br>
     <input id="level-1" type="radio" name="level1" class="level" value="beginner"/> Beginner<br><input id="level-2" type="radio" name="level2" class="level" value="intermediate"/> Intermediate<br><input id="level-3" type="radio" name="level2" class="level" value="advanced"/> Advanced</label>
    </fieldset>
    <fieldset>
      <label for="reason">Why do you want to learn English? <select id="dropdown" 
       name="reason" 
        <option value="">(select one)</option>
        <option value="1">Conversation</option>
        <option value="2">Business</option>
        <option value="3">Both</option> 
        </select>
      </label>
    </fieldset>
    <fieldset>
      <label for="reason">What would you like to focus on?<br><em>Check all that apply.</em></label> 
       <label><input type="checkbox" name="Speaking" id="Speaking" value="Speaking" class="inline" />Speaking</label> 
       <label><input type="checkbox" name="Writing" id="Writing" value="Writing" class="inline" />Writing</label>
       <label><input type="checkbox" name="Reading" id="Reading" value="Reading" class="inline" />Reading</label>
       <label><input type="checkbox" name="Understanding" id="Understanding" value="Understanding" class="inline" />Understanding</label>
    </fieldset>
    <fieldset>
      <label
        for="interests">What are your interests?<em> Provide 3 </em> <input id="interests-label" name="interests" class="interests" required></label>
    <label for="additional information">Additional Information <textarea>If there is any other information you would like to share please write it here.</textarea></label>
    </fieldset>
    <fieldset>
      <label for="terms-and-conditions">
          <input id="terms-and-conditions" type="checkbox" value="checkbox" required name="terms-and-conditions" class="inline" /> I accept the <a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions.</a>
        </label>
      </fieldset>
      <input id="submit" type="submit" value="Submit"/>
    </form>
  </body>
</html>

** end of undefined **

** start of undefined **



** end of undefined **
