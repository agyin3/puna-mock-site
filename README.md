# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

## Instructions

In this project you'll be building a mock 3 page react app. You'll find mocks of each of the pages in `public/mocks`. Feel free to reference back to them as needed and feel free to utilize any colors/fonts that you'd like to make this your own.

For this project you will be working with the **[Open Brewery API](https://www.openbrewerydb.org/documentation/)**. We will be using the `List of breweries` endpoint, so find that section, click run and familiarize yourself with the data.

### Helpful Hints

You'll want to utilize the following packages

-   axios
-   react-router-dom
-   styled-components

**React**

-   Try to really think about how you want to structure your components
    -- What components should be imported in the `<App/>`
-   Props, props, props - when in doubt following the chain of command of your prop drilling
-   `useState` and `useEffect` will be helpful. Try to keep it simple but effective with their usage

**Styled Components**

-   Brushing up on some basic CSS could be helpful, `flexbox` especially will make things easier as you start to work with spacing.

-   Setup a theme file that can hold your common styles (fonts, colors, spacing, etc.) and setup your project to be able to utilize it

-   Where possible try to make common reusable components and then custom those as needed but don't force it

**Axios**

-   Can utilize `trycatch` or `chaining` to handle this. For now, if we do catch an errors we just want to log them to the console

**React Router Dom**

-   Remember you can name your routes anything you'd like but if you're having trouble I'd reccomend
    -- `/`
    -- `/breweries`
    -- `/breweries/:id`

-   How might we want to utilize `useParams` to help us achieve our goals

## Final Thoughts

Remember this project is just meant help you continue learning react. Refer back to past projects we have done to see if there is anything you can reference. Taking the time to plan before just jumoing into the code could save you time debugging later but take any approach that works best for you. There is no one right way to do this project so just keep the endgoal in mind of making this functional.
