# Spicetify Theme Developer Docs (Unofficial)

This is a document dedicated to what class goes to what element in spicetify. This will include a CSS file with all of the classes that are useful laid out for you. AN easy way to find elements if this doesnt get updated is to open a issue or to enable devtools and check for yourself on spicetify with `spicetify enable-devtools`. This will be divied up into sections and i will have pictures to represent where the element is.
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
**Purpose:** This is the parent element that makes up the majority of the spaced and controls the sizing of the nav button.
![alt text](/Screenshots/navitem.png)

### Nav Links

**Class:** `main-yourLibraryX-navLink` & `main-yourLibraryX-navLinkActive`
**Purpose:** Class one is the passive link element that actually redirects the user to the specified page and class 2 is the active version showing what page you are on.
![alt text](/Screenshots/navbutton.png)
