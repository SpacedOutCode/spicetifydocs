# Spicetify Theme Developer Docs (Unofficial)

This document is dedicated to what class goes to what element in spicetify. This will include a CSS file with all of the useful classes laid out for you. An easy way to find elements if this doesn't get updated is to open an issue or to enable dev tools and check for yourself on spicetify with `spicetify enable-devtools`. This will be divided up into sections and I will have pictures to represent where the element is.
</br>

## Side Bar

This is the side navigation and playlist bar.

### Nav Bar Parent

**Class:** `main-navBar-mainNav`

**Purpose:** This element dictates the size of the navbar library and the navbar.

![alt text](/Screenshots/sidebar.png)

### Nav Bar

**Classes:** `main-yourLibraryX-entryPoints` & `main-yourLibraryX-navItems`

**Purpose:** Class 1 is the parent element of the nav bar and class 2 is the `<ul>` element that holds the nav buttons.

![Class 1](/Screenshots/navitems.png)
![Class 2](/Screenshots/navbar.png)

### Nav Item

**Class:** `main-yourLibraryX-navItem`

**Purpose:** This is the parent element that makes up most of the spacing and controls the sizing of the nav button.

![alt text](/Screenshots/navitem.png)

### Nav Links

**Class:** `main-yourLibraryX-navLink` & `main-yourLibraryX-navLinkActive`

**Purpose:** Class 1 is the passive link element that redirects the user to the specified page and class 2 is the active version showing what page you are on.

![alt text](/Screenshots/navbutton.png)
