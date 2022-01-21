## Goal

Read the blogs:

* [Build a GraphQL API with Node](https://blog.jscrambler.com/build-a-graphql-api-with-node/) By Ahmed Bouchefra
* [Building a CRUD App with Vue and GraphQL](https://blog.jscrambler.com/building-a-crud-app-with-vue-and-graphql/) By Ahmed Bouchefra

reproduce the steps and improve the example web app  

## Submodules

This repo contains two submodules, one with the client and the other with the server:

```
➜  fullstack-graphql-vue git:(main) ✗ git submodule foreach 'git remote -v' | grep 'origin.*fetch'
origin  git@github.com:crguezl/client-graphql-vue-hello.git (fetch)
origin  git@github.com:crguezl/server-graphql-hello.git (fetch)
```
* [Server Repo](https://github.com/crguezl/server-graphql-hello)
* [Client Repo](https://github.com/crguezl/client-graphql-vue-hello/tree/main)

In the branch `solution` of each of those repos you will find the solution to this lab.

## TODO

* [  ] Accept the assignment
* [  ] Clone the repo:

  ```
  git clone --recurse https://github.com/ULL-ESIT-DMSI-1920/fullstack-graphql-vue-casiano-rodriguez-leon-alumnoudv5.git
  ```
*  [  ] Go to the submodule folders

  ```
  ➜  tfa-fullstack-graphql-vuejs cd fullstack-graphql-vue-casiano-rodriguez-leon-alumnoudv5
  cd client
  ➜  client git:(b8104ff) git --no-pager branch -a
* (HEAD desacoplada en b8104ff)
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
  remotes/origin/solution

## Optional Extensions

### Deploy in Heroku
  * [Deploying Node.js Apps on Heroku](https://devcenter.heroku.com/articles/deploying-nodejs)

### Add authentication
    * See [Handling authentication in your GraphQL-powered Vue app](https://blog.logrocket.com/handling-authentication-in-your-graphql-powered-vue-app/) by [Anjolaoluwa Adebayo-Oyetoro](https://blog.logrocket.com/author/anjolaoluwaadebayooyetoro/)


## References

* [Server Repo](https://github.com/crguezl/server-graphql-hello)
* [Client Repo](https://github.com/crguezl/client-graphql-vue-hello/tree/main)
* [Build a GraphQL API with Node](https://blog.jscrambler.com/build-a-graphql-api-with-node/) By Ahmed Bouchefra
* [Building a CRUD App with Vue and GraphQL](https://blog.jscrambler.com/building-a-crud-app-with-vue-and-graphql/) By Ahmed Bouchefra