1. What is HTML?
HTML (HyperText Markup Language) is the standard language used to structure the content of web pages.  
It tells the browser what each part of the page means, like headings, paragraphs, images, links, tables, and sections.


2. W3C Validator
I tested my `index.html` file using the W3C Markup Validator.  
The page passed with 0 errors.

![W3C Validator Result] (assests\validator-result.jpeg) 


3. HTML Entities Used
    1. `&lt;`  → `<`
    2. `&gt;`  → `>`
    3. `&amp;` → `&`
    4. `&copy;` → ©
    5. `&hearts;` → ♥
    6. `&nbsp;` → non-breaking space
    7. `&rarr;` → →
    8. `&quot;` → "
    9. `&apos;` → '
    10. `&trade;` → ™


4. Why I used `<dl>` instead of `<ul>` for Skills
I used a description list `<dl>` in the Skills section because each skill has:
- A term (the skill name) → `<dt>`
- A description (what I can do with this skill) → `<dd>`

This makes more sense semantically than a normal unordered list `<ul>`,  

because skills are not just bullet points, they are pairs of (name + explanation).
