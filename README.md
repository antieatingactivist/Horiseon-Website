# Horiseon Website
## https://antieatingactivist.github.io/Horiseon-Website/

This page is an exercize in refactoring including adding accessability functionality, search engine optimization, and descriptive semantic tags. We've streamlined the CSS by consolodating similar code blocks into a more easily maintainable form.


For example, we've consolidated this code...
```
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```
To this...
```
aside section {
    margin-bottom: 32px;
    color: #ffffff;
}
```
This is possible by grouping these 3 elements on the page inside the semantic tags `<aside>` and `<section>`.

---

We have also made the page much more readable by people with special needs by applying the `alt` property to images.

`<img src="...search-engine-optimization.jpg" alt="notebook labeled 'SEO'"/>`



What we've ended up with is a much more readable source code as demonstrated by our browser elements tab.
<img width="448" alt="Screen Shot 2021-12-15 at 7 43 17 PM" src="https://user-images.githubusercontent.com/1414728/146304636-978ac7a8-f4a7-45cd-b594-5ab183dbb564.png">





![Screen Shot 2021-12-13 at 22 07 13](https://user-images.githubusercontent.com/1414728/145942600-ecc07427-8cdb-47ff-b15b-33ee84554ae5.png)

