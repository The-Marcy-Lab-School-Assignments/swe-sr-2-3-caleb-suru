# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

What are the main differences between Flexbox and Grid layouts? Describe scenarios where each layout system would be more suitable.

### Response 1

## Prompt 2

What is the difference between `justify-content` and `align-items` in Flexbox? How does each property control the positioning of flex items within the container?

### Response 2

## Prompt 3

Describe the difference between `grid-template-areas` and `grid-template-columns`/`grid-template-rows`. When might you prefer one approach over the other?

### Response 3

The difference between the two is that with `grid-template-columns` and `grid-template-rows` is that you have more flexibility with what you want to do over `grid-template-areas`. You might use `grid-template-areas` when you have to deal with a lot of things at once.

## Prompt 4

Explain the `min-width` and `max-width` keywords in media queries. How do they help create responsive breakpoints for different screen sizes?

The `min-width` and `max-width` keywords allow you to set a piece of media to a boundary px value.
These keywords help create responsive breakpoints for different screen sizes as they set the boundaries of how big a picture should be and what to do if they meet the px requirement. This makes it so that whether you are accessing a picture on your phone or on a computer, it will fit decently on your screen.

## Prompt 5

Imagine you are teaching a brief lesson on **mobile first design**. Your lesson should include the following information:

* An explanation of mobile first design and a few of the benefits of this approach
* A CSS code example demonstrating how to use media queries to adjust the layout of a container from mobile to desktop with either Flexbox or Grid (choose one).
* An explanation of the code example.

### Response 5
```css
@media (min-width: 600px) {
   ul {
    display:flex;
    flex-direction: column;
  }
  
  main {
    display: flex;
    flex-direction: column
  }
}

@media (min-width: 1000px) {
     ul {
        display:flex;
        flex-direction: column;
    }

    main {
        display:flex
    }
}
```
The code above has two media queries: One set to activate when the screen is 600px or more at one set to activate when the screen is 1000px or more.
They both take the css selectors `ul` and `main`, as well as add flexbox to both of them. This organizes the media in an adjustable column.