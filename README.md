# Blog project Server

Hello, if you've reached this repo, looking for the blog backend, you're the best. 
Here, i'll create all the blog backend flow , and step-by-step, understand how the backend works.

My goals for it is : 

- Create the sign up flow 
  - Create new account flow
  - Create reset password flow
  - Create login flow
- Create the posts CRUD
  - The user can create a new post
  - The user and the admin can delete a post
  - The user and the admin can edit a post
  - The admin can make the post "private"
- Create the Update profile flow
  - The user can update the profile picture
  - The user can change the email
  - The user can change the password
- Create the comments flow
  - Any user can comment in a post
  - The comment must have :
    - The user pic
    - The user name
    - The Date/time
- Create the like/dislike comment flow
  - Every post will have the like/dislike counter
  - Every user can just hit ONE button once. If the like is clicked, the dislike is not. The user can change this state.
- Create the favorite flow
  - The user can favorite any post, and save it in the favorite section. 
  - The favorite section is always available, since the user has at least one post favorited.
- Create the recursive comments flow.
  - The users can comment in other comments, and create a recursive conversation.

## Tech that will be used 
To create this , i'll use :
- Node,
- Typescript
- TypeOrm / Prisma


## NOTE
This is a backend playground, that i'm creating this to learn backend. This code can be VERY VERY messy, but it will be refactored and updated since i learn how to do it. 
PR's and issues will not merged, until i learn how it works, once this repo is to LEARN and not to create a product.