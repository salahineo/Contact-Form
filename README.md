<h1 align="center">Contact Form</h1>

## Table of Contents

- [Goal](#goal)
- [Benefits](#benefits)
- [Installation](#installation)
- [Configurations](#Configurations)
- [Technologies](#technologies)
- [Contact](#contact)
- [Copyright and license](#copyright-and-license)

### Goal

This is a simple contact form using PHP-Mailer library with gmail SMTP server. I coded this project to practice on my knowledge of HTML, CSS, jQuery, and PHP in real project.

### Benefits

Here are some ideas to benefit from this project:

- Take this project as a task and try to make it, and if you could not do a specific section, see how i make it in the source code (use comments to reach this section).
- Extract code of specific section and use it in your project.
- Review source code to see how other people code their projects.
- Edit on this project after studying its code well, to know how to work in pair-programming with other people
- Upgrade this project, and add your own sections or pages

### Installation

Here are the guidelines to run this project on your localhost:

1. Download, then install [XAMPP](https://www.apachefriends.org/download.html) web server
2. Download this project, then rename its folder to `contactForm`
3. Copy the `contactForm` folder to the `htdocs` folder which exists in XAMPP installation path
4. Start XAMPP control panel from your Desktop, then start `apache` web server
5. Open your browser, and type `http://localhost/contactForm`

### Configurations

Here are some configurations to do in the `index.php` file:

- Set the `$mail->Username` (line: 37) to your google email (ex: example@gmail.com). This email will be used to send messages from google
- Set the `$mail->Password` (line: 39) to your google password for previous email
- Set the `$mail->addAddress` (line: 46) to your google email, and your name. This email will be used to receive messages

> In the `$mail->Username`, you should add a google email which allow the **Less Secure App Access**, otherwise the message will not be sent with this email. You can manage that from google email security settings

### Technologies

- HTML
- CSS
- jQuery
- PHP

> This Application is fully responsive

### Contact

- [Github](https://github.com/salahineo) :octocat:
- [LinkedIn](https://linkedin.com/in/salahineo) 💼
- [Website](https://salahineo.github.io/salahineo/) :globe_with_meridians:
- [Facebook](https://facebook.com/salahineo) 😎
- [Twitter](https://twitter.com/salahineo) 🐤
- <a href="mailto:salahineo.work@gmail.com">Email</a> :email:

### Copyright and license

- **[GPLv3](https://www.gnu.org/licenses/gpl-3.0)**
- **© 2020 | Mohamed Salah**

---

**If You Find My Work Good, Consider Giving it a :star: or Fork-ing to Show Some :heart:. It Helps Me Stay on Track and Be Motivated.**

> **Explore all of my projects from [Here](https://github.com/salahineo/Projects-Reference)**

---