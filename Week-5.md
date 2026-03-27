# Week 5 – Learning Journal (Prac 5: WordPress Child Themes)

## Learning Activities & Resources

This week I focused on learning how WordPress child themes work and how to customise a website safely without editing the original theme files.

Resources used:
- YouTube tutorials on WordPress child themes (Astra)
- ChatGPT for troubleshooting and understanding errors

Some prompts I used:
- "How to create a child theme in WordPress Astra step by step"
- "Why is my child theme not showing in WordPress?"
- "How to fix stylesheet not loading in child theme"

These helped me understand both the setup process and how to fix issues when things didn’t work.

---

## Estimated Hours

Approximately 2–3 hours

---

## Content Insights

This week I learned that a child theme allows developers to customise a website without directly modifying the parent theme. This is important because if the parent theme updates, any direct changes would normally be lost.

By using a child theme, all customisations are stored separately, which makes the website safer and easier to maintain.

I learned how to:
- Create a child theme folder inside `wp-content/themes`
- Add a `style.css` file with correct header information
- Link the child theme to the parent theme (Astra)
- Use `functions.php` to properly enqueue styles
- Apply CSS customisations such as hover effects, colours, spacing, and layout changes

Using the browser inspect tool was very helpful because I could test CSS changes live before adding them permanently.

### Problem I faced

At first, my child theme was not showing in WordPress. I realised the issue was that my `style.css` file was either named incorrectly or missing the correct header (Template: astra).

Another issue I faced was that some CSS changes were not applying even after activation.

### How I solved it

I checked the file name and ensured it was exactly `style.css` (not `.css.txt`). Then I corrected the header information and made sure the `Template: astra` line matched the parent theme.

For the CSS issue, I realised that I needed to properly link styles using `functions.php`. After adding the enqueue function, the styles started working correctly.

I also used ChatGPT to confirm the correct structure and fix mistakes, which helped me understand the process better.

---

## Career / Employability / Learning Insights

This practical showed me how important it is to follow best practices when working on real websites. Instead of editing theme files directly, using a child theme is a professional approach that prevents future issues.

I realised that developers need to think about long-term maintenance, not just quick fixes. Child themes allow updates without losing custom work, which is very important in real projects.

I also improved my problem-solving skills this week. When my child theme didn’t work at first, I had to debug step by step by checking file names, structure, and code. This taught me to be more patient and systematic.

Another important learning is that tools like browser inspect can speed up development. Instead of guessing CSS changes, I could test them first and then apply them properly.

Using ChatGPT helped me learn faster, but I made sure to understand the logic instead of just copying code. I tested everything and adjusted it based on my needs.

Overall, this week helped me understand how professional WordPress developers customise websites safely and efficiently, which is a valuable skill for my future career in IT and web development.
