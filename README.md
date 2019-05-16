# Welcome to your new History 295LA website

I have adapted the ["Clean Blog Jekyll Theme" by Start Bootstrap](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll) to help you get to grips with Jekyll and GitHub pages in this class, and to give you a head start developing your personal websites and projects. [Bootstrap](https://getbootstrap.com/) is an open source toolkit for developing websites, originally started by some people at Twitter.

## To start:
1. Fork this repository and rename it `[yourusername].github.io`. If you have a repository with that name left over from the last class, get rid of it or rename it first.
2. Once you've done this, clone it to your computer using GitHub Desktop or git in the command line.
3. Once the files re on your computer, open the entire project with AtoM. You can do this from GitHub desktop by right-clicking the name of the repository, from a fresh window of AtoM (File > Add Project Folder), or by dragging the folder into the Atom icon in MacOS.
  * How are the files structured?
  * What seems to go where?
4. Then, from the command line, go to that folder and start Jekyll with the command `bundle exec jekyll serve`. This will make a prompt with a a URL, which will be something like `http://127.0.0.1:4000/`. Visit this address to see your site. This is being served on your computer, rather than the Internet. To make it avaiable beyond your computer, you will need to enable GitHub Pages on the GitHub site. We'll do this later. For a reminder about how to use the command line, have a look at the [Programming Historian tutorial](https://programminghistorian.org/en/lessons/intro-to-bash) that I gave you in the first part of the course.
5. In Atom, Open the file called `_config.yml` and enter your details in the various fields.
6. Customise other aspects of your site, add content, make it look like nice. **Make sure you save the files you edit after every change, so that you can see the effects in your browser.**
7. Keep an eye on the terminal. **If you break something, the terminal will let you know, so you can undo the latest thing you did.**
8. When you are finished, commit you changes on the GitHub app and push them up to the cloud. Your website should become available at the address `[yourusername].github.io` shortly after, provided GitHub pages is enabled. If it is not enabled, you can do so from the settings tab. Also stop serving it on your computer by going to the terminal window that is running jekyll and pressing `ctrl+c`.

# Some questions that will probably come up:

### How do I use Markdown?
Check the example blog post, both on the site and in the `_posts` folder.

### How do I add new blog posts?
Create new markdown files in the `_posts` folder, making sure to include the header bit between the three lines (`---`). The easiest way is to create a copy of the example post I made for you and to edit it.

### How do I add new pages?
Create a new markdown file in the `_pages` folder, making sure to include the header bit between the three lines (`---`). The easiest way, again, is to create a copy of an existing file, such as `about.md`.

### How do I add my own pictures?
Copy them into the `img` folder, but make sure they have been optimised for the Internet. (For example, by running them through an application like [JPEGmini lite](https://www.jpegmini.com/), or a web app like [Reduce Images](https://www.reduceimages.com/)). To make them appear in the heading section of your pages and posts, change the paths in the YAML header (the bit between the sets of three dashes - `---` – at the top of the file) from the example files to your own.

### How do I edit the look and feel of my site (fonts, etc.)?
By editing the `assets/main.scss`. I put instructions inside.

### How do I edit the navigation menu?
By editing the `_includes/navbar.html`. I put instructions inside.

### What if I want the home page to be a static page and not a list of blog posts?
Replace the file called `index.html` with the file called `index(page-first).html` (by removing the bit in parentheses), and you can edit the contents as if it were a normal page using Markdown and HTML as long as you keep the YAML header (the bit between the sets of three dashes - `---`) To change it back, replace that file with `index(blog-first.html)`.

### What happens if I break something?
You can always undo the last thing you did and save the file again. If it all goes horribly wrong, you can replace broken files copying them from my repository, or by downloading the theme from it as a zip file, unzipping it on your computer, and replacing the broken files with fresh ones. Or you can fork the repository again and start from scratch. If you get completely stuck, see me in office hours.

---

The original readme.md that came with the theme can be fund in the file called original-readme.md
