# Building a Free Blog with GitHub Pages in Minutes

Here is a link where you can find instructions to create a blog into Github.
https://chadbaldwin.net/2021/03/14/how-to-build-a-sql-blog.html

Here are the steps in the link above.

## This blog post is pending update, but I want your help!

### Step 1 - Create a GitHub account
If you don’t have a GitHub account, create one, otherwise go log in.

Note: Your username will eventually be part of your websites URL, so just keep that in mind when picking a username.

### Step 2 - Open the template I built for you
After logging into your GitHub account, open this link and follow the instructions in Step 3:

https://github.com/chadbaldwin/simple-blog-bootstrap/generate

### Step 3 - Name and create your repository
*If you don’t name your repository correctly, none of this will work

Name your repository like this: {Your GitHub username}.github.io

If your GitHub username is “chadbaldwin”, then name it chadbaldwin.github.io

If your GitHub username is “giraffeface”, then name it giraffeface.github.io

Make sure you leave it set to “Public”. If you set it to “Private”, your website will not be published.

Now you can click “Create repository from template”.


Like this: https://chadblogtest.github.io

--

## Customization
It’s great and all that you have this fancy blog now…but, you probably don’t want your site saying “Default Author Name” all over the place, and you probably want to change the blogs name to something other than “My Blogs Name”.

In order to edit these things, we’ll need to make some changes to this file: _config.yml

If you don’t want to provide an email, or any of the social media usernames, you can simply comment them out using #

Next, you’ll want to customize your home page. Here you can write a small bio about yourself, or maybe a summary of what your blog is about. That’s up to you.

To edit the home page, it’s the same process we just went through to edit the _config.yml file, except this time, you’ll want to edit the index.md file. This is your home page.

Open up index.md, hit the edit button, and start writing. If you know how to use Markdown, you can use that for formatting, but if you don’t, that’s okay, don’t worry about it, just write whatever you want, no need to worry about HTML or CSS or anything like that.



You might be tempted to immediately go to your site to look at the changes, but like I mentioned earlier, you need to wait a minute or two for GitHub to detect that you made changes, and then it needs to rebuild your site. But eventually, you’ll see the changes.

--

## Your first blog post
You may or may not have noticed, there’s already a blog post in there. Take a minute to look at it in the browser, maybe even view it on your phone to see how it looks.

Then go back to GitHub to view the files. Blog posts are stored in the _posts folder and you will see a file in there for the sample blog post.

Before we dive too deep into this, let’s lay out a some of the things you need to know about blogging with GitHub Pages:

GitHub Pages uses software called “Jekyll” to handle all the fancy stuff behind the scenes. Jekyll is what converts your blog post files into nicely formatted HTML that you can view in the browser. Jekyll is capable of doing a TON of great stuff, but for now, that’s really all you need to know.

Blog post files should always be named using this format: yyyy-mm-dd-your-blog-post-name.md

A post written on January 28th, 2021, would be named 2021-01-28-my-blog-post.md. Be careful not to use future dates because the post won’t show up.

Posts are written in markdown, if you don’t know it, don’t worry, there’s not much to it. See this post by GitHub to learn some of the basics.

That’s about all you need to know to get started.

Lets create a new blog post
Navigate to the _posts folder on GitHub
Click Add file > Create new file
Name your file 2022-11-10-your-new-blog-post.md
Set the title of your blog post by using a markdown header
Write this as the first line ## This is my first blog post
Add some content…write some random things, whatever you want
Throw in a code block (code blocks are created by surrounding your code snippet with three backticks at each end and an optional “language hint”), copy paste this in:Copy
 ```tsql
 SELECT *
 FROM sys.tables
 WHERE [name] = 'SomeTable'
 ```
Important note, if you’re using T-SQL code, make sure to use the tsql tag. This will tell your site that you want to use the SSMS style formatting.
Click the Preview tab so you can see what it looks like so far.
Here’s a full playback of what it would look like:



Once you save (Commit) the file, after a minute or two your new post will show up on the home page, ready for everyone to read it.
