# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

What are the main differences between Flexbox and Grid layouts? Describe scenarios where each layout system would be more suitable.

### Response 1

While both the Flexbox and Grid create an ease of use by eliminating the need for float or positioning when making a layout structure, they still differentiate from one another in some ways. The flex-box works as an container with items inside it, while the grid works as a parent-child system(in which the child does whetever the parent says). The more definitive differences are between the Flexbox's properties and values against the Grid's. The grid is not even a container by defualt, you have to transform an HTML element into a grid container by changing it's display property value to grid. The difference between the two containers is that flex-box, hence the name is way more flexible and offers a lot more display options, while grid only works as a set of columns and rows with the size and amount of colums and rows being the only thing that can be modified. The Flex-box items can be modified directly allowing for much creativty; the grid on the other hand requires the columns and rows to be modified, giving the illusion of item manipulation meaning a lot more restriction and calculated item positioning. Flex-box even provides the option to create multiple varients of the same form to be used on different devices with very diverse screens and interface settings. If someone is working on a form that is meant for only certain eyes to see, with there being only two types of screens it would be viewed on then grid would be the layout to use, however for almost everything else flex-box would be more suitable.

## Prompt 2

What is the difference between `justify-content` and `align-items` in Flexbox? How does each property control the positioning of flex items within the container?

### Response 2

In Flexbox, `justify-content` aligns the items according to horizontal placement, and manages the empty space that surrounds the items, while `align-itmes` aligns the itmes according to vertical placement, and manages how much space the items take within the container.

## Prompt 3

Describe the difference between `grid-template-areas` and `grid-template-columns`/`grid-template-rows`. When might you prefer one approach over the other?

### Response 3

## Prompt 4

Explain the `min-width` and `max-width` keywords in media queries. How do they help create responsive breakpoints for different screen sizes?

### Response 4

## Prompt 5

Imagine you are teaching a brief lesson on **mobile first design**. Your lesson should include the following information:

- An explanation of mobile first design and a few of the benefits of this approach
- A CSS code example demonstrating how to use media queries to adjust the layout of a container from mobile to desktop with either Flexbox or Grid (choose one).
- An explanation of the code example.

### Response 5

Mobile first design is an approach that focuses on designing and developing a website for mobile devices first, then modifying it to adapt it to larger screens. Mobile devices now account for a significant portion of internet traffic so there are many benefits to this approach. Designing for mobile devices first ensures a better experience for the users. Mobile-first designs tend to result in smaller file sizes and faster load times, because the priority is to deliver only the necessary content to mobile devices. Not only is this approach convient for users but also for the designers;it is a less demanding and tedious task to progressively enhance a design by adding features and styles for larger screens compared to scaling down a desktop design for mobile devices.
