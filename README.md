# EBTea

## QWERhacks
This project was originally created during QWERhacks 2023 where it won the title "Comeback Baby". EBTea was created by Alyssa Tadeo, [Alex West](https://github.com/awest25), [Tyler Tran](https://github.com/tylerdtran), and [Colleen Lam](https://github.com/colleenhlam). The Devpost for this hackathon project is available at https://devpost.com/software/ebtea.

## Inspiration

Our inspiration was the food insecurity presentation by the QWERhacks speakers. Individuals who are low-income and food insecure are likely to elect for nutritionally inferior options such as fast food or foods with high quantities of sugar, oils, fats, etc. 
Our project is a web application called EBTea that seeks to provide alternatives for healthier, nutritionally beneficial meals that are cheaper and more accessible by utilizing EBT/SNAP benefits.

## What it does

Our web application is a meal planner which keeps track of weekly spending and maintains user data about weekly meals. 
Current features include being able to view meal plans for the week and being able to add the meals of the day below. One can also input their daily spendings and keep track of the current/remaining balance for the rest of the week.
Future features we intend on implementing: a locator for EBT friendly and SNAP grocery stores/restaurants & nutrition ratings for each meal added to the planner in order to advise the user on how meals can be improved.

## Tech Stack
* React.js
  * Material UI
  * React Router
* Google Firebase
* GitHub

## Challenges we ran into
The initial challenge was setting up the base of the application for all four team members to begin developing. Two of us were new to React.js so we all worked together to overcome the learning curve and teach each other. Another challenge was using React hooks to fetch and update the user data in Firebase through the front-end. We solved these issues by reaching out for help with mentors at QWERhacks and discussing alternative solutions with other teammates. Additionally, we ran into problems installing npm modules which caused dependency errors.

# Using EBTea

### Local Hosting
1. `git clone https://github.com/ajtadeo/qwer-hacks-2023.git`
2. `cd qwer-hacks-2023`
3. `npm i --force`
4. `npm start` 
5. Open [http://localhost:3000](http://localhost:3000) to view EBTea in your browser.

### Deploying to Firebase
1. `cd qwer-hacks-2023`
2. `npm run build`
3. `firebase deploy`
