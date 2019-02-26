A simple 12 column CSS layout tool:
Use class = "col-x" with x being the fraction of 12. For example, class="col-1" would be 1/12 of the screen width, and class="col-6" would take up half the width. Groups of elementscontaining a "col" class can be nested in a div with the class of "row" for additional layout options.

Also a very simple navbar layout:
Use class "nav-bar" for the navbar wrapper, and use class "nav-item" for the individual items:

```
    <nav class="nav-bar">
      <ul>
        <li class="nav-item"><a href="#">Home</a></li>
        <li class="nav-item"><a href="#">About</a></li>
        <li class="nav-item"><a href="#">Contact</a></li>
        <li class="nav-item"><a href="#">Products</a></li>
      </ul>
    </nav>