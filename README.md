# Weston's Full Stack Web Development Resources
A repo to keep track of resources I pick up while learning Full Stack Web Development. Use to improve the quality of your brain. 

★ = Essential/Suggested

### General
+ Web Programming Patterns
  + [Dependency Injection](https://en.wikipedia.org/wiki/Dependency_injection)

### Reference
+ [Mozilla Developer Network](https://developer.mozilla.org/en-US/)

### Course Sites
Sites with structured courses and/or guides for learning web dev.
+ [Bento](http://www.bentobox.io) - Guides for web development 
+ [Udacity](https://www.udacity.com/) - Programming courses

### Core Web Concepts
Core concepts on what everything below this is built on.
+ HTTP
  + Tutorials
    + [HTTP Made Really Easy](http://www.jmarshall.com/easy/http/)
  + Questions
    + [Difference between "Cache-Control: max-age=0" and "Cache-Control: no-cache"](http://stackoverflow.com/questions/1046966/whats-the-difference-between-cache-control-max-age-0-and-no-cache)
+ HTML5
  + Books
    + [Dive Into HTML5](http://diveintohtml5.info/index.html)
  + Local Storage
    + [THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS](http://diveintohtml5.info/storage.html)
  + IndexedDB
    + [Difference between Local Storage and IndexedDB](http://programmers.stackexchange.com/questions/219953/how-is-localstorage-different-from-indexeddb)
  + Web Sockets
    + [MDN - Web Sockets](https://developer.mozilla.org/en-US/docs/WebSockets)
+ [Web Components](http://webcomponents.org/)

### Workflow/Deployment
+ ★ [Bower](http://bower.io/) - Front-end dependency management
  + [How to find available versions of package](http://stackoverflow.com/questions/21242143/how-to-find-available-versions-for-a-bower-dependency)
+ ★ Gulp
  + [Gulp + Browserify: The Everything Post](http://viget.com/extend/gulp-browserify-starter-faq)
+ [Deploying a MEAN stack app to Heroku](http://www.tilcode.com/deploying-a-mean-stack-app-to-heroku/)

### Dev Environment
+ Terminal
  + [iTerm2](https://www.iterm2.com/) - Terminal replacement for OSX
    + Themes
      + [Giant ZIP of Themes](http://iterm2colorschemes.com/) (Favorites: Flatland)
  + [Improve Mac OSX Terminal Experience](http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/)
+ Text Editors
  + ★ [Sublime Text 3](http://www.sublimetext.com/3) 
    + Themes
    + Plugins
      + ★ [Package Control](https://packagecontrol.io/) - Package manager for Sublime 
      + [Sublime Linter](https://packagecontrol.io/packages/SublimeLinter) - Linting (required additional plugins for each linter (e.g. JSHint)
      + [Bracket Highlighter](https://github.com/facelessuser/BracketHighlighter) - Highlight matching brackets, quotations, etc.
  + [Atom by Github](https://atom.io/)
+ [Spectacle Window Manager for OSX](http://spectacleapp.com/)

### Client-Side
#### HTML
#### CSS
+ General
  + Style Guides
    + [Trello CSS Style Guide](https://gist.github.com/bobbygrace/9e961e8982f42eb91b80)

#### Javascript
+ General
  + [MDN Javascript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Introduction)
  + [PlainJS](https://plainjs.com/javascript/events/) - Helpful tips for writing plain javascript
  + New Features
    + ES6
    + ES7
      + [Async/Await](https://github.com/lukehoban/ecmascript-asyncawait) - Async programming in a synchronous fashion
+ Various *need to be sorted*
  + [Eloquent Javascript Chapter 10: Modules](http://eloquentjavascript.net/10_modules.html)
  + [Overwhelmed by Javascript Dependencies](http://blog.startifact.com/posts/overwhelmed-by-javascript-dependencies.html)
+ Books
  + [You Don't Know JS Series](https://github.com/getify/You-Dont-Know-JS)
+ Frameworks
  + AngularJS
    + [Angular 1.x](https://angularjs.org/)
      + General
        + [A Different Approach to Angular Nav Menus](https://ryankaskel.com/blog/2013/05/27/a-different-approach-to-angularjs-navigation-menus)
        + [Save form values on view chnage](http://stackoverflow.com/questions/12940974/maintain-model-of-scope-when-changing-between-views-in-angularjs)
        + [Binding to Directive Controllers - Using isolate scope and controllerAs](http://blog.thoughtram.io/angularjs/2015/01/02/exploring-angular-1.3-bindToController.html)
        +  + [Redirection example](http://stackoverflow.com/questions/27212182/angularjs-ui-router-how-to-redirect-to-login-page) - [Plunker](http://plnkr.co/edit/3kImqU?p=preview)
      + Questions
        + [Difference between '@' and '=' in directives](http://stackoverflow.com/questions/14050195/what-is-the-difference-between-and-in-directive-scope)
      + Dependency Injection
        + [Diving Deep with Dependency Injection](http://www.ng-newsletter.com/posts/deep-dive-in-angular-dependency-injection.html)
      + Architecture
        + ★ [John Papa's Style Guide](https://github.com/johnpapa/angular-styleguide)
        + [13 Step Guide to Angular Modularization](https://blog.safaribooksonline.com/2014/03/27/13-step-guide-angularjs-modularization/)
      + Plugins
        + ★ ui-router
        + ★ [Smart Table](http://lorenzofox3.github.io/smart-table-website/) - Great table directive
    + [Angular 2.x](https://angular.io/)
    + [Giant List of Angular Resources](https://github.com/jmcunningham/AngularJS-Learning)
    + [Zeef Angular Page](https://angularjs.zeef.com/gianluca.arbezzano)
  + Aurelia
    + General
      + [Article on IoC and Dependency Injection in Aurelia](https://gist.github.com/jdanyow/f54bd89d755af8f78720)
      + [Patrick Walters Best Practices for Aurelia - Application Structure](http://patrickwalters.net/my-best-practices-for-aurelia-application-structure/)
      + [Patrick Walters Best Practices in Aurelia - Passing and Sharing State](http://patrickwalters.net/my-best-practices-in-aurelia/)
      + [Creating your first Aurelia app: From authentication to calling an API](https://auth0.com/blog/2015/08/05/creating-your-first-aurelia-app-from-authentication-to-calling-an-api/)
  + Ember
  + Backbone
    + Beginner
      + [A complete guide for learning Backbone](http://codebeerstartups.com/2012/12/a-complete-guide-for-learning-backbone-js/)
  
### Server-Side
#### Node.js
  + Packages
    + Mongoose - MongoDB thing (rest of description TBD)
      + [Helpful article on `populate`](https://alexanderzeitler.com/articles/mongoose-referencing-schema-in-properties-and-arrays/)
  + [Stack Overflow - Learning Express for Node.js](http://stackoverflow.com/questions/8144214/learning-express-for-node-js)
#### Databases
  + MongoDB
    + [MongoDB Shell Quick Reference](http://docs.mongodb.org/manual/reference/mongo-shell/)
      + **Start Shell** `mongo`
      + **Use Database** `use [database name]`
      + 

### Various (need to be sorted)
+ [JSBin](http://jsbin.com/) - Web app for mocking up examples with HTML/CSS/JS.
+ [Github Markdown Guide](https://guides.github.com/features/mastering-markdown/) - Useful for writing ReadMe's, documentation, etc.
