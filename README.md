# Angular Todo App with Routing Feature

Successfully created my first Angular JS app

- visit https://sunilale0.github.io/angular-todo-and-routing/ for live deployment

## Features:

- add todo
- update todo
- delete todo
- check console to if the features are working. I am using https://jsonplaceholder.typicode.com/todos, so some features don't work for new user inputs

### How to deploy angualar Application to github:

- Step 1: `ng build --prod --output-path docs --base-href /<project_name>/`
- Step 2: make a copy of `docs/index.html` and name it `404.html`. save it in the same folder `docs/` so it has both files `index.html` and `404.html`

_Here is the link to the guide: https://angular.io/guide/deployment#deploy-to-github-pages_

There is Angular-cli-ghpages that can automatically do all of these for you. It creates another branch called `gh-pages` like by `react-gh-pages`. Set `gh-pages` as the source folder to deploy.
_here is the link: https://github.com/angular-schule/angular-cli-ghpages_
