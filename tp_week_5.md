<style>
    html {
        background-color: lightsalmon;
    }
    alternate {
        color: white;
        animation-duration: 5s;
        animation-name: Async;
        animation-direction: alternate;
        animation-iteration-count: infinite;
    }    
    @keyframes Async {
        from {
            color: black;
        }
        to {
            color: grey;
        }
    }
    grey {
        color: grey;
    }
</style>

### <alternate>What is <grey>RESTful</grey> API?</alternate>

REST: Representational State Transfer

- Get routes in a descriptive way
- The verbs like PUT, POST, PATCH and DELETE will tell you what you want to do

#### What we will be building

- Store code snippets and seperate them by language
- id, author, code, title, description, language, comments, favorites
- endpoints
  - Snippets
    - Create: <b>POST</b> (to all of the) /snippets
    - Read all: <b>GET</b> /snippets
    - Read one: <b>GET</b> /snippets/:id
    - Update: <b>PATCH</b> /snippets/:id
    - Delete: <b>DELETE</b> /snippets/:id

#### Pitch: SilentNews

- Social Media based on local News

  - Third party api's we would need:
    - News API for the news feed
    - Maps API for the location and distance
    - Crime API
  - My target users college age students from 18 to 30 years
  - Competitors:
    - local news - ex: latimes
    - Social media - twitter
  - Possible roadblocks:
    - UX - Website Navigation
    - Budget
    - Loading times
    - Outreach

- Collect data:

  - Sign-ups
  - Question prompts
  - Heat maps

- It has the ability to comment on the news
- You can read the news but you can't comment on it if you don't live in the city or have an account
