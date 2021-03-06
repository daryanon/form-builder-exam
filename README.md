# Form Builder Task
Welcome to the Form Builder application exam. This app is simple web application that allows the user to create a custom form to which anyone can submit answers. (Think: Google Forms)

You can use **any stack** you like: any language for the server(java, c#, python, node and etc.), and any framework for the javascript client part(React, Angular, Vue.js and etc.). You will have to deploy your app to some server.

You can use any general purpose libraries, that are not specifically solve the "form building" case.
However, please note, you will be required to add additional functionality after you finish the project, when choosing libraries, keep that in mind.

Example of things you can (only if you _like to_, it's just an example) use:
[express](https://expressjs.com/),
[typeorm](https://github.com/typeorm/typeorm),
[mongoose](https://mongoosejs.com/),
[axios](https://github.com/axios/axios),
[material-ui](https://material-ui.com/),
[react-bootstrap](https://react-bootstrap.github.io/),
[wix-style-react](https://github.com/wix/wix-style-react),

glhf

# Instructions

You're required to build a Web-Application with the pages below.

## List of Pages
 * [Forms List Page](#forms-list-page)
 * [Form Builder Page](#form-builder-page)
 * [Form Submit Page](#form-submit-page)
 * [Form Submissions Page](#form-submissions-page)

### Forms List Page
This page will include a list of all forms and a link to create new form.

The list of forms is a table with the following columns:
 1. Form id
 2. Form Name
 3. Number of Submissions
 4. link to Form Submit Page
 5. link to Form Submissions Page

For Example:

| Form Id | Form Name       | # Submissions | Submit Page | Submissions Page |
|:-------:| --------------- | ------------- |:-----------:|:----------------:|
| 1       | Task Feedback   | 0             | [View](#form-submit-page)   | [View](#form-submissions-page) |
| 2       | Job Application | 152           | [View](#form-submit-page)   | [View](#form-submissions-page) |

### Form Builder Page
In this page, you'll implement a wizard to create form. You will see a form, where you enter **field label**, **input name** and **input type** and press on an "Add Field" button in order to add this form. the field label and input name are free text, and the input type is of the following input types: **text, color, date, email, tel, number** (you can read more here - [HTML input types](https://www.w3schools.com/html/html_form_input_types.asp)).

After adding a field you should see your input with the label on the screen. When you are done adding fields you should enter **Form Name** and press on the save button in order to add the form to your forms list and redirect to the form-list.

### Form Submit Page
For an url with the id of the form, you will see all the fields you created in the **Form Builder Page**, and a submit button. on submit, all data will be saved to the **Form Submissions Page**.

### Form Submissions Page
For an url with the id of the form, you will see all the form submissions in a table when each header is the field name, and each row is a submission with the user input.

## Before Submitting
* Make sure to use clean code. (References: [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882), [Code Complete](https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670/) ). Make use of tools that will help you with standtard [formatting](https://prettier.io/) an [linting](https://eslint.org/).
* Your data should be presistent and well structured. When choosing a storage mechanism, consider it's pros and cons, use whatever suites the problem at hand, use proper entities and relations. (You can choose whatever storage solution you like)
* You might be required to explain your implementation, make sure you understand all your code.

## Submitting your project
After you've completed your tasks, and you are ready to submit it, do the following:
* Create a git repositry (preferably on github.com)
* Make sure all the code is committed and pushed
* Make sure you added a markdown file (`README.md`) with instructions on how to run your project from scratch, that must include any operations that is required in order to run the project (i.e. setup a database, create tables, etc.)
* Deploy your work to be viewed from any computer (you can find simple free deployment in [heroku](https://www.heroku.com/), but you can also find one in Amazon, Google, Azure and more).
* Clone your repo and use your instructions to see it works as expected
* Add `shalevshalit`, `itzikkit` and `Wo1v3r` as users to the repo (Master permission)
* Send us an email with your repo link
* Profit!

Please contact `shalevsh@wix.com` or `itzikk@wix.com` or `jonathanl@wix.com` for details
