# Design System 101
Are you planning to develop a Design System or just curious to know what Design System is? 
If yes, then here is the detailed guide for you. No matter who you are - a designer, developer, 
product owner, UX Writer, tester etc. this guide do have something for everyone.

# Why this guide?
From last few Months I am working on Design System at my workplace. There were challenges and lot of learnings too. 
I was sharing my experience on social media about DS as a result many people showed their interest in DS. This
guide is for everything I learned and I will be learning while working on DS.

## Key Terms:
- Presentational and Functional Components
- Open and close components
- Namespacing - CSS and React
- Performance Metric
- Your DS's terminology 
- Your DS's rules
- 360 degree consistancy (from style to documentation)

## Agenda
- What is Design System?
- Why you need a Design System?
- Use the already available or create your own?
- How to Start?
- Scope of the Design System.
- Roles in Design System
  - Designer(s)
  - Developer(s)
  - UX writer(s)
  - Tester(s)
- Pre Design System guide
  - Designer Guide
    - Design audit
    - Design Tokens
    - Styleguide
    - Flexibility vs consistency
    - Design Kits
    - Color palatte
    - Micro-interaction(s)
    - Design language and tone
  - Developer Guide
   - Reusability
   - Consistency
   - Scalability - SCSS, Methods, Kits, styleguide, React, namespacing
   - Archiecture
   - Tech Stack
   - Delivery the DS
   - Documentation
   - Examples
- Post Design system
   - Releases
   - Maintaince, CR
   - Awarness and Advocacy
   - Community Building
   - Collabration
   - Mesaurement of the DS

- Learnings
- Do's and Don'ts
- Portal - All details...one stop solution of all the infromation, Think it as a portal for every new designers, product manager, Developer as the black book to learn about the company and guidelines. 

### EXTRA
- Lifecycle of Design system
- Security
- Multi Tech Stack + DS
- Scope of the Design System
- Advocacy
- Design tokens
- Organize the team to scaleability
- Internal community
- What is successful DS - KPI (Key performance Indicators - survey - speed, quality, ease of contributions and completness)


## What is Design System
A single source of the truth for the designers, developers, and the products.

## Why Design System
We talk about the smart work and consistency.Developers, Designers, even the product owner are doing same thing again and again.
DS helps in saving time, bring consistency in the products. Develoeprs and the product owners can focus on the more innovative work 
by adapating the D. DS helps in building the prototype the product.

## How to start?
Do not start with the code. I repeat do not.

- Audit and review the current projects
Understad the current products. Review the product designs understand the UI , UX and patterns.

- Survey
Do survey about what current DS they are using? What are deciding factors to pick a DS etc.

- Scope
Create the scope of the DS. You don't need to everything. It is fine if in starting you have only 10 components or just style guide but it is not fine if no one is using them. Would it be responsive or not? No one is going to ask you about accessibility but you need to do it.

- Tech stack
What technology you are going to pick? If there are decision makers then your job is easy otherwise you have to spend time to make the rest of the products understand why X and not Y.

## Pre Design System
Do the audit of the products from the POV of UX and UI. Understand the browsers, OS, Breakpoints etc.
Pull out the patterns
Pull out the components
Understand the Typescale, Spacing, Colors, Micro-interaction(s), 
Understand the data-handling and consuming
Understand the performance metric (if any)

## Collabration
- Product Audit
- Design tokens
- Namespacing
- progressive Enhancement
- Browsers + OS
- Patterns
- Dos and Donts
- Documentation


## Designer Guide
- Colors
- Sizes (types)
- typescale
- Spacing
- Responsive
- progressive enhancement
- Styleguide
- Micro-interactions
- Error stages
- Design Kit for scalability
- UX guides (Dos and Donts such as - when to use what? Accordion vs tabs, Color contast, tags vs chips)


## Developer Guide
- Tech stack
- NPM or Yarn or CDN
- Responsive
- Accessibility
- Reusability
- Architecture
- CI/CD
- Consumable Lib
- Backward compatibility
- Documentation
- security
- Test cases
- List of the components
- Scope of components
- Releases
- Change Requests
- Defects
- Maintaiance
- modules
- Quality

### Tech Stack
Pick the tech stack by research

### Quality
Prettier, CSSLint, JSLint, Format. Make them part of the CI/CD.
Make them the part of the Github Readme

### Responsive
Scope of responsive. If not responsive then how we are going to pass the message?

### Accessibility
No matter anyone asked or not make the accessibility the part of your development

### List of the components
Make the list of the components

### Reusability
Reusability is very important not just for the users but for the developers too.
Whenever you are developing anything keep thinking how it can be reuse not just by user but by developer too.

### Architecture
PS: We used SCSS because we were scaling our DS in Angular and React. Hence instead of CSS-in-JS this is more easy way.

Vanilla
React
Angular

### CI/CD
Diagram

### Consumable Lib

### Backward compatibility

### Test cases
For smaller component you might feel that there is no need of test-cases
but as you move ahead it is important to take TDD.

### CSS Guide
- BEM
- Functional CSS
- Name space
- Naming convention
- Breakpoints
- Colors
- Font-family
- Typescale


### Markup
- Semantic
- Avoid lot of code
- Markup with classname should not be tighltly coupled
- Close vs open Markup
- Data-attributes


### Javascript
- How to initalize
- Repaint vs reflow
- Memory leaks
- Data-attributes vs classname/ID
- Dynamic Binding
- Event delegation + binding


### React
- Sepration simple to complex
- props required, default
- props validation
- Flexibility vs conisitency
- JS or React State?
- children, HOC, etc
- Playground
- Why smallest component also

### Tech Stack
As a developer you need to decide the tech stack of the DS. It is not simple to pick any famous tech. You need to understand your company' product, market demand and few more.

The few decision making points are:

- Team skills
- Migration
- Learning curve
- Browser and OS support
- Open issues
- few more...


- Vanilla
- Reactjs
- Angular
- Vuejs
- Web components
- Stencils

- Folder archietcture
- Build process
- Playground
- Documentation
- Themes
- Patterns
- Examples

## Reuseability
- Styling
- Markup
- Methods and props names
- Documenation template
- Global Methods
- CSS Styling
- Design Kit
- Styleguide
- Decide between flexibility vs consistency
- Components within components
- Modules - SCSS 

## Documentation
No matter how good your design system is but if you don't have good documentation no one is going to use it.
As well as bad documentation will also lead to lot of issues in the Github full of queries. Hence, documentation is important.

Documentation is collabration work of UX Designers, UI developers, and UX writers. 

Create a template of documentation and share with the team to fill it - Images, examples, DoS and Donts, description of component, how to use, methods, props guide.

## Patterns or Examples
Build the ready to use patterns from your design system. It will help you to understand the gaps, fix the gaps and understand how easy is DS to use. As well as, these will interest lot of products who want to save the time.

No one is going to come and ask for 'I am looking for checkbox or button' but there is higher chance of developers coming and asking about I am looking 'Filter-able Data grid with pagination'.


## Post Design System
- Release plans
- Defect log
- New Feature Request
- Awarness and advocacy 
- X vs Y - Ask why? and then implement that in your DS.
- Community Building


## Learnings
- Migration is tough
- Every product is a case study
- You need to taste your own medicine
- UX is always take prioroty
- Defining the scope is important
- Patterns are very important
- Start always from the small
- You should not add a component in your DS coz X product is asking
- To gain the trust about DS talk about how we are checking the quslity and maintaing the testing, as well as
  build process, release plans etc.  



## Dos and Dont's
- Start from small
- Thinking about reusability
- Always consider the flexbity
- Create the scope of the DS and components
- rem, em , px
- use children
- Less required
- Namespacing - class name as well as props
- Props valdiations
- Close vs open components

## Where to Host?
You can pick either github or a dedicated website. It is always good to provide the website, the reason is non-tech people such as 
designers, UX writer, product owners can easily go and check the informationa and if you have clients then for them too. 

Website will become the 'Black Book' of your company work culture - UX, UI, Guidelines, the case styuides etc. 


## Thank you very much by reading till end.




