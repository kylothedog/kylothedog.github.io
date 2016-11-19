

Bootstrap

Goals:
- Understand what Bootstrap is and how to properly include it
- Understand Bootstrap’s container class
- Understand the Grid System
- Understand some responsive images with bootstrap









What is a CSS framework?
    Some pre-written, standardized code ...

    that we can include in our code ...

    that ultimately makes our work easier!


Why Bootstrap?
    Incredibly robust
    Includes default styles
    Includes "helper classes"





The Grid System

  - Will help you create layouts
  - Will help you build responsive websites










Three parts of the system:

.container
    |
1200px max width

    .row
      |
    100% width

        .col-*-*
            |
        Each single column = 8.3333% width
            |
        A group of columns = up to 100% width





What's up with col-*-* ?

col = class name denoting that this will declare a screen size and a number of columns

* = screen size, where '*' is xs, sm, md, or lg

* = columns, where '*' is an integer, 1-12





col-md-4 + col-*-4 + col-*-4 = 12 columns

col-*-6 + col-*-6 = 12 columns

col-*-2 + col-*-4 + col-*-1 + col-*-5 = 12 columns

col-*-7 + col-*-5 = 12 columns
