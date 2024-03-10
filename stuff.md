# inititated project with react and typescript with transpiler as swc

# npm installed dnd-kit

npm install @dnd-kit/core
npm install @dnd-kit/sortable

# Install tailwind css then

> TO LEARN : we can add custom color properties to tailwind by editing theme.extends like this extend:

{
colors: {
mainBackgroundColor: "$0D1117",
columnBackgroundColor: "#161C22",
},
},

> WE can also edit predefined color according to DOC

ex-

theme: {
colors: {
transparent: 'transparent',
current: 'currentColor',
'white': '#ffffff',
'purple': '#3f3cbb',
'midnight': '#121063',
'metal': '#565584',
'tahiti': '#3ab7bf',
'silver': '#ecebff',
'bubble-gum': '#ff77e9',
'bermuda': '#78dcca',
},
},
}

# after that perform cleanup of app css and index .css and add the tailwind directives

@tailwind base;
@tailwind components;
@tailwind utilities; in app.css

# after that install other tailwind utility called tailwind merge

npm install tailwind-merge

# We can apply classes to html elements using apply so for black bg and white text write this in app.css to apply this in all html/ body as well as div with root id

html,
body,
#root {
@apply bg-black text-white box-border;
}

# after that in src create a components folder and add a Kanban component
