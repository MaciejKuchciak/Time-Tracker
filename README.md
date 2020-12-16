# Time Tracker
A time management application written in JavaScript. The application allows the user to add tasks (each has a title and description), and add detailed operations needed to complete a given task.

---

## About application

An application that does not contain any data in its code, instead it uses REST API, hence relies on communication with the server. This application communitaces with API by CodersLab, therefore a mandatory step is to generate a token at [get token](https://todo-api.coderslab.pl/apikey/create), copy it and paste into the const "apikey", in the script.js file. Otherwise it won't work.

We can add whatever task we want. The task may be "Grandma's birthday", with the description "Grandma Maria is 80 this year!". The operations might be:
> - buy birthday decorations
> - decorate the living room
> - bake a cake
> - to prepare food
> - invite the family

By clicking on the "+ 15m" or "+ 1h" buttons, we will add the time to the counter that is available for each operation. Thanks to this, after the birthday we will know that baking a cake takes "6h 30m", and inviting a family "45m".
When the task is completed, we can mark it as finished by clicking "Finish". The completed task is read-only - we will not add new operations or time to the current operations. They also cannot be removed.

With this project I practiced:
> - coding in JavaScript and CSS
> - working with the Fetch API
> - modifying an already existing DOM tree

---

## About author

My name is Maciej and I've started my adventure with programming in 2020. It derives me a lot of satisfaction, pleasure and fun to code and finding solutions to our problems which we can face everyday in our both professional and private life.
More about my experience you can find out here: [LinkedIn](https://www.linkedin.com/in/maciejkuchciak/)

---

### Thank you for looking at my app! ;)
