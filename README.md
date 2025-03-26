## WhammyTech Technical Assignment

### Introduction
This assignment helps us better understand your ability to solve problems and fulfil task requirements with technical solutions. We would like to get an impression of how you write code in the real world. We will be evaluating your communication skills, development capabilities, and your interpretation of what good, clean, production-ready code should look like.

### Scenario
Cinema operators such as Cathay are one of the most popular merchants. We want to build an app to help our users discover movies easily.

### Requirements
Create a standalone movie app / mobile web(responsive UI) with the following screens:

### **Home screen with list of available movies**

- Ordered by release date (default), alphabetical, rating - can use dropdown
- Pull to refresh
- Load when scrolled to bottom
- Each movie to include:
    - Poster/Backdrop image
    - Title
    - Popularity

### **Detail screen**
Movie details should have the following:
- Synopsis
- Genres
- Language
- Duration
- Book the movie (simulate opening of this [link](https://www.cathaycineplexes.com.sg/) in a web view)

### **Frontend Design**
It is up to you to design the UI. Simple is good.

### **Backend**
Use the API from [TMDb](https://developers.themoviedb.org/3/getting-started/introduction) as your data source.

You can use our API Key: `328c283cd27bd1877d9080ccb1604c91`

### **Senior requirement**
- Account system (Login with google, facebook)
- Favorite movies feature
- Inifinite loading in list screen 

**Sample requests:**

Listing

```
http://api.themoviedb.org/3/discover/movie?api_key=328c283cd27bd1877d9080ccb1604c91&primary_release_date.lte=2016-12-31&sort_by=release_date.desc&page=1
```

Detail

```
http://api.themoviedb.org/3/movie/328111?api_key=328c283cd27bd1877d9080ccb1604c91
```

### Technical requirements:

| Web |
| ----------- |
| React based framework (ReactJS, create-react-app, etc) |
| CSS or SASS |
| Use context API & hooks (for React) |
| Use correct routes, param & URL (navigation required) |
| Knowledge & experience using typescript is a must |

We expect unit tests for the main functionalities only.
You can use third party libraries.

## AI Prompts / Tools Used
Please describe how you used AI in this project (if any):

- **Tool used**: ChatGPT / Copilot / Cursor
- **Prompt example**:
  > “Build a Next.js component that fetches movies from TMDb and supports infinite scrolling using React hooks.”

- **Which part AI helped you the most?**
  > Helped generate base layout, setup fetch logic, and design responsive card grid.

- **Any AI-generated code that you modified?**
  > Yes. Cleaned up code structure, added error handling, and typed API responses manually.

## Time Taken
> Total time spent: ~1.5 hours

### Code Repo
Please use this repo for your commits.

## Evaluation Criteria
- Clean, readable, maintainable, and performant code
- Clear documentation that describe your assumptions and design considerations, you can use the wiki in this repo. Don't know how to create wiki? [Create one](https://docs.github.com/en/github/building-a-strong-community/adding-or-editing-wiki-pages)
- Unit Tests will be evaluated
- Deployment is required with senior developer position
- Document about starting application locally and deployment instruction

That’s the end of the assignment, we hope you have fun!
Looking forward to your submission.
