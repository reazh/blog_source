Title: My first blog post!
Date: 2019-10-31 13:51
Category: General
Tags: pelican, publishing, github, git
Slug: first-post
Author: Reaz H.
Summary: First blog post recording the source and method

This is the content of my first blog post. I used the tutorial at [TheDigitalCat's](https://www.thedigitalcatonline.com/blog/2019/06/07/run-a-pelican-blog/) blog to set up this blog. While I am not a novice at versioning nor git, I received a refresher and learned a thing or two in the process.

TheDigitalCat has published a Pelican template on Github. Using the Cookiecutter package, one can replicate the templateand get a blog up and running in no time. However, as usual I ran into some issues. Here's what I learned:

- **Be aware of your private network limitations:** I tried to set this up at work and for the longest time I could not push the blog onto GitHub. I realized eventually that the issue maybe that external ssh access may be blocked (with good reason). 
- **Make certain to have a valid ssh key registered with GitHub:** Use the instructions on [GitHub](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) to setup and store your ssh key. This will enable you to `git push` code to your repository.
- **Always have a separate ***develop*** and ***deploy*** workspace:** [TheDigitalCat](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) uses this method to keep his production blog code clean from development bugs, etc. All the development code is tested using a local server. Once the blog post/page looks ideal, they are committed to the repository and pushed to GitHub from where they are served. 

I am still finding my way around Pelican and Markdown. In days to come, I hope to update some of these posts and pages. I will be linking my repositories on GitHub with explanations soon. While I created this blog to showcase all things related to topics in Computer Science and Engineering, I will also post about unrelated topics as they catch my interest. 
 
