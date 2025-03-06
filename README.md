# Sticky Comments

![Video](docs/demo.gif)

Threw this together over a few hours: sticky nested comments. When a comment has replies to it, the parent sticks to the top so you always see the full conversation context and are able to tell when a subthread ends. What do you think? 👍 or 👎?

Issues right off the top of my mind:

* If a particular comment is too long and becomes sticky: only the bottom part of that comment sticks (demonstrated in this video)
* If a thread becomes too long while sticky: limit depth of shown child comments before offering a paginated option (e.g. 4 levels of depth and then a "continue reading" button to go deeper along with a button somewhere else to jump back to the top level - this approach can extend for any depth of replies).

I think this can be further refined so if a sub-comment only has 1 reply, it doesn't need to stick (feels redundant in such a case).

## Technical Details

The project is built using vanilla HTML, CSS, and JavaScript.

## Getting Started

1. Clone the repository
2. Open any of the HTML files in a modern web browser
3. No additional setup or dependencies required

## Browser Support

The project is compatible with modern browsers that support:

* CSS Grid
* CSS Sticky Positioning
* ES6+ JavaScript features
