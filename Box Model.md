Content: text, images, etc;

Padding: transparent area around the content, inside of the box;

Border: goes around the padding and content;

Margin: space between other boxes;

Fill Area: area that gets filled with background color or background image;
   -- includes padding and border
   -- excludes the margin


Total Width = right border + right padding + specified width + left padding + left border;

Total Height = top border + top padding + specified height + bottom padding + bottom border;

  -- in these cases specified height/width is the content area

example: Total Height = 0 + 20px + 100px + 20px + 0 = 140px

# border-sizing: border-box;
Height and width defined for the entire box.
Includes padding and border with height and width.
  -- excludes margins