# FrontEndDev_Assignment15.3
### Assignment 15.3 of the AcadGild Front End Web Dev Course

● Create a service, which will store an object of task in your current component  
 and then make a link on the same view and when the user clicks,  
  it should go to the next page and show that task object data in view.  
  
<u><b>Notes:
 1. Angular CLI is used to create app. So, use `ng serve` to run on localhost:4200
 2. Used the Todo List example created by `https://github.com/resolvethis/ng2-todo`
 3. Added an edit todo component
 4. Modified the todo item component, so that user can check off item as completed and NOT archive it  
    and conversely, can archive it without completing it
 5. Modified the service method removeItem to accomodate the completed flag
    Also, added a getItem by id for the EditComponent
 6. For this assignment the EditComponent doesn't actually let user change anything, just view it
 7. Also, modified the todo list so that each todo task has an `<a>` tag to take user to view the selected todo item
 8. Code structure:
       * app-root
       * todo-page, archive-page
       * todo-page:
       * new-todo, todo-list
       * todo-item, edit-todo
       * archive-page:
       * archive-list, edit-todo 
       