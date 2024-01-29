# Slide-bootstrap-navbar

```css css
@media (max-width: 992px) {
    .navbar-collapse {
        position: fixed;
        top: 50px; /* adjust to height of navbar */
        left: 0;
        padding-left: 15px;
        padding-right: 15px;
        padding-bottom: 15px;
        width: 75%;
        height: 100%;
    }

    .navbar-collapse.collapsing {
        left: -75%;
        transition: height 0s ease;
    }

    .navbar-collapse.show {
        left: 0;
        transition: left 300ms ease-in-out;
    }

    .navbar-toggler.collapsed ~ .navbar-collapse {
        transition: left 500ms ease-in-out;
    }
}
```
