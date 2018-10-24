## Getting Started
So you’d like to contribute to the [IREC 2019 project log?](http://irec19.sedsucf.org/) Great! There are a few steps you’ll have to follow to get set up, but once you’ve got the process down it’s a relatively painless process.

First up, you’ll need a GitHub account if you don’t already have one. After you’ve got one of those, it’s highly recommended you join the [SEDS-UCF](https://github.com/SEDS-UCF) organization. This is not technically required, but it makes life a lot easier. Message Benjamin Straw on the Slack for an invite.

Now you're free to start editing existing posts and writing new ones of your own! The following text describes the easiest way to get started, and is quite simplified. If you're already familiar with Git and Markdown, feel free to edit this on your own computer using whatever tools you're comfortable with.

The only files you'll need to edit reside in the `_posts` directory. To edit an post file, click on its file and then click the pencil icon between the _History_ button and the trash can icon. To create a new post, simply click _Create new file_. (Make sure you're inside the `_posts` directory!)

You'll be greeted with the text editor, where you will do all of your writing work. At any time you can click to _Preview_ tab to see what your post will look like. This will also show you all the changes you've made if you're editing an existing file.

## Post Format
When writing a new post or editing an existing one, there are a few things you should know.

First off, the filename. All post filenames must follow this format:
```
[YYYY]-[MM]-[DD]-some-short-title.md
```
The date in the filename will be the date that the post will have listed as the publishing date on the website. It does not necessarily have to be the day you wrote it. Your title can be whatever you want, but aim for a short filename and no special characters, just letters and dashes.

Now we move on to the content of the file. The first few lines must be what's called "front matter," a block of metadata that tells the website how to handle the file. It must be in this format:

```YAML
---
layout: post
title: "<title>”
tags:
  - <tag>
  - <tag>
---
```

- `layout` MUST be `post`
- `title` can be whatever you want. The title can contain special characters, but NOT a double quote (`"`).
- `tags` is a list of tags that apply to the post. These are not predefined and can be whatever you want. Please make the first tag the team your post represents, or `general` if the post speaks on behalf of the entire team. Note that tags are case-sensitive, and must be all lowercase (with a few exceptions that we'll deal with on a case-by-case basis), however they may contain spaces. Feel free to add as many tags as you want, just continue that pattern (new line, two spaces, a dash, a space, and the tag) as much as needed.

Once you're past those three dashes, you're into the body of your post. Feel free to put anything you want here! Just write out your post, there aren't any other special things you have to do. The posts are formatted with Markdown, [here is a good cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) that shows how to mark up your text to get various effects.

If you need an example of a post to look at, click any of the posts in the `_posts` directory and then click _Raw_, that will show you the actual unformatted Markdown used in the post.

## Making a Pull Request
Now that you're happy with your post, it's time to get your changes live onto the website. The first step is to commit your changes. At the bottom of the page, there is a section with a few text boxes and other various options. In the first text box, provide a short (no more than 1 sentence) summary of your changes. If you feel it's necessary, you can give a more in-depth description of what you did in the second, larger text box.

Make sure that the box "create a new branch" option is selected. The name of the branch is not important, feel free to leave it as the default. Then, click the big gree button.

You'll be taken to a page where you can create a new pull request, which is exactly what it sounds like: a request for your changes to be pulled into the main codebase. Make sure you have some description of your changes in the body of the pull request, and then click the _Create pull request_ button.

The `master` branch of this repo, from which the live website is generated, is protected so that no individual can push changes directly to it. Instead, all changes must be proposed in a pull request and reviewed by another member of the SEDS-UCF organization. They can comment on the pull request as a whole, as well as annotate specific lines of the changed files with comments and suggestions. After they're satisfied with the changes, they will approve your changes, and they can be merged into `master` by clicking the big green button.

Congratulations! Within 30 seconds or so, you changes will be live for the world to see on the [IREC 2019 project log!](http://irec19.sedsucf.org/)

This has been a very simplified guide, and doesn't cover the case where you want to change multiple files at once, or any number of other more complicated scenarios. However, this should be enough for all members of the IREC 2019 team to get started writing their own posts on the website. Show off your creative solution to a tough problem you faced or talk about how your team plans on overcoming a specific issue. Remember to keep them professional and on-topic; the purpose of this website is for the team to showcase its talents and hard work to the world. I'm looking forward to all of the quality posts.

Ad astra.
