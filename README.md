# builf-my-first-course-exit-survey-form
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>

  <body>
    <h1 id="title">course exit survey</h1>
    <p id="description">This course provided valuable knowledge and helped me strengthen my understanding of key concepts.The lessons were clear,engaging,and useful for improving my practical skills and confidence.
    </p>
   
<form id="survey-form">
  <label for="name" id="name-label" >Full Name:</label>
  <input id="name" type="text"placeholder="Write your name here..." required/>
   <label for="email" id ="email-label">email id:</label>
   <input id="email" type="email" placeholder="Write your email "size="20"required/>
    <label for="number"  id="number-label">phone no.:</label>
    <input id="number" placeholder="Write your no. here"  type="number" max="12" min="10" required/>

<label for="dropdown">choose any one</label>
<select id="dropdown" name="dropdown">
<option selected value="student">Student</option>
<option value="parents">parent</option>
<option  value="teacher">teacher</option>

</select>


<label for="college" >College review out of 3
<input type="radio" name="review" value="Bad"> Bad
<input type="radio" name="review" value="good">Good

<input type="radio" name="review" value="Excellent">Exellent
</label>

<label for="satisfaction">ARE YOU SATISFIED WITH THE COURSE EXIT SURVEY:
<input type="checkbox" value="no">No
<input type="checkbox" value="yes">Yes
</label>
<SECTION>
<label for="comments">Extra comments</label>
<textarea id="comments"

  name="comments"
  rows="4"
  cols="40"
  placeholder="Write your message here..."
  required></textarea>
    <button id="submit" type="submit">Submit</button>
</selection
</form>
    </p>
  </body>
</html>
