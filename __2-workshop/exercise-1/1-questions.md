# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screenreading helps peoeple who are blind or visually impaired to use computers and access websites, so if the html format is not in the correct order, the screenreader will read things from the top then the botton and create issues for the users.

https://abilitynet.org.uk/factsheets/introduction-screen-readers

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
img
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
ul, ol, li, a href=""
c) You want to sell designer hats. You need to receive orders from the user.
input, type
## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, a button is a clickable element and an inline element. Inline elements don't include children and clickable elements' descendants cannot be clickable elements.
## Q5 - What is the most generic tag you can use?
div
## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list items

e) `tr` table row

f) `th` table head

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?
td is usually a child of tr
## Q8 - What is the difference between td and th?
td stands for table data and represents the items in the table.
th stands for table head and it represents the header of the column in the table.
## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1, however, we should never use it to control size, but instead control size by using CSS.
If we use h1 to make text bigger this will create problems for screenreaders.
## Q10 - In which situation can you use self closing tags?
If the element did not have any children or text between tags.
## Q11 - What is autofilling and why is it important?
Autofilling is when the input field predicts the rest of the text, it just more convenient.
## Q12 - Which attributes are always present in an img element?
src="", alt=""
## Q13 - Which attribute is always present for an anchor tag?
href=""