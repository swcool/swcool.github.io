# Membership Only

## Custome Style

### Basic (example)

  ```css
    * { font-size: 120%; color: red;}
  ```

### Hide Markview outline and buttons-container (example)

  ```css
    p {color: green;}

    #markdown-buttons-container { visibility: hidden; }

    #markdown-outline {  visibility: hidden; }
  ```

### Instruction: User can go to Inspect Element to find the item to change. 
  * Steps to find out target elements:
    1. Go to markdown page, activat markview to view.
    2. Select the item you like, right click mouse and select "Inspect Element".
    3. The Developer Tool window popup and Go to find the related CSS item.
    
  * Steps to apply changes:
    1. Select checkbox "Use Custome Style" and click "Save My Options"
    2. Enter the style you like (css) below in textarea and save.
    3. Navigate to your markdown page
    4. Click the browser action icon
    5. Hey, CSS is injected!