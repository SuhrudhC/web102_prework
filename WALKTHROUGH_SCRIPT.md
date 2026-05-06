# Sea Monster Crowdfunding - Website Walkthrough Script (2 minutes)

---

## [INTRODUCTION - 20 seconds]

"Hi, I'm walking you through the Sea Monster Crowdfunding website I built as part of my Web102 prework. This project taught me fundamental JavaScript concepts like DOM manipulation, array methods, and event handling. The website displays data about crowdfunded games and allows users to interact with the data in meaningful ways."

## [WELCOME SECTION - 15 seconds]

"At the top of the page, you'll see the Sea Monster header and a welcome section that explains the company's background. Below that is a dynamic description that shows the total amount raised—$800,268—across all 11 games. It also tells you that 7 games remain unfunded. This text uses a ternary operator to stay grammatically correct."

## [STATS SECTION - 25 seconds]

"The Stats section shows three key pieces of information. First, Individual Contributions displays the total number of backers across all games: 19,187. Next is the Total Raised: $800,268. And finally, the total number of games: 11. Below that, you can see the top two most funded games highlighted—Zoo Tycoon at the top, followed by How to Read Minds 2 Kit. I implemented this using the reduce() array method to sum values and destructuring to grab the top games."

## [GAME CARDS - CHALLENGE 3 - 20 seconds]

"Moving to the Our Games section, you see individual game cards for each of the 11 crowdfunded games. Each card displays the game's image, name, description, and the amount pledged. I created these cards dynamically using a for loop and DOM manipulation methods like createElement() and appendChild(). This was Challenge 3, and it taught me how to work with the DOM in real time."

## [FILTER BUTTONS - CHALLENGE 5 - 20 seconds]

"Below the game cards are three filter buttons. Let me demonstrate—if I click 'Show Unfunded Only'..."

[*Click the "Show Unfunded Only" button*]

"...the page displays only the 7 games that haven't yet met their funding goal. If I click 'Show Funded Only'..."

[*Click the "Show Funded Only" button*]

"...it shows the 4 games that have met or exceeded their goals. And 'Show All Games' brings everything back. These filters use the filter() array method to create new arrays based on whether pledged >= goal."

## [CSS & CUSTOMIZATION - 15 seconds]

"For styling, I used Flexbox to create responsive layouts for the stats cards. I also added hover effects—when you hover over the stats cards, they get a subtle blue shadow effect. This makes the interface feel more interactive and polished."

## [CLOSING - 15 seconds]

"Throughout this project, I used ES6+ features like arrow functions, template literals, and destructuring. The combination of HTML, CSS, and vanilla JavaScript created a fully functional, interactive website. This foundation prepares me well for moving into React development. Thanks for watching!"

---

## Timing Guide:
- Total: ~2 minutes (approximately 320 words)
- Introduction: 20 seconds
- Welcome Section: 15 seconds  
- Stats Section: 25 seconds
- Game Cards: 20 seconds
- Filter Buttons: 20 seconds
- CSS & Customization: 15 seconds
- Closing: 15 seconds
- Interactive Demo: 30 seconds (clicking buttons)

## Speaking Tips:
- Speak at a natural pace (~150 words per minute)
- Pause briefly when clicking buttons to let the action complete
- Point at elements on screen as you describe them
- Maintain enthusiasm about the JavaScript concepts
