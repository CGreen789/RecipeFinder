# Week 6 Hackathon - Plateful Of Pleasure

At the end of Week 6, Sam and I were joined by Bidhan to create a React App that retrieved data from an API. 

### Step 1 - API
We were given a list of potential APIs and had to choose one.
After some time, we settled on a Recipe API (https://www.themealdb.com/api/json/v1/1/random.php).
We checked the console for how the data was structured and managed to get the data to appear in the console, so we were happy to move on to the next step.

### Step 2 - Planning
We spent some time ideating using a JamBoard - we used the Disney ideation method and spend a few minutes in each room.
We created a rough plan for our MVP and spent some time drawing our component tree in drawio on VSCode.

### Step 3 - MVP
We took it in turns to share screens and worked on the code base together. After initialising create-react-app, we worked our way down from the top (app.js), planning as we went.
We managed to get the MVP of our app working by 15:00 and talked about our next steps.
We wanted to add some functionality to the app, so you could click on the recipe itself and expand the view so it showed the full details from the API.
We decided, however, to focus on the CSS of the app. A logo was added and we spent some time working out the layout using Flexbox. In hindsight, I think CSS Grid would have been a better solution here.

### Step 4 - Retro/presentation
At the end of the day, we had a few minutes to share our app and discuss the day.
My main take-aways:
    - I'm happy we spent the time checking on the API to make sure we could access the data.
    - I felt we worked as a team well. It had just been Sam and I for the week, so adding a third on Friday changed the dynamic, but allowed both Sam and myself to slow down and work through the problems at a steady pace. This definitely helped us stay on track and make fewer errors.
    - I'd like to try to add the functionality to the app so the recipe is displayed on click.
    - We didn't write any tests for this app 
      - I'd like to have a think about how to test the different functions.


____
## INFO FROM SCHOOL OF CODE

# React-athon

## Task 1 - API Research (20 - 30 mins) ✅

Choose at least one external API to fetch data from that you'll then use in your React app. This [list](https://apilist.fun) may help. Remember to read the API's documentation and send test requests from Postman to view the data you get back first before deciding it's suitable to use. You can always use the API list we used in the hackathon earlier in the course as well.


- "https://www.themealdb.com/api/json/v1/1/random.php" Recipe API chosen
## Task 2 - Ideate and Plan (30 - 60 mins)

- Once you choose an API and test it out ✅, use Disney ideation to come up with an idea of what you want to build - what problem are you solving? Who are your users, and what do they need? Set a timer for each room (dreamer, realist, and critic). ✅
- Boil down what your MVP is and what then becomes stretch goals. Break down your idea into its component parts and prioritise your tasks. Use project management software like [Trello](https://trello.com/en) to organize your plan, breaking it down into tasks that you can then treat as tickets for each feature. Base each of these around a [user story](https://www.atlassian.com/agile/project-management/user-stories).
- Create a component tree with state and behaviour for each component and at least low-fidelity wireframes for your design.

## Task 3 - Build your MVP

Build the simplest version of your app (just enough features to be useable). Make regular commits as you build, and practice branching off for each component and merging that branch in. Use the React hooks and tools we've looked at over the past weeks where appropriate.

## Stretch Goals

Once your MVP is functioning and if you have time left, focus on what features you are going to build next - iterate through your planned stretch goals one by one. Again, make use of feature branching and atomic commits (committing often after each change).

## Retro

You'll be presenting your apps to each other, and each team member should be prepared to present about their app so an end of day wrap-up is a good idea. This is a good time to practice an [agile retrospective](https://www.atlassian.com/team-playbook/plays/retrospective) - leave time before presentations to discuss what you did well today, what you learned, what you might do differently next time, and actions you can take forward into your project next week.
