# Adding Navigation to React App
We all know we need to nevigate on different web pages to get different informations (Home / About / Contact-us etc.) <br>
But sometimes this can be tedious because it may require refresing page which may involves loading new as well as old contents. <br>
React Router is an API for React Applications allows us to build a single-page web application with navigation without the page refreshing as the user navigates. <br>

## Acceptance Criteria:
- [ ] Create React Application and add Navigation feature to it.
- [ ] There will be two components **App** and **LocationDisplay**. Put all your components in App.js and export them. Make **App** as default export.
- [ ] 'App' is your compelete Application.
- [ ] 'LocationDisplay' should display your current location pathname in DOM. Like if user on route '/' should be see **"/"(without quotes)** on screen or Like any route '/any-route' should see able to **"/any-route" (without quotes)**. *Hint:* useLocation()
- [ ] there will two routes '/' and '/about'
- [ ] default route will be '/' (home page)
- [ ] on '/' should able to see **You are home**. Note: other contents can be there but this must.
- [ ] on '/about' should able to see **You are on the about page**. Note: other contents can be there but this must.
- [ ] By clicking on About able to go to '/about'
- [ ] By clicking on Home able to got '/'
- [ ] If user go to some random url, display 'No match' on screen.
- [ ] user should be able to go back and forth.
