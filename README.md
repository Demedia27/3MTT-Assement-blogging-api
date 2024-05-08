Welcome to Abel Udoh's Blogging API

Thank you for choosing the Blogging API for your content management needs. Our API provides a simple and efficient way to create, manage, and publish blogs. Below is a guide to get you started:

Getting Started

Welcome Message: When you visit the root URL of our API (https://abeludoh-blogging-api.onrender.com), you'll receive a friendly welcome message confirming that the API is up and running.

User Authentication

Sign Up: To create a new account, send a POST request to https://abeludoh-blogging-api.onrender.com/users/signup with your first name, last name, email, and password in the request body. You'll receive a message in response if the sign-up is successful.

Sign In: To sign in to your account, send a POST request to https://abeludoh-blogging-api.onrender.com/users/signin with your email and password in the request body. You'll receive a token in response if the sign-in is successful.

Blog Management

Create a Blog: To create a new blog post, send a POST request to https://abeludoh-blogging-api.onrender.com/blogs with your blog content in the request body. Include the token received during sign-in in the Authorization header as a Bearer token.

Update a Blog: To update an existing blog post, send a PUT request to https://abeludoh-blogging-api.onrender.com/blogs/:id with the blog ID in the URL and the updated content in the request body. Include the token in the Authorization header.

Delete a Blog: To delete a blog post, send a DELETE request to https://abeludoh-blogging-api.onrender.com/blogs/:id with the blog ID in the URL. Include the token in the Authorization header.

Additional Features

List Blogs: To get a list of published blogs, send a GET request to https://abeludoh-blogging-api.onrender.com/blogs. You can paginate, filter, and order the results using query parameters.

Get a Blog: To retrieve a specific blog post, send a GET request to https://abeludoh-blogging-api.onrender.com/blogs/:id with the blog ID in the URL. The API will return the blog details and update the read count.

I hope this guide helps you get started with the Blogging API. If you have any questions or need assistance, please don't hesitate to reach out to our support team. Happy blogging!