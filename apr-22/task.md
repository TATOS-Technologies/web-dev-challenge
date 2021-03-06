# Task for Full-stack Developer

## Summary
Your task is to create a **personal blogging site** with ability for users to comment and a **public facing API** for external apps to fetch data.  
Only admin has the ability to post blogs. The blog content should have RichText support.  
Admin should be provided with a richtext editor.
Readers will be able to comment and like the articles posted.  
The public API for external apps should support the following:
- authenticate a reader (for likes and comments)
- fetching a list of blogs items
- fetching a single blog item (including comments)
- like a blog 
- post comments
- fetch comments by a user
- fetch list of liked articles

## Details
Create a repository **on your personal github account**. Commit all your work to that repository.  
Host the project on a platform of your choice for demo.  
**Code review will be done.**  
Please add clear and concise commit messages to your commits.  
**Provide documentation** / usage information for all APIs in the backend.
Optionally, provide a brief documentation regarding the frontend.  

### Frontend
For the frontend, you can follow a basic blogging site layout.  
Make sure you have the following checked:
- A landing page listing blog articles
- A page where you can read a blog item
- Option for readers to login ( just for posting comments )
- **Comments** section for readers 
- An **admin page** where you can login to create, edit and delete blogs

### Backend 
For the backend, we have the following requirements
- Use a **noSQL** database
- Use **node.js** with framework of your choice (prefer nest.js)
- Create APIs for basic blogging CRUD for the admin
- APIs for the blog frontend (listing, readig blogs,likes and comments)
- public facing API for integration with a mobile app (same functionality as the blog webpage)
- Search for articles  
- Categories for articles  
- APIs to handle media upload(for embedding media within blogs).

The blog content should be HTML (for Richtext support). 

## git
Please work on seperate branches for major features. This is crucial for code review.

## Timeline and reporting
You have 5 days (working days) for completing this task.  
There will be daily stand-ups for progress reporting. You will be required to report your days progress.  
Tasks will be tracked via [Clickup](https://app.clickup.com/).  





Please feel free to reach out in case of any doubts.

All the best.