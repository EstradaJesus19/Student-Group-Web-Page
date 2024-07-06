# Student Group Website

Welcome to the repository for a Student Group website! This project includes various sections that represent the activities and resources of the group.

## Site structure

- **Home**: The main page featuring highlighted news and an overview of the group.
- **Blogs**: A collection of blogs written by group members. Each blog covers interesting and current topics in science.
- **Gallery**: A collection of photos and videos from group events and activities.
- **Events**: Information about past and upcoming events organized by the group, including talks, seminars, and workshops.
- **Posts**: An embedded  instagram feed for showing posts and reels.
- **About Us**: Information about the group, mission, team members, and contact details.

## Preview

![Website Preview](/media/preview.gif)

## Guide for modifications

### Board members
To add a new board member, please add the following lines in the div named "board-members" in [us page](/us.html):

```html
<div class="card">
    <img src="" alt="Position" class="profile-pic">
    <div class="info">
        <h4>Position</h4>
        <h3>Name</h3>
        <p>Career</p>
        <p>Semester</p>
        <div class="contact-info-member">
            <a href="mailto:email@uninorte.edu.co">
                <img src="media/email_icon.svg" alt="Email Icon" class="icon">
                <span class="email-text">email@uninorte.edu.co</span>
            </a>
        </div>
    </div>
</div>
```

### Events
To add a new event (upcoming or past), please add the following lines in either div named "upcoming-events" or "past-events" in [events page](/events.html):

```html
<div class="event-box">
    <img src="media/events/induccion.jpg" alt="Event name" class="event-image">
    <div class="event-info">
        <h2 class="event-title">Event name</h2>
        <p class="event-details"><strong>Lugar📍:</strong> Place</p>
        <p class="event-details"><strong>Fecha📅:</strong> Date</p>
        <p class="event-details"><strong>Hora🕞:</strong> Time</p>
        <p class="event-description"> Description</p>
    </div>
</div>
```
Same for adding the event to the [main page](/index.html).

### Gallery
To add new images or videos of an event to the gallery, please add the following lines in the div named "gallery" in [gallery page](/gallery.html):

```html
<div class="event">
    <h2>Event name</h2>
    <div class="photos-videos" id="course_python">
        <img src="link" alt="Event name - #media" class="photo">
        <video class="video" alt="Event name - #media">
            <source src="link" type="video/mp4">
        </video>
    </div>
    <div class="button-container">
        <button class="load-more">Mostrar más</button>
        <button class="show-less hidden">Mostrar menos</button>
    </div>
</div>
```

### Blogs
To add a new blog, please create a copy of [blog0001.html](/blogs/blog-0001.html) in the folder [blogs](/blogs), replacing the content and the data of the blog. Then add the following lines in the div named "blogs-list" in [blogs page](/blogs.html):

```html
<div class="blog-item" data-category="personal">
    <img src="Blog banner" alt="Blog tittle">
    <h2>Blog tittle</h2>
    <h3>Author</h3>
    <h4 class="blog-date">Date</h4>
    <h5><font color="#e89d1c">Category</font></h5>
    <p>First lines...<a href="blogs/blog-0001.html">Leer más</a></p>
</div>
```

## Contact

If you have any questions or suggestions, feel free to contact me at [my e-mail](mailto:jagallardo@uninorte.edu.co).

---

**Thank you for visiting my repository!**
