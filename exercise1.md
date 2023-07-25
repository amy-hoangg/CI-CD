Some common steps in a CI setup include linting, testing, and building. 
CI: merge the developer changes to the main branches often.
steps happen in CI:
- lint: to keep the code clean and maintainable
- build: put all parts of the code together ito runable software bundle. For example: if you've written your application in typescript, and you intend to run it on node, then the build step  might be transpiling the typescript into javascript
- test: to ensure we dont break existing features
- package: put it all together in an easily movable batch
- deploy: make it available to the world


What are the specific tools for taking care of these steps in the ecosystem of the language you picked? 
I chose Typescript.
lint: eslint or prettier
build: Webpack to bundle the code to Javascript
test: use the react testing library or jest
package: 
deploy: can use render or fly.io to deploy


What alternatives are there to set up the CI besides Jenkins and GitHub Actions? 
Gitlab provides a built-in CI/CD capabilities similar to Github Actions. It allows to define CI/CD pipelines within GitLab repositories

Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?
In my case, it would be better to set up CI in a cloud-based environment. Because i have small project that doesnt need any special requirements. the configuration is simple and i dont need to go to the hassle or expense of setting  up. it would be cheaper. 