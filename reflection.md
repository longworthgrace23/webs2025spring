# Reflection

## Project description

Even before reading the parachute prompts for this unit, I knew I wanted to create a professional portfolio of my writing samples and design experience (mostly because I had been meaning to sit down and make one to submit with job applications all year). After gathering the samples I wanted to include and learning the basics of HTML and CSS using the Kevin Powell tutorial, I began building the site in VSCode. 

### Landing page

The basic structure of this home page includes four sections: a top layer briefly describing me and my professional qualities plus a headshot, two links to navigate between the main categories of my samples, a more in-depth description of my professional experience pulled from my resume, and a footer with links to a few of my social media profiles and the site’s credits. I used grid styling on the first two sections, using classes and divs to properly define them and the CSS property “grid-auto-flow” from [this tutorial](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow) to ensure viewport size-responsiveness. The images below show the before-and-after of the size responsive styling on the “projects” menu in both code and browser view. 

Before:
<img “src=https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/unresponsive%20styling%20on%20.projects_nav.png?raw=true”>

After:
<img “src=https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/projects%20menu%20sizing.png?raw=true”> 

### Sample hubs

The buttons in the images above direct users to two HTML pages (“written_samples.html” and “design_samples.html,” respectively) that list links to the samples I’ve chosen to include in the form of either further subpages or the sample’s original publication. Each sample’s link is attached to an image with a blue border that changes size and shade when hovered over, which adds to the site’s visual appeal but was difficult to figure out. Billy suggested in workshop that I use the a:hover declaration in my site more. I use it on the various menus throughout the site like the main menu, sample buttons on the landing page and social media links, but it’s best displayed in the image links.

<img src="https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/feedback.png">

<img src=“https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/img%20link%20border%20change%20(workspace%20+%20webpage).png?raw=true”>  

These images also had issues with viewport size-responsiveness when I first implemented them. In trying to keep them all a consistent size, I declared a fixed height property on them in CSS and caused them to warp when the screen got smaller. Because they were also in a grid with fixed column proportions, the captions beneath each of them narrowed to about one word per line on a small viewport. To address both of these problems, I combined ideas from the [“grid-auto-flow” tutorial](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow) and the [Rachel Andrew tutorial](https://gridbyexample.com/examples/example28/) from lesson 22. The “repeat(auto-fill, minmax())” property from the latter forces divs into new rows when the viewport becomes too small to accommodate an image of the declared size, while the former involves the “dense” value that keeps the images attached to their corresponding captions as items move around. The screenshots below show what the grids look like on a full Chrome window on my laptop versus an iPhone 14 (converted using the inspect tool):

Chrome window:
<img src=“https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/sample%20layout%20full%20chrome%20window.png?raw=true”> 

iPhone:
<img src=“https://github.com/longworthgrace23/webs2025spring/blob/main/screenshots/sample%20layout%20responsiveness.png?raw=true”> 

### Individual samples

Because most of my academic essays only exist on my Google Drive, I decided to copy/paste them into their own subpages of the site rather than converting them into PDFs so the styling could match the rest of the site. They were relatively straightforward to compile, including headings, body text, and smaller lines of text near the top with a byline and some necessary context for each paper. Both pages open into new tabs, so users can easily get back to their previous page (either of the sample hubs) by navigating between tabs. All of the site’s pages also include the main menu at the top of the screen, meaning users can also go directly back to the home page or one of the sections of it. 

## Next steps

While I was able to accomplish much of what I intended to when I started this project, there are several aspects of it that I would like to continue working on in the consolidation unit. For example, I was hoping to have made more progress on a data analytics research project by this deadline, but I don’t have enough complete to include it as a robust example of my work. By the end of the consolidation unit, it will be fully complete. I would also like to keep experimenting with the code I’m using to make my grids size responsive. I’m mostly satisfied with the sample images, but I think my headshot on the home page is too large, and I haven’t been able to figure out how to make it smaller while still having the text take up the rest of the screen. Same goes for the main menu and social media grids – on small screens, the individual links either overlap each other or force a horizontal scrollbar. Based on this and Billy’s feedback, I’d like to reevaluate how I’m structuring the main menu and potentially convert the entire thing into a hamburger menu. 

## Criteria + Conclusion

At this point in the process, my site is meeting all of the baseline and some of the aspirational criteria for the project. For baseline, I use size and color to draw the viewer’s attention, navigable HTML locations, a sitewide stylesheet, no dead ends, images with alt text and credits, and elements that load successfully in a web browser (according to the feedback I received). As far as aspirational criteria, my design is dynamic and responsive but could be optimized, as discussed in the previous section. I use grids in much of my layout styling and further include non-default fonts and coordinating colors for audience engagement. For the code, I ran my HTML files through a validator website and resolved all errors, my code includes comments and whitespace for readability, and I used semantic HTML and WAVE to check my accessibility practices. 

Overall, this project was difficult but rewarding to work through. I am happy with the point I am at currently and am excited to improve the project even further in the next unit.

# First Draft

This repository houses Grace Longworth's professional portfolio, built in HTML and CSS and designed for Professor Ben Miller's "Composing Digital Media" course at the University of Pittsburgh. 

This site walks the viewer through two main categories of my work: written and designed. The landing page also includes a brief introduction to me, an image of me, more in-depth information on my professional experience and skills, and links to my social media accounts. The site's two primary subpages divide the work samples I've chosen to include into the aforementioned categories and provide links to each one using related images.

# Preview

So far, the .html content of my web design project builds out the basic structure of the landing page. It includes a heading with a title and a navigation menu, space for a professional headshot and introduction, a projects section with further navigation to two undeveloped html pages, and a section that will contain information about my professional experience. Next steps for this page include writing up text to fill the space currently taken by placeholders, building up the styling, and increasing the functionality of the header's navigation. For the two blank pages linked in the 'projects' section menu, I plan to use them as a hub that direct users to links/further pages within the site containing my work samples. The samples included will correspond with the two subpages I have outlined. 

**No assets used yet**

# Proposal

My plan for this web design project is to curate a professional portfolio of my work in both journalistic/research writing and digital production/design (photojournalism, work from this class and similar projects, etc). The main pages within this project will be a home/landing page that gives a brief description of me and serves as a cover letter of sorts, a page each for writing samples and digital projects, and an “about” page that provides a more in-depth look at my professional experience (more like a resume). Since many of the samples I plan to include are unpublished and only exist in my Google Drive, the links to them in the greater writing samples/digital projects pages will lead to subpages within the website with text copied and pasted rather than external files. This will allow me greater freedom in their design (fonts, colors, etc) and avoid forcing users to download additional files to view the site’s contents. Any published work will include a link to its original publication.

Sketches:
<img src="screenshots\IMG_5234.jpg">

Prospective assets:
| **Needs** | **Solutions** |
| -------------------------------- | ---------------------------------- |
| Headshot | Personal image | 
| Menu icons | Undraw | 
| Background/header image(s) for landing page/menu | Unsplash |