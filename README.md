# InnovationStack
Build a qualitative research tool for structuring the innovation process. Currently we are only targeting one user (professor Dr. Paul Fearis from Design Health at Duke) with one use case (web app). We aim to achieve minimum utility for usability. Two key features are on our plate:
1. process handwritten notes in the Operating Room from into a digital format 
- timestamp : observation
- slack-style user input i.e. a trigger to generate new timestamp or previous timestamp + one min etc.
2. video with note-taking capacity

Link to Team Working Github: https://github.com/innovation-stack-engineering

Asset: any object 
- a note, an imported video are separate assets
- video, a note created and paired with the video (data structure?)
Timer notes: auto-log time during live recording 

Two-tier note hierarchy
- similar to bullet points / google comments

Currently export to csv
- in the future: store in database, generate visualization and insights

Technologies
- Database: MongoDB
- Frontend: React, Node, npm
- API development collaboration and testing: Postman
- Cloud storage (free): Heroku, switching to AWS S3
- Git: main (rarely touch), testing branch, feature branches; archive for storing features (on the frontend)
remote server
git clone <repo>
git checkout -b <branch>
git add <reactComponent.js>
git commit -m "Here's what I did"
git push
from <Branch> -> testing //merge branch to testing
- Project workflow: Trello (follows Scrum protocols)


