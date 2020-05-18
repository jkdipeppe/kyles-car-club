# kyles-car-club
Static site for my car club

# How to run the site
 - check out the master branch
 - cd static
 - npm install
 - npm start
 - app should be viewable locally at localhost:3000

 # Heroku deployment
  - git subtree push --prefix static heroku master


# Status
Implemented design and most components for desktop viewing.
Finishing up FAQ  design improvements and Apply Page/Linking
Next steps:
    - add media queries for semantic tablet and mobiel views
    - move images to an S3 bucket
    - Refactor pages with repeated Grid/Columns/Rows (ex. The Cars) to easily add new cards.
    - Add database to handle 'applications'
    - Implement a car booking system for members