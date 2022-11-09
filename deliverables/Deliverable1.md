## Deliverable 1
---
### What is a static site generator?
----
A **static site generator** is a tool made to automate the creation of web pages. Using a template and data parameters a Static site generator can generate an HTML file for a specific purpose.

---
### What is Jekyll
---
Jekyll is a static site generator that has risen in popularity for its integration with github.

---

### What is github
---
Github is a for profit cloud service for hosting files using the open source distribution control program: git.

---
### How to install Jekyll in Ubuntu
---
Jekyll is installed using simple commands

|Command|Purpose|
|-------|-------|
|```sudo apt-get install ruby-full build-essential zlib1g-dev```| Download Ruby and all of the other prequesites|
|```echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc source ~/.bashrc``` |Installs ruby gems to your home account |
| ```gem install jekyll bundler``` | Installs jekyll |

---
### Building a jekyll website

---
Jekyll websites have a file directory set to the following structure.

|Directory/file|Purpose|
|----------|------|
|_posts|Contains daily posts |
|_static|Contains the compiled website|
|about.markdown|The about page|
|index.markdown|The home page|
|404.html|Contains the 404 page|
|config.yml|Contains the sitewide

---
### Documenting the Process of building a site.

|![](screens/2022-11-09_10-18.png)|
|:--:|
|![](screens/2022-11-09_10-19.png)|
|Installing the prereqs|

|![](screens/2022-11-09_10-23_1.png)|
|:--:|
|![](screens/2022-11-09_10-23.png)
|Installing Jekyll and using a command to create a website|
|![](screens/2022-11-09_10-24.png)|
|![](screens/2022-11-09_16-19.png)
|A basic website, before and after testing ,making a new post|
