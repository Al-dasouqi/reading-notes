# Forms 

HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

In most cases, it's convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form.

Then the React component that renders a form also controls what happens in that form on subsequent user input.

An input form element whose value is controlled by React in this way is called a "Controlled component".

Since the value attribute is set on our form element, the displayed value will always be this.

With a controlled component, the input's value is always driven by the React state.

In these situations, you might want to check out uncontrolled components, an alternative technique for implementing input forms.

# The Conditional (Ternary) Operator Explained

The result of your condition should be true or false or at least coerce to either boolean value.

Anything between the ? and the : is what is executed if the condition evaluates to true.

Driver =Since the condition of our conditional is true, the value between the ? and : is returned.

The movie theatre offers two ticket prices: $12 for the general public, and $8 for students.

Log(price);// 8.Since our isStudent boolean is true, the value of 8 is returned from the ternary to the price variable.

Our second conditional tests isSenior - since this is true, only the code after the ? but before the : is executed.

Let isStudent = true;let price = 12;isStudent ? (price = 8,alert('Please check for student ID' : (alert('Enjoy the movie' ;In the above example, the price of our movie is already set to $12. If isStudent is true, we adjust the price down to $8, then send an alert to have the cashier check for student ID. If isStudent is false, the above code is skipped, and we simply alert to enjoy the movie.