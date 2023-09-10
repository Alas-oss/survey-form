# buila-a-survey-form
** start of undefined **

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css"/>
    <title>Sleep Survey Form</title>
  </head>
  <body>
    <h1 id="title">Pomodoro</h1>
    <p id="description" class="established">i need sleep</p>
    <form id="survey-form" action='https://survey-form.freecodecamp.rocks/?name=Jan&email=jan.mlinaric%40gmail.com&age=22&role=student&user-recommend=definitely&mostLike=challenges&prefer=back-end-projects&comment=a'>
    <fieldset>
      <label id="name-label">name<input id="name" type="text" placeholder="enter your name" required /></label>
      <label id="email-label">email<input id="email" type="email" required placeholder="example@gmail.com"/></label>
      <label id="number-label">email<input id="number" type="number" required min="13" max="113" placeholder="age"/></label>
      <label> which one of these best describes you current sleep situation
        <select id="dropdown">
          <option value="">Select which one applies</option>
          <option value="1">8 hours</option>
          <option value="2">7-5 hour</option>
          <option value="3">4-2 hours</option>
          <option value="4">one hour</option>
          <option value="5">I refuse to sleep</option>
        </select>
      </label>
    </fieldset>
    <fieldset>
      <label> would you recomend sleep to your freinds?</label>
      <label><input type="radio" class="inline" name="attribute" value="1 checked" /> 10/10 would recomend</label>
      <label><input type="radio" class="inline" name="attribute" value="2" /> Up too you</label>
      <label><input type="radio" class="inline" name="attribute" value="3" /> Sleep is for the weak</label>
    </fieldset>
    <fieldset>
      <label>What is your favorite thing about sleep
        <select id="dropdown2">
          <option value="">Pick one</option>
          <option value="1">The energy</option>
          <option value="2">Health</option>
          <option value="3">The bags under the eyes</option>
        </select>
      </label>
    </fieldset>
    <fieldset>
      <label> Anything else?
        <textarea rows="5" cols="50" placeholder="enter your comment here..."></textarea>
      </label>
    </fieldset>
    <fieldset>
      <input type="submit" values="Submit" id="submit" />
    </fieldset>
    <fieldset>
      <label> would you recomend sleep to your freinds?</label>
      <label><input type="checkbox" class="inline" name="attribute" value="1 checked" /> 10/10 would recomend</label>
      <label><input type="checkbox" class="inline" name="attribute" value="2" /> Up too you</label>
      <label><input type="checkbox" class="inline" name="attribute" value="3" /> Sleep is for the weak</label>
    </form>
  </body>
</html>

** end of undefined **

** start of undefined **



** end of undefined **
