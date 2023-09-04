# Header Component

The **Business Card Component** is a simple and customizable way to display 
business card information within your `fastn` pacakge. With just a few lines of 
code, you can showcase your contact details, company information, even 
include a logo and others.

## Preview

Here's an example of how the Business Card Component might look when rendered:

### Header

![header.png](.github/assets/header.png)



## Getting Started

To use the Business Card Component in your `fastn` package, follow these steps:

1. **Add the Business Card Dependency**: Open your `FASTN.ftd` file and add 
   the following line to include the Business Card component:
   ```ftd
   -- fastn.dependency: __user_name__.github.io/__repo_name__
   ```
2. **Use the Business Card Component**: In the file where you want to add 
   the business card (e.g., `index.ftd`), you can import the component and 
   use it like this:
    ```ftd
   -- import: __user_name__.github.io/__repo_name__ as header

   -- header.header: My Site
   site-logo: $assets.files.images.ipsum-logo.svg
   site-url: /
   
   -- ftd.text: Hello
   
   -- end: header.header
   ```
   
## Customization

Feel free to customize the business card by adding, removing, or modifying 
fields.

## Fields

Feel free to reach out if you have any questions or need further assistance. Happy coding!
