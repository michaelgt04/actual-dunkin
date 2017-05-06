# React Livecode Clinic

## Description

React, oh React. Don't worry if you're still getting the hang of React and setting
up your application. Given all the configuration we have to do for React, you all
should be excited to get anything to display on the page at all.

Thank you all for indulging me and sitting with me as I geeked out about this
'Actual Customers of Dunkin' skit. I maintain it's one of the best I've seen on
SNL in a long time.

A couple of things for you all to remember as we head into the rest of the week and
the system check on Friday:

1.  Don't forget to import `React` and `Component` (if you're making a stateful
component). Without those, you won't have access to the React library.

2.  Don't forget to export new components at the end of your definition and to import
them wherever else you're using them!

3.  Bind your handler functions! Without the binding process in your constructor
you will run into all kinds of crazy issues with your state.

4.  Take everything one step at a time. Make sure you've got your new
component hooked up the right way and then worry getting your display logic and
handler functions. It will help you debug more effectively.

5.  Finally, `debugger` and `console.log` are your best friends. Do. Not. Forget.
Them.

## Setup

You'll need to run the following commands to get started!

`npm install`
`bundle install`

Then in order to get the application up and running you have to open up two
tabs and run `ruby server.rb` in one and `webpack --watch` in the other!
