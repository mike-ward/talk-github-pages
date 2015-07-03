title: GitHub Pages  
author:  
  name: Mike Ward  
  twitter: mikeward_aa  
  url: http://mike-ward.net  
output: index.html  
style: style.css  
--
# GitHub Pages
## Websites for you and your projects
## http://mike-ward.net/talk-github-pages

--
### What are GitHub Pages?

- Web Pages hosted directly from your GitHub repository 

- Just edit, push, and your changes are live

- You get one site per GitHub account and organization, and unlimited project sites

--
### 5 Reasons to use GitHub Pages

>>> ![](all-the-things.png)

--
### 1. It's fast (really fast)

- Pages are static HTML

- GitHub infrastructure is fast  
http://status.github.com

- Caching

--
### 2. It's free

- No ads

- No begging

- No kidding

--
### 3. Use your own domain name

- Update you domain host to point at GitHub

- Add a file with your domain name

--
### 4. Uses Git

- Gentle introduction to Git and GitHub

- All the other advantages of using GitHub

--
### 5. No FTP

- Updating the Repository === Publishing

- `git push`

--
### Demo - How I Publish Blog Posts

1. Add some insightful content to a file
2. Save file in the _posts folder
3. `git cm "my insightful new blog post"`
4. `git push`
5. Stand back and revel in the glory of my blog post

--
### http://pages.github.com

1. Create a new repository named username.github.io
```
where username is your username
```   
2. Clone the repository
```
git clone https://github.com/username/username.github.io
```    
3. Create some HTML
```
cd username.github.io
echo "Hello World" > index.html
```
4. Push it
```
git add --all
git commit -m "Initial commit"
git push
http://username.github.io
```
