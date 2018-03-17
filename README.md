# AIMA WEBSITE 4

## This website is based on the HUGO blog templating service . I made this website to showcase my skills .

In the website page :
- Included some sample exercise question to show that it can integrate with mathjax and can produce code samples .
- It has a fixed content bar that shows all the question headings .

So , if we use Hugo for building the Website this Summer , then :
- We will make X no. of pages like this for X exercises , all connected with a table of contents directory as the index page .

How this works :
- Fork this repo ( master branch ).
- Add the markdown files you want to include in the /contents/Questions folder .
- In terminal , change directory to the project folder .
- Run Hugo Serve ( To check if the markdown file is properly rendered )
- Then run deploy.sh file .( Change the repository link to your repo by editing the file )
- The website will be created/updated in gh-page branch in your repository .
- Manually open the index.html and add ```<link rel="stylesheet" href="css/styles.css">``` in the header , to link the css file.
- Voila ! It's done !


# I have implemented STATICMAN commenting service , which is better than disqus , because it doesn't require any signup to comment and the comments are directly added to the gh-pages branch's ```_data``` folder . One can gice suggestions/ask questions via these comment section . We can also apply a filter that will turn off spam , that I have currently disabled .
