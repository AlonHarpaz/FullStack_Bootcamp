# 19.1 - DOM Walk

Please make the following changes to the html file while navigating the DOM.
Create a variable that holds the <li> element with the class “start-here”.

Use traverse methods to complete these tasks:

1. Change the text from “title 2” to “main title”
2. Add another sub title with the text “sub title 4”
3. Delete the last <li> element from the list.
4. Change the <title> element text to “Master Of The Dom”.
5. Change the text of the <p> element ot something else of your

---

# 19.2 - Multiple inputs copy

Many times an application needs to verify the account by sending a verification
code by text message. Lets create a functionality the enables the user to paste
the verification code to the input fields.

Features:

1. The user is allowed to type the values manually. After each value is
   inserted, the next input will be focused.
2. The user is allowed to paste the verification code.
3. An extra challenge will be to auto submit the form once all inputs all
   populated.

Things to thing about: What happens if the user pastes only 3 digits and there
are 6 inputs to fill out.

---

# 21.1 - User Age

Create a webpage that has an input field for the user’s age and a button. If the
user enters a number above 18, make the text “you can drink appear”. If the user
enters a number below 18, make the text “you’re too young” appear.

---

# 21.3 - forEach and DOM

You get an array of objects of users from your database: const users = [ { id:
167464, firstName: "Jimmy", lastName: "Arnold", email: "jimmya@gmail.com", }, {
id: 578447, firstName: "Martha", lastName: "Goldman", email: "gold@hotmail.com",
}, { id: 864578, firstName: "Tim", lastName: "Burton", email:
"timmy.hotmail.com", }, ];

1. Loop over the array with the forEach method and dynamically create an ordered
   list of the first and last names from the objects.
2. Remove the bullet points of the ordered list with javaScript.
3. Create a custom data attribute called “data-id” and attach the id value to
   each li.
