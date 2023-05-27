# **<ins> Furniture store project:</ins>**

The creation of this website actually came about through a misunderstanding of the assignment given.

## **<ins>The task:</ins>**

I was given the following:

* **User brief:** Furniture store.

* **Client needs:** A user accessible and SEO friendly website.

* **Create a loose wireframe:**
    - Show where everything will go for the layout.

    - Show where the elements will go.

* **Annotate the wireframe if possible** - can be hand drawn.

## **<ins>The Misunderstanding:</ins>**:sweat_smile:

**<ins>Can</ins>** code after: add classes to show where I want content to go. 

ℹ️ *(Remember this part if your still reading at this point)*

I fully believed at this point I had been asked to not only design the site from scratch, using the user brief, I also thought I had to build it.

Please also bear in mind that the timeframe would be less than 24 hours and was being worked on straight after I had built my text-based game (also in a repository).

## <ins>Part 1 - Research:</ins>

I knew a little about accessibility as my daughter uses screen reader software to aid her studies at university.
I wasn't completely confident in the subject though, so that was my starting point.

What I found was that user accessibility and SEO go together, as the bots search engines use to site crawl, followed the accessibility DOM the same way a screen reader would.

From my research I took away the following:

* **User experience** - There should be a clear and intuitive user journey.

* **Content hierarchy** - Prioritise the most important and relevant content on each page.

* **Responsive design** - The ability of the site to adapt to different screen sizes.

* Use the principles of ***WCAG*** to implement accessibility testing - **POUR** an acronym for:

    - **Perceivable** - consider disabilities.

    - **Operable** - user control of interactive elements.

    - **Understandable** - content written clearly.

    - **Robust** - assistive technology support.

I also learned the <ins>5</ins> rules for the usage of ***ARIA*** (Accessible Rich Internet Application).

* **Rule 1** - Don't use ARIA - If document is using semantic HTML, ARIA may not even be necessary.

* **Rule 2** - No unnecessary ARIA added to HTML - If the ```<div>/<span>/<input>``` tags are nested within a semantic HTML tag, the nested element gains semantic meaning.

* **Rule 3** - Support keyboard navigation - Allow users to follow logical path through the page or site.

* **Rule 4** - No hidden focusable element - Don't use ARIA properties on elements that should be focusable

* **Rule 5** - Accessible names for interactive elements - This means reduce redundancy in code and not overriding default HTML tags.

There was also mention that semantic HTML has no need for ID/Classes.

***

## **<ins>Part 2 - The Planning/Designing:</ins>**

Taking what I'd learned, I first created a sitemap.

### **<ins>The Landing page:</ins>**

I decided I would create a landing page for a furniture store and created the user journey and wireframe.

The ```<Header>``` would contain the ```<img>```logo and below that the ```<nav>```.
Within the ```<nav>``` would be ```<a>``` for:

* **Products =>** leading to Product details page.

* **About us =>** leading to Brand mission statement page.

* **Contact us =>** leading to a form to submit questions not answered on the FAQ page.

* **FAQ** 

* **Blog**

* **Site search**

* **Shopping cart =>** leading to a Thank you for purchasing page

The ```<footer>``` would also have the following ```<a>```:

* **About us**

* **Contact us**

* **FAQ**

* **Blog**

* **Sitemap**

For the layout I decided to use **CSS Grid.**

The landing page would also have:

* ```<main>``` x 3 **=>** showing CTA (call to action) and featured products.

* ```<article>``` x 3 **=>** leading to featured blogs.

***

## **<ins>Part 3 - The building</ins>**

As I now know, I was only supposed to show the structure of the site and classes/id's to show where the content would go.

I however, as you can see, went even further than showing HTML structure.

Thinking I was working to a deadline, I attempted a CSS layout I had only read about before.

The result is this WIP furniture store.  Even when I was building it I found my initial ideas being discarded in favour of different ones

This was the most frustrated I have been so far in my web development journey and after coming through the other side, I'm quite proud of my accomplishment.

My mentor put it into perspective for me:
Not only did I research, plan and wireframe the website, in less than 24 hours, I managed to build the structure with HTML and attempt to style it with CSS Grid.  

Something I have yet to be taught.

I did have help with fixing my header - a change I made on the fly after seeing a real furniture store website with the same thing.
The sticky header CSS and also the logo image was a bit of a nightmare as the logo I originally wanted was quite big and as a result the sticky header took up too much space.
I also added an extra ```<a>``` 

* **Find us =>** leading to a directions and address page possibly with google maps api embedded.

## **<ins>In Conclusion:</ins>**

In hindsight, I actually enjoyed pushing myself to learn and try something new.
I could've done with not pulling an all-nighter for what turned out to be over and above what I was required to do.
However, this experience has shown me what I'm capable of and I intend to continue with this page as a personal project now.

As you can see from the repository, I am currently working on the same site with **CSS Flexbox**

I will attempt applying what I learn going forward, to this project.
