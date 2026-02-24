# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**

Accessibility means designing content so that it can be used by everyone, including people with disabilities like visual, motor, or other cognitive differences. It matters because it makes equal access to information and functionality for all users, and is also a legal requirement. Labels improve form accessibility in two key ways, they give screen readers a way to announce what each input is for, and they increase the clickable target area of an input since clicking a label focuses its associated field.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**

The `id` attribute identifies an element on the page and is used by the `for` attribute on a `<label>` to associate that **label** with a **input**, when they match, clicking the **label** focuses on the **input**. The `name` attribute is what gets sent to the server when a form is submitted. The `for` attribute belongs on the `<label>` element and its value must match the `id` of the **input** it describes, creating the accessible pairing between the two.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**

Using specific input types provides built-in validation and better user experience, for example, `type="email"` will warn the user if they forget the @ symbol, and `type="number"` prevents non-numeric characters from being entered. Using `type="text"` for everything would lose all of these benefits and push more work onto the developer or the user.

## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**

When you log into a site like Spotify, a **form** collects your email and password and submits that data to Spotify's servers. The server then checks the submitted credentials against its database, if they match a stored account, it authenticates the user. Without this form submission process, the server would have no way of knowing who is trying to access the account.
