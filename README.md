# **Responsive Portfolio**

This project consists of re-creating a website with the bootstrap library through snippits given to us. The goal was to get our website as close as possible to the example and to ensure that all pages worked correctly. We had to make sure we implement bootstrap's navbar, responsive layout, and responsive image classes throughout our files. This project was very challenging but I learned alot during the process.

<br><br>

![image](https://user-images.githubusercontent.com/52800632/102450610-ac914c80-3feb-11eb-92d1-546efa95ba41.png)

# **Installation**
Link bootstraps library to your html files
```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
```

Track changes and push onto your own Github Repository.

```html
git add .
```
```bash
git commit -m "message"
```
```bash
git push origin main
```

# **Built With**

<ul>
    <li> Bootstrap - Front end open source toolkit
    <li> HTML - The standard markup language for web pages </li>
    <li> CSS - used to describe the presentation of markup langauges such as HTML </li>
</ul>

# **Code Snippet**

```html 
  <!--  Responsive Navbar -->
        <!-- Changed navbar background white -->
        <nav class="navbar navbar-expand-md navbar-light bg-white sticky top">
        <div class="container-fluid">
        <a class="navbar-brand" href="#">Ron-Arjay Caluag</a>
        <button class = "navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive" aria-contrls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class = "collapse navbar-collapse" id="navbarResponsive">
```
```html
 
           <!-- w-75 added to customize length of input field -->
            <div class="form-group w-75">
            
            <h1><strong>Contact</strong></h1>
            <hr></hr>
                <label for="inputName">Name</label>
                <input type="name" class="form-control" id="inputName" aria-describedby="emailHelp" placeholder="Name">
            </div>

            <div class="form-group w-75">
                <label for="inputEmail">Email</label>
                <input type="password" class="form-control" id="inputEmail" placeholder="Email">
            </div>
           
            <!--<textarea> used instead of <input> because input is generally used for single lined input -->
            <div class="form-group w-75">
                <label for="inputMessage">Message</label>
                <textarea style = "height: 90px" type="Message" class="form-control " id="inputMessage" placeholder="Message"></textarea>
}
```
# **Deployed Link**

https://arjaycaluag.github.io/responsive-portfolio/

# **Author**

Ron-Arjay Caluag

[Linkedin](https://www.linkedin.com/in/ron-arjay-caluag-00b29b182/)
<br>
[Github](https://github.com/ArjayCaluag)

# **License**

The MIT License (MIT)

Copyright (c) 2011-2020 Twitter, Inc.

Copyright (c) 2011-2020 The Bootstrap Authors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
