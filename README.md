<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8" />
<title>My Projects</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial;
}

body{
    background:#111;
}

/* PROJECT BLOCK */
.project{
    position:relative;
    height:70vh;
    overflow:hidden;
}

.project img{
    width:100%;
    height:100%;
    object-fit:cover;
    filter:brightness(70%);
    transition:.4s;
}

.project:hover img{
    filter:brightness(100%);
    transform:scale(1.05);
}

/* TITLE */
.title{
    position:absolute;
    bottom:40px;
    left:40px;
    color:white;
    font-size:3rem;
    font-weight:bold;
}

a{
    text-decoration:none;
    color:white;
}
</style>
</head>

<body>

<!-- Project 1 -->
<a href="projects.html#project1">
<div class="project">
    <img src="https://picsum.photos/1600/900?1">
    <div class="title">Residential House</div>
</div>
</a>

<!-- Project 2 -->
<a href="projects.html#project2">
<div class="project">
    <img src="https://picsum.photos/1600/900?2">
    <div class="title">Community Center</div>
</div>
</a>

<!-- Project 3 -->
<a href="projects.html#project3">
<div class="project">
    <img src="https://picsum.photos/1600/900?3">
    <div class="title">Urban Plaza</div>
</div>
</a>

</body>
</html>
