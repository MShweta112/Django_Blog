# Django_Blog


**Registration:**

Users can sign up for an account using Django's built-in UserCreationForm.
Login:

Users can log in using Django's built-in AuthenticationForm.
Logout:

Users can log out using Django's built-in logout functionality.
Blog Post Model:

Model Definition:
Title: CharField – The title of the blog post.
Content: TextField – The main content of the blog post.
Author: ForeignKey to User – The user who created the blog post.
Created At: DateTimeField with auto_now_add=True – The date and time when the post was created.
Updated At: DateTimeField with auto_now=True – The date and time when the post was last updated.
Status: ChoiceField – The publication status of the post, with choices including 'Draft' and 'Published'.
Views and Templates:

**List All Blog Posts:**

View: Create a view to list all blog posts.
Template: Design a template to display the list of posts.
Create a New Blog Post:

View: Implement a view to handle the creation of new blog posts.
Template: Design a template with a form for creating new posts.
Update an Existing Blog Post:

View: Implement a view to update existing blog posts.
Template: Design a template with a form to edit an existing post.
Delete a Blog Post:

View: Implement a view to delete a blog post.
Template: Design a template for confirming the deletion of a post.

Overview:
The blog website allows users to register, log in, and log out. It includes functionality for managing blog posts, with features for creating, listing, updating, and deleting posts, as well as handling user authentication and authorization

