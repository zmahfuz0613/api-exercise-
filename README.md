# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  SOFTWARE ENGINEERING IMMERSIVE

# Build a Blog JSON API

Your task is to build a blog json api using MongoDB, Mongoose, and Express.

Your app should include the following:

- CRUD routes (ability to create, read, update, and delete blog posts)
- a seed file to create seed data in your database

Test all routes in Postman.

Here is the schema:

```
const Post = new Schema(
  {
    title: { type: String, required: true },
    imgURL: { type: String, required: true },
    content: { type: String, required: true },
    author: { type: String, required: true },
  },
  { timestamps: true }
)
```

Pull Request when done.

Deploy your app to MongoDB Atlas and Heroku.
> include the heroku deployment URL in your Pull Request description
