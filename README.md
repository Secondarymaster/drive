# drive-pages
Pages for drive


##Some lame notes. It's basicly a static webpage. Can use markdown and html etc to generate the pages.
The content for each page is found in /input and assests is home for index.. gonna fix this later lol.

You may notice a makefile, this is because it uses redcarpet to read the input files and gen the html.
If redcarpet isnt cool, we can use something else. I copied SOME of the info from the main readme
from the project. Eventually we'll fix what we need...

So you generate you, need to install redcarpet. (it's a nice simple ruby gem https://github.com/vmg/redcarpet)
Edit the input files to edit the content for the pages. Then run make in the dir... and thats it. 