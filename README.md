# RepRevolution
 Citrus Hack 2023
 
## Inspiration
When I was introduced to the three tracks and social impact was brought up with the definition of having a positive impact on society and increasing community engagement, I instantly thought of creating a gym workout tracker. Since college started, my original friend group from high school that I would often go to the gym with has spread out across California and some across the USA. When catching up, we frequently share our gym progress to keep each other in check and see our improvement rate. As I thought about it, not one of my friends uses a gym workout tracker app. We all use the iPhone "notes" app where we manually type each muscle group, workout, rep count, set count, and weight each time we go. And whenever we share our progress, we scroll through the long list of workouts saved and screenshot the plain text. This inspired me to create a website that allows the user to easily choose the date, the muscle group they're working on that day, each workout, and the number of reps, sets, and weight values. In addition, the users will be able to easily take a screenshot of their workout log that's easily readable and pleasing to the eye.

## What it does
In short, Rep Revolution allows the user to log their workouts. Thoroughly explained, Rep Revolution allows the user to pick a muscle group [Chest, back and shoulder, legs, arms], date, workout (lists of workouts are separated by muscle group, so there's no chest press when legs are chosen), rep count, weight, and set count. After picking values for said options, the user can "add an entry" which adds the chosen options to a list on the top of the page. Directly under the list, there's a button that allows the user to "download the list as a PNG", which saves the list into a PNG file, allowing for ease of sharing. 

## How I built it
I used VSCode, HTML, and JS scripts embedded inside the HTML file. 

## Challenges I ran into
I ran into many problems because this was one of my first big HTML projects. I have never worked with HTML to this extent, but this was an eye-opening project and I'm glad I was able to produce some sort of working product. 

Dynamically changing list: I wanted to have the workouts change based on the muscle group which made everything a lot harder. Rather than having a static list, the workouts changed based on what type of muscle group was chosen. 

Downloading list as PNG: I wanted to have some sort of method of sharing the workout and I didn't know how to create a network that allowed multiple users to have their own account and have that shared onto some server. I learned about html2canvas and was able to utilize that to create an image that captured the workout table and save it as a PNG file type.

## Accomplishments that I'm proud of
I'm super happy with how the dynamically changing lists and saving the workout list as a PNG turned out. I was also thoroughly surprised with the visual of the page. I was certain it would look glitchy and buggy, but it turned out to be a simplistic one-column page.

## What I learned
I learned a lot about HTML, how to create multiple types of elements, create buttons, create dynamically changing lists, and download some parts of the page as a PNG. I believe I've become much more proficient in HTML.

## What's next for Rep Revolution
When I first planned out my idea for Rep Revolution, I wanted to have some method of progress sharing where users can share their progress with their network. I also wanted to craft some sort of algorithm that provided suggestions for certain workouts based on the user's workout cycle, muscle groups targeted, and historical data. I also wanted to make Rep Revolution into a primarily mobile-based application because no one's carrying their laptop around the gym to track their workouts. But mainly the two things I hope to add to Rep Revolution are machine learning for more personalized workout suggestions and mobile app development.
