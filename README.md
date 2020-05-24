# Code Refactor Starter Code
This project entailed fixing existing code that was for the most part functional (other than a broken button linking to the Search Engine Optimization). 

I started by renaming the header and footer divs to header and footer, before renaming the content and benefits divs to sections. I changed the tags enclosing the links from div to nav. I renamed the individual content and benefit sections to articles as well. When changing "<div class="header"> to <header> I also had to rename the assosiated styles to take into account they were in reference to the pre existing header tag, rather than the original custom versions. 

Once these tags were revised, I moved on to reducing redundant classes. The classes covering the content of each piece of content were identical, as were the classes covering the contents of benefits, so I reduced them from three to one, renaming the class more generically. I then made sure the html would reference these new classes. I repeated this process for the other elements (img, h2). I also renamed the float-left and float-right to content-float-left and content-float-right as they were only used in the content section, and further they had more than one style each. to reduce potential future confusion when attaching what appeared to be a generic class to other pieces of content I thought renaming them was preferable. 

I then added alts to the images to allow for page readers to detail their contents. 

I then saw that the title for the page was simply "website" so I altered it to "Horiseon Inc."

Lastly I saw that I needed to add a readme detailing the project, and here we are. 

URL: https://josephptflanagan.github.io/200524-Horiseon-Refactor/

SCREENSHOT:finished-screenshot.png
