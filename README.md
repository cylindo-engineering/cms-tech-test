The goal is to create an image viewer in which you can easily browse through frames showing different angles of a furniture.
For reference you can see a viewer [here](https://www.cylindo.com/solutions/360-product-viewer/)

_Key Features:_

- The user should be able to use drag to browse through images.
- Use the Cylindo API to fetch the images you need. Api is [here](https://learn.cylindo.com/hc/en-us/articles/360005334798-API)
  - Use customer 4404 and ARCHIBALDCHAIR
  - Ex: content.cylindo.com/api/v2/4404/products/ARCHIBALDCHAIR/frames/1/ will get you the first frame. Change to …/frames/2/ for second frame etc. (Max 32 frames).

The solution must be written in JavaScript or TypeScript using React.

## Evaluation

The main goal is to evaluate your ability to solve problems efficiently.

Things that matter:

- the code should be as simple as possible while solving the problem.
- the outcome should resemble the reference viewer on Cylindo.com (Ignore the fullscreen button and the bottom thumbnail bar.) We do not expect pixel perfection and 100% accurate colors.
- The viewer should have good performance
- We will use your solution as the basis for the technical interview, so be prepared for questions about your design and implementation decisions.

Things that does not matter:

- tests (though you are ofc welcome to write as many as you like)
- App setup, use Create react app, Gatsby, Next.js or what ever you like.
- cross browser compatability, if it works on one of the major browsers we are happy.

## Delivery

Create public git repo (github, bitbucket, gitlab your choice) and send the link to andreas@cylindo.com. Make sure to include a README.md with instruction on how to build and run your app.
