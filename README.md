# A-0524 Lab Day 2 - Bootstrap Website

Bootstrap Docs: [https://getbootstrap.com/docs/5.3/getting-started/introduction/]

## Instructions

- Recreate the mockup provided in the `design` directory. Use the `index.html` file.
- No custom CSS stylesheet, use only Bootstrap classes.
- Once you are done, commit and push.

## Notes

### Header

- On large screens, the search form is between the logo and the menu. On smaller screens, the order is switched and the search form is after the menu.

### Sidebar

- On large screens, the blue sidebar is on the left of the main content. On smaller screens, the sidebar goes below the main content.

### Main Content

#### Table

The table needs to be responsive. You can find the table data below:

```html
<table>
  <thead>
      <tr>
          <th>#</th>
          <th>Name</th>
          <th>Email</th>
          <th>Role</th>
          <th>Status</th>
          <th>Phone</th>
          <th>Address</th>
      </tr>
  </thead>
  <tbody>
      <tr>
          <td>1</td>
          <td>John Doe</td>
          <td>john.doe@example.com</td>
          <td>Administrator</td>
          <td>Active</td>
          <td>(123) 456-7890</td>
          <td>1234 Elm St, Springfield</td>
      </tr>
      <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>jane.smith@example.com</td>
          <td>Editor</td>
          <td>Active</td>
          <td>(234) 567-8901</td>
          <td>5678 Oak St, Metropolis</td>
      </tr>
      <tr>
          <td>3</td>
          <td>Samuel Johnson</td>
          <td>samuel.johnson@example.com</td>
          <td>Subscriber</td>
          <td>Inactive</td>
          <td>(345) 678-9012</td>
          <td>9101 Pine St, Gotham</td>
      </tr>
      <tr>
          <td>4</td>
          <td>Lisa Wong</td>
          <td>lisa.wong@example.com</td>
          <td>Contributor</td>
          <td>Active</td>
          <td>(456) 789-0123</td>
          <td>1121 Maple St, Star City</td>
      </tr>
  </tbody>
</table>
```

#### Login Form

The two labels are floating labels. When you click on the input field, the label will float to the top part of the input.
