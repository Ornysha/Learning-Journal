# Week 4 – Learning Journal (Prac 4: Local Development)

## Learning Activities & Resources

This week I focused on learning how to set up a local WordPress development environment using XAMPP. I followed online tutorials and documentation to understand how WordPress works locally and how databases connect to the website.

Resources used:
- YouTube tutorials on “WordPress localhost setup XAMPP”
- https://www.youtube.com/watch?v=xzk5Q02gkYc

I also explored how WordPress export/import works using XML files and how hosting platforms like CloudAccess differ from local environments.



## Estimated Hours

Approximately *5–6 hours*

---

## Content Insights

This week helped me understand how WordPress actually works behind the scenes instead of just using it through hosting.

One key thing I learned is that a WordPress website has two main parts:
1. Files (themes, plugins, uploads)
2. Database (content, settings)

When I moved my site from CloudAccess to localhost using an XML file, I realised that the XML only transfers content like pages and posts, but not the theme itself. This caused errors like “Stylesheet is missing” because the theme used online was not available locally.

I also learned how WordPress stores important settings inside the database, such as the active theme (template and stylesheet). Fixing this manually using phpMyAdmin showed me how powerful and sensitive the database is.

Another important learning was understanding localhost URLs vs live URLs. My database was still pointing to the live CloudAccess domain, which caused conflicts. This helped me understand why proper configuration is important when migrating websites.

---

## Career / Employability / Learning Insights

This practical made me realise that real-world web development is not just about designing websites, but also about problem-solving and debugging.

I faced multiple issues like:
- WordPress installation errors
- Database connection confusion
- Missing theme errors

Instead of giving up, I learned how to search for solutions, follow documentation, and fix issues step by step. This is an important skill in the IT industry because developers often spend more time debugging than building.

I also realised that using a local environment like XAMPP is very useful because it allows safe testing without breaking the live website. This is something professionals use before deploying real systems.

From a learning perspective, I found that doing hands-on work (like installing WordPress and fixing errors) helped me understand much more than just watching videos. When I made mistakes, I learned faster because I had to actively solve them.

Overall, this week improved my confidence in working with WordPress, databases, and troubleshooting technical issues, which are important skills for my future career in IT.
