# Recharge - personal reflection
![the boys](images/theboys.png)
*The boys - from left to right: Dennis Wegereef,  Me,  Tim Ruiterkamp - can we conclude from these images that backend developers are happier than frontend developers? :thinking-face:*

---

## Learning goals
Legend, goals met according to myself:   

| Icon | Definition |
|------|------------|
|✔️| Succeeded |
|🔸| Partially succeeded |
|❌| Failed |


- **Web app from scratch**
    - Give user feedback at the right moment ✔️
        - Microinteractions ✔️
        - Showing sate ✔️
        - Empty states ✔️


- **Performance matters**
    - Application works (partially) offline and thus gives an 'instant' feeling to the user 🔸
        - Writing a serviceworker 🔸


- **Web design**
    - Utilizing the exclusive design principles 🔸
        - Right contrast, accessible to all users ✔️


- **Real Time Web**
    - Real time connections and multi-user support ✔️
        - When status updates notify users and other stakeholders ✔️

---

## Personal process
I had a difficult time combining the personal learning goals I initially set with the development of this project.
We were all mostly focussed on making a solid working prototype that fit the design challenge rather than trying to put in extra functionality based on the learning goals.

When I was working on an aspect of the product, someone would step in and start working on the aspects that I described in my personal learning goals. Most of the real-time connections were coded by Tim, and because of a lack of time most of the offline support was handled by a plugin called @nuxt/pwa. We did have to figure out how it worked and we edited the files it came with a little bit, but it still doesn't really feel like it classifies as checking off a personal learning goal.   
I also didn't personally really implement the exclusive design principles per sé. This product isn't meant to be designed specifically for one user. It isn't really fitting to add in nonsense either.    
In this way, the scope of the case and the focus on creating a fitting prototype got in the way of my intially set learning goals. I do feel like a lot of the things I learned in this minor have been implemented in this project.

I'll sum up some things I *do* feel I've learned more about.
- Code structure
- Documentation
- User experience design
- Component based projects
- GraphQL
- Team-based work with github
- Real time connections

### Code structure
I feel like the structure of my code files has improved massively: keeping a clear distinction between different parts of a product, putting components in their own little encapsulated file.
Also, the code itself improved. I feel like I'm thinking more about the readability in my code and deliberatly choosing between ways of writing functionality.
I try to keep my functions shorter and more clear. My naming of functions has also improved, I feel.

### Documentation
When writing the [design rational](https://github.com/timruiterkamp/laadpalen-app/blob/master/README.md) I tried to keep checking if there was enough context for the user to understand what was going on. I tried to refer back to previously made points.

### Component based projects
I've worked with vue before, but usually I end up in a weird combination of components intertwined in eachother without much consistency or a clear overview of what functionality is where.
In this project, we focussed heavily on making each component as encapsulated as possible in order to uphold maintainability.

### GraphQL
I wasn't planning to, but one day Tim wasn't able to come in to work alongside Dennis and me. I had to implement a feature that would update issues and also had to update charging stations in the database.
Since Tim couldn't be around, I had to implement some changes to the API and database myself. I added the full functionality of the charging stations in the database, and some additions to the update resolver of Issues.
I've never had any experience with typescript or GraphQL, but since Tim setup his codebase so well-structured, I was able to figure out how to add these additions, without having to watch hours of footage on how to deal with GraphQL and Mongoose.

### Team-based work on github
I've worked on projects with multiple contributors in the past, although usually the contributors wouldn't work and push changes at the same time. We were with three people, working alongside eachother at the same time.
We didn't have to coordinate alot, because we started thinking about how to tackle this beforehand.
We made sure to work component based, and on a branch for each specific feature. We pulled updates from the master first, merged the master in our own branches, resolved conflicts and merged our branch back into the master. Then we would push the master.
Because of this, we've had very little merge conflicts, giving us more time to implement features instead of working to resolve conflicts.

### Realtime connections
Altough I didn't write all the code for the WebSocket connections, it was really refreshing to find a good use case for WebSockets. It was also really fun to make the data being send as small as possible, and update multiple parts of a page based on one real-time data update.

---

## Teamwork
I've had a really good experience working with Tim and Dennis. They are both very skilled people, with strong opinions. This helps, because we had discussions about how to implement features, parts of the concept and more. In the product are ideas from everyone. It resulted in a few heated moments, sure, but we would calm down quickly and were very willing to listen to eachoters arguments.    
I can get a little stubborn sometimes, which can be really annoying to deal with, but Tim and Dennis handled it very well.     
We've worked almost all the available days alongside eachoter and only weren't around if we had a good reason. We communicated about most aspects of our work, and checked eachoters code and implementations as well.    
We all got really excited when we found a really smooth way to implement certain features, which kept the spirits high.

---
## Navigation
- [Recharge - repository](https://github.com/timruiterkamp/laadpalen-app)
- [Recharge - live prototype](https://denniswegereef.nl)
- [Recharge - personal product biography](product-biography.md)
