# Project Structure

Each part of the project has **its own assets and style folders**.  

`/project-root`
`│`
`├── index.html                  # Team homepage (embedded CSS only)`
`├── assets/                     # Images used ONLY by the team homepage`
`│`
`├── jaber/                      # Jaber’s personal folder`
`│   ├── index.html              # Personal homepage`
`│   ├── career.html             # Career skills page`
`│   ├── style/`
`│   │   └── style.css           # External CSS for Jaber`
`│   └── assets/                 # Images for Jaber only`
`│`
`├── assmaa/`
`│   ├── index.html`
`│   ├── career.html`
`│   ├── style/`
`│   │   └── style.css`
`│   └── assets/`
`│`
`├── romain/`
`│   ├── index.html`
`│   ├── career.html`
`│   ├── style/`
`│   │   └── style.css`
`│   └── assets/`
`│`
`└── noah/`
 `   ├── index.html`
`    ├── career.html`
`    ├── style/`
`    │   └── style.css`
`    └── assets/`

----------

# Naming Conventions

## **Files & Folders**

-   Folders named after **real first names**: `romain/`, `assmaa/`, `jaber/`, `noah/`
-   Lowercase with hyphens if needed:  
    `profile-photo.jpg`, `team-picture.png`
    
## **CSS**

-   Use **camelCase** for classes and IDs:  
    `.mainHeader`, `.profileImage`, `#bioText`
- Always use double quotes for any string or selector requiring quotes
-   Use **meaningful names**, not visual descriptions:
    -   Good: `.teamContainer`
    -   Bad: `.blueBox`
        
## **HTML**

-   Tab indentation, 4 spaces
  -  Always use double quotes for all attributes (example: `<div id="header" class="container">`)
-   Recommended attribute order:  
    `id` → `class` → others  → `style`
    Example:
`<div id="header" class="container" data-info="...">` 
`<img id="profilePicture" src="https://google.com" style="width: 100px">` 
    
----------

# Git Workflow

The group will use **Git** with the following branching strategy:
-   `master` → final stable submission
-   `dev` → integration branch for merging everyone’s work
-   `romain`, `assmaa`, `jaber`, `noah` → personal branches
    
✔ Members work **only in their own branch**  
✔ After finishing a part, they merge **into `dev`**  
✔ At the end, `dev` merges into `master`

----------

# Page Requirements (According to Assignment)

## **1. Team Page (`index.html`)**

-   Members’ names + student IDs
-   Links to each member’s personal homepage
-   Introduction to **Hefei or Suzhou**
-   Images related to the city
-   External links (some attached directly to images)
-   Text in english
    
### **CSS rules - MUST be inside `<style>` tag (embedded CSS, not external!)**

-   One shared selector for 2+ tags
-   One class selector
-   One contextual selector (e.g., `section p`)
-   Hover effect on `<a>`
-   Several inline styles also required
-   Responsive layout
   
----------

## **2. Personal Homepage (`/nom/index.html`)**

-   Photo, full name, student ID
-   Personal info: hobbies, background, interests
-   Links to:
    -   Team page
    -   Career skills page
-   Career development plan

### **Required CSS**

**External CSS file (`style/style.css`):**
-   Style for all `<p>` tags
-   A generic, reusable class
-   A tag-specific class (e.g., `.header h1`)
-   `.link:hover` or equivalent with hover effects
    
**Embedded CSS** in `<style>` inside the page:
-   One ID selector for font styling
-   One heading style (e.g., `h2 { ... }`)
-   One contextual style (e.g., `.content p { ... }`)
    
> [!IMPORTANT]
> Responsive design required

----------

## **3. Career Skill Page (`/nom/career.html`)**

-   List of hard & soft skills
-   Must include **multiple inline CSS styles** 
    Example:
    `<p style="font-size: 18px; color: #333;">Problem Solving</p>` 
    
----------

# Submission Rules

1.  Place your final project in a single folder
2.  Name it:  
    **Team11_Romain_Assmaa_Jaber_Noah**
3.  Compress it into `.zip`
4.  Submit as per instructor’s instructions
