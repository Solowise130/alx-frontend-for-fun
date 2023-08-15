Sass & Scss

Resources

+ Sass Basics --- https://intranet.alxswe.com/rltoken/kLRkCzW0Yvkj0H6u0AxBVg

+ Sass flow control directives: @if, @for, @each and @while --- https://intranet.alxswe.com/rltoken/yQhZfQxQtH5dUc3iiTfjMQ

+ Sass references --- https://intranet.alxswe.com/rltoken/Pq23qrLxlxGpiintmVQ4zg


Learning Objectives

What Sass means

How to write Sass & Scss file

What is the difference between Sass and Scss

What is the Sass preprocessing

How to declare a variable

How to use nested definition

How to import a Sass file

How to use mixins

How to declare extend/inheritance styles

How to manipulate operators


Install Sass/Scss on Ubuntu 18.04 LTS

$ sudo apt-get install -y ruby2.5 ruby2.5-dev

$ sudo apt-get install ubuntu-dev-tools

$ gem install sass -v 3.7.4

$ sass --version
Ruby Sass 3.7.4


Tasks

0-debug_log.scss --- Writes a Sass file that prints Hello world in the debug output.

1-color_variable.scss --- Writes a Sass file that assigns the text color #3D3D3D to the HTML tags body and p.

2-color_variables.scss --- Writes  a Sass file that assigns:

* The text color #3D3D3D to the HTML tags body and p

* The background color #6D6D6D to the HTML tags body and h2

* You must use 2 Sass variables

3-nested_tag.scss --- Writes a Sass file that assigns:

* No margin or padding in body tags

* Margin 10px to all of the p tags inside body tags

* You must use nested declarations

4-nested_class.scss --- Writes a Sass file that assigns:

* Text color #3D3D3D to elements inside body tags

* Text color #FF0000 to any elements of class .red inside body tags

* You must use nested declarations

5-nested_child.scss --- Writes a Sass file that assigns:

* Text color #3D3D3D to elements inside body tags

* Text color #FF0000 to any elements of class .red that are the first children of the body

* You must use nested declarations

6-nested_hover.scss --- Writes a Sass file that assigns:

* Text color #FF0000 to button tags

* When the user hovers over button tags, text color should change to #00FF00

* You must use nested declarations

7-nested_deeper.scss --- Writes a Sass file that assigns:

* Font size 14px to all body tags

* Font size 16px to all h1 tags inside body tags

* Font size 12px to h1 tags of class .smaller inside body tags

* You must use nested declarations

8-mixin_margins.scss --- Writes a Sass file that assigns:

* Margin left and right at 10px to body tags

* Margin left and right at 15px to div tags

* You must use a mixin

9-extend_list.scss --- Writes a Sass file that assigns:

* Font size 12px to all tags of class .info

* Text color #00FF00 to all tags of class .success and extend style of the class .info

* Text color #FF0000 to all tags of class .warning and extend style of the class .info

10-import_colors.scss --- Writes  a Sass file that assigns:

* Text color $red from 10-colors.scss to the class .red

* Text color $green from 10-colors.scss to the class .green

* Text color $blue from 10-colors.scss to the class .blue

* You must use @import

11-loop_photos.scss --- Writes a Sass file that creates a class for each name in the list $list-names and assigns the background image based on the name

* You must use @import

* You must use @each statement

12-loop_header.scss --- Writes a Sass file that creates H* tags, where ‘*’ is the size of the font used.

* h1 must have font size equal to 1px, h2 must have font size equal to 2px, etc.

* You must create H* tags from 1 to 5

* You must use @for statement

100-loop_col.scss --- Writes a Sass file that creates classes with different width:

* col-1 with width equals to 100%

* col-2 with width equals to 50%

* col-3 with width equals to 33.3333333333%

* col-4 with width equals to 25%

* You must create .col-* class from 1 to 4

* You must use a @for statement

101-media_query.scss --- Writes a Sass file that assigns:

* Font size 20px to h1 tags

* Font size 14px to h1 tags, when your screen width is smaller than 320px

102-media_query.scss --- Writes a Sass file that assigns:

* Font size 20px to h1 tags

* Font size 18px to h1 tags, when your screen width is smaller than 960px

* Font size 16px to h1 tags, when your screen width is smaller than 640px

* Font size 14px to h1 tags, when your screen width is smaller than 320px

* Text color #1D1D1D to h1.small tags, when your screen width is smaller than 320px

103-sort_strings.scss --- Writes a Sass file that sorts the variable $list_to_sort and prints the sorted list in the debug output.
