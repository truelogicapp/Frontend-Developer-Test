# Frontend Developer Test

Create an application frontend based on provided layout.

All elements of the shared layout should be functional, it's up to you how they will work at the end.

Usage of GIT is required. **Create a repository for this task, solution for each STEP should be in a separate branch in your repository**

### Considerations

- The documentation starting on the README.md file need to be clear
- We want to see not only the solution but also how you think and your working process, so please keep all your commits accessible and use proper naming standard for them
- All steps are required so do not skip any. If you don't know, or don't feel comfortable with the required technology, just try your best and commit what you can

### Layout

You can find layout of a page in `/layout` catalog. 

We share only mobile view, its up to you if you will provide desktop but it's not required


### STEP 1 

Transform `/layout` to html using sass / es6 / npm / webpack 

for this step please use pure JavaScript or jQuery.

### STEP 2

Data displayed on the website should be loaded from .json files.

Create .json files, structure is up to you. Put some random data in it and load it into the page using ajax calls

Required data:
- main product data (image URL, title, price, available sizes, colors description)
- see more products (products image URLs)

Consider those files to be your API, feel free to put them online to be able to do proper calls.

### STEP 3

Please use React. 

Each element should be a separate component.


### STEP 4

Test all the things. We are going to focus on functional tests. We can use MochaJs or whatever else tool, but we need to be able to run all the tests headless from the command line. You can use docker for all the dependencies.


### STEP 5 (BONUS)

- We like PWA, use it if you can
- Use loading shimmer ([article](https://medium.com/@dhilipkmr/the-loading-shimmer-f7129ac41894))
- Add at least 1 micro-interaction ([article](https://uxplanet.org/creating-meaningful-micro-interactions-99cbde1fbee7))
- Add additional pages, maybe some landing page or product list page

### Deployment

We would like to see application online. Deploy it wherever you feel comfortable. 

We like AWS and GCP but Netlify, Heroku, Digital Ocean or whatever suits you will be also fine.


### Wrapping up

In the README file, we should be able to find all the information necessary to run the project, the different challenges, and the test. Documentation is highly important for the resolution of this test.


### Delivery

If your repository is private, please share it with r.katyal@gmg.com.
