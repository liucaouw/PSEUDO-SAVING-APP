# PSEUDO-SAVING-APP
A HCI project at Northwestern University
## Tasks
### Task 1: Record the cost
  It is a very common function regarding to this kind of apps. Users can record daily cost and
can review the sum of weekly, monthly and annual cost. Our system can show the proportion of
spending on different aspects. For example, a student can record $50 which he spent for a new
book today. So he could see the money he has spent, and the percentage it takes in the total spent
money.

### Task 2: Record daily pseudo-saving
  It is one of the most important functions in our app, which the user can input the price of
something that he/she would’ve bought, but ultimately decided not to. Taking ice cream as
example, when a user considers: “Should I buy a regular ice cream cone for $2.00 or get a large
for $2.40?”, finally if he buys the regular one, which means he saves 40 cents. So, $0.4 will be
recorded here.

### Task 3: Compare prices of two different choices
  When users encounter many choices, such as different sizes, our app can give them
suggestions to decide to buy the best one according to our amazing algorithm. More concretely,
our app could help users compute unit price of items which they choose to compare
automatically and show the recommendation item. For an instance, a father saw two types of
milk: 2.5 dollars with 1 liter and 5 dollars with 4 liter. Our app will compute the unit price for
each milk($2.5/liter and $1.25/liter) and recommend him to buy 5 dollars one which unit price is
lower.

## Components
### Component 1: Data Visualization
We use pie chart to visualize the money users have spent or saved. It can give users a more
direct view of their consumption habits such as the percentage of total spent/saved money of
different item types.

### Component 2: Reward
Users can set goals for the money they want to save. And if the money they’ve saved reaches
the goals, users can see whole progress bar turns green, which means they have reached the
goals. Our application provides users with a rewarding mechanism by reminding them that they
are free to use the 90% of the money they saved. In this case, even they spend all this 90% of
money, and they still save 10% money actually.

### Component 3: Interactive Data Filter
Users could view a subset of their large data set based on provided criteria. The criteria
includes two standards, time and money type. Time includes “Week”, “Month”, and “Annual”
and money type includes “saving” and “cost”. By adopting these two criteria, users could easily
get the data they want. For example, users could see that they spent $500 totally shown in the
homepage, and 5% of them in this week belongs to entertainment in the trend page.

## Platform
Chrome on Linux.

## Modifications
1. Our TA noticed that there should be some sort of feedback on the tabs to know which one
he is in. So the tab of page that users are in will turn to light green, which is helpful for
them to know which page they are in.
2. Our TA noticed that Weekly/Monthly/Yearly look like are buttons, but functionally
they’re more like tabs. So we make these tabs bigger. And make the weekly saving as the
default. And color of this tab is light green, which may let users understand the function
of these choice. What’s more, these tabs will also turn to light green when they are
clicked. Users can then know what data they are looking at.
3. Our TA noticed that the week visualization doesn’t show up unless you click on one of
the bottom buttons. It should default to one of them. So we just make the weekly saving
as the default.
4. Our TA noticed the bottom selectors, especially on the monthly tab, are too small and
cluttered. So we decided that it can only visualize the weekly, monthly, annually data,
and we think it become much better now.
5. Our TA thought that we can rework the colors on the Month view data sheet, yellow is
impossible to read. So we just change the button to be blue, which may apply the
consistent of Norman’s principle.
6. And TA thought “Chart” isn’t a descriptive header, So we change the chart to trend.
7. And TA noticed that it is not good to use the back button, So we just get rid of these back
button and use the bottom bar instead.
8. TA noticed that there are some weird diamond. Errors in the category names in between
the name and the percentage. And we have fixed this bug now, it should work fine.
9. TA noticed that If it’s not a settings tab, it shouldn’t say setting. So we change the setting
to goal. Which meanings it is the page that let users set their goals.
10. Our TA noticed that the goals menu seems a bit sparse. So we add a process bar on the
top, and we also add a bottom bar.
11. Our TA noticed that it should be consistent with upper/lowercase in the box. And the
yyyy part is cutting off on his screen. So we just make the resize the box. And make the
box longer.
