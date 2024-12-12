# FetchProject
### Steps to Run the App

Just Open the FetchProject.xcodeproj file and run

The app will show the main list of recipes, if you wish to reload them you can just drag the screen and any new recipes or changes made in this url will appear here. At the top of the application you will see 3 options "Normal", "Malformed", and "Empty" you can change between on any of these and the table will update for that option. For Malformed and Empty you will get an error pop up with an appropiate error handling.

### Focus Areas: What specific areas of the project did you prioritize? Why did you choose to focus on these areas?

My focus was the Network Manager, as it contains the request methods for both the list and images, as well as the logic for the cache on disk, my focus was to build for testability

### Time Spent: Approximately how long did you spend working on this project? How did you allocate your time?

I decided to work on this projects by parts and divided the work on a task, since some of the topic were new for me I spend some time researching it and seeing what best practices I could use 

1. UI/Table View recipes list 2-3hrs
2. Loading recipe list and error handling 1-2 hrs
3. Cache 1 hr
4. Testing 1hr


### Trade-offs and Decisions: Did you make any significant trade-offs in your approach?

None in particular, I decided to take my time to cover as many of the requested items as possible

### Weakest Part of the Project: What do you think is the weakest part of your project?

I would say the cache may be the weakest part since it was the piece of the project in which I had the most difficulty understanding and I wanted to learn myself instead of relying in existing libraries

### External Code and Dependencies: Did you use any external code, libraries, or dependencies?

I used online resources when I came across questions or doubts on any part of this project, specially when I worked with the cache, network manager and test suite

### Additional Information: Is there anything else we should know? Feel free to share any insights or constraints you encountered.

This was my first time using some of the these tools and I wanted to take my time to learn them and implement it in my App, this was my biggest takeaway now, that I learn how to do some of the common iOS principles as singleton, testings , JSON Decoders and more
