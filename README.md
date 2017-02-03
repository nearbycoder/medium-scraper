# medium-scraper

### Installing
```
npm install medium-scraper
```

## Getting Started
medium-scrapper allows for you to scrape latests article from a user

### Example
```javascript
  scraper = require('medium-scraper');

  var medium = {user: '@nearbycoder'}

  scraper.getPosts(medium).then(function(results) {
    console.log(results)
  })
```

### Results
```json
[  
   {  
      "title":"We’re Presenting at Tulsa TechFest",
      "time":"Jul 22, 2016",
      "image":"https://cdn-images-1.medium.com/max/900/0*ZFgMpOUO0KV0KXuL.jpg",
      "url":"https://medium.com/made-by-munsters/were-presenting-at-tulsa-techfest-682efde980d9"
   },
   {  
      "title":"Ruby Remote Conf Recap",
      "time":"Jul 1, 2016",
      "image":"https://cdn-images-1.medium.com/max/900/0*qOVLWAPfZPY6bNcF.png",
      "url":"https://medium.com/made-by-munsters/ruby-remote-conf-recap-c87f00c05db2"
   },
   {  
      "title":"Getting Around API Rate Limiting",
      "time":"May 19, 2016",
      "image":null,
      "url":"https://medium.com/made-by-munsters/getting-around-api-rate-limiting-642b7790b225"
   },
   {  
      "title":"Welcome Back TulsaJS",
      "time":"May 11, 2016",
      "image":null,
      "url":"https://medium.com/made-by-munsters/welcome-back-tulsajs-cd73fec008ac"
   },
   {  
      "title":"Writing Angular with Webpack and es6",
      "time":"Apr 14, 2016",
      "image":null,
      "url":"https://medium.com/made-by-munsters/writing-angular-with-webpack-and-es6-e84cc668f827"
   },
   {  
      "title":"Authorizing Trello Integration with Angular",
      "time":"Apr 5, 2016",
      "image":null,
      "url":"https://medium.com/made-by-munsters/authorizing-trello-integration-with-angular-13eb6b85de88"
   },
   {  
      "title":"Commit with Intent",
      "time":"Mar 15, 2016",
      "image":null,
      "url":"https://medium.com/made-by-munsters/commit-with-intent-b0bb67bea50a"
   },
   {  
      "title":"How I learned failure as a developer",
      "time":"Jan 12, 2016",
      "image":null,
      "url":"https://medium.com/@nearbycoder/how-i-learned-failure-as-a-developer-94429e4a971c"
   }
]
```
