# Postify UI

## Objective
Create a UI for managing posts where users can create new posts and view all existing posts. Each post should have a userId, id, title, and body. Posts should be saved in a list in local storage. Additionally, provide functionality to delete posts and ensure the UI is responsive for both small and big screens.

## Features
1. **Create Post:**
   - Users can create a new post by providing a userId, title, and body.
   - Posts are saved in a list in local storage.

2. **View All Posts:**
   - Display all existing posts on a dedicated page.

3. **Delete Post:**
   - Each post should have a delete button for removing it from the list.
   - Deleting a post updates the list in local storage.

4. **Responsive Design:**
   - The UI should be responsive, providing a seamless experience on both small and big screens.

## Implementation Details
### Create Post Form
- Create a form component allowing users to input userId, title, and body.
- Handle form submission to save the post in local storage.

### View All Posts Page
- Display a list of all posts fetched from local storage.
- Implement a delete button for each post to allow users to remove them from the list.

### Responsive Design
- Utilize CSS media queries to adjust the layout and styling based on screen size.
- Ensure the UI elements are easily accessible and readable on both small and big screens.

## Technologies Used
- React.js for building the user interface.
- Local storage API for storing and retrieving posts.
- Bootstrap for styling [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## Next Steps
- Implement comment for post [create, edit, delete]
- Implement user for posts [create, edit, delete]
