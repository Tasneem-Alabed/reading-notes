# View Components

View components are similar to partial views, but they're much more powerful. View components don't use model binding, they depend on the data passed when calling the view component
A view component:

- Renders a chunk rather than a whole response.
- Includes the same separation-of-concerns and testability benefits found between a controller and view.
- Can have parameters and business logic.
- Is typically invoked from a layout page.

  View components include the same separation-of-concerns and testability benefits found between a controller and view. You can think of a view component as a mini-controller—it’s responsible for rendering a chunk rather than a whole response. You can use view components to solve any problem that you feel is too complex with a partial.
  
