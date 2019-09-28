# Design System 101
Are you planning to develop a Design System or just curious to know what Design System is? 
If yes, then here is a detail guide for you. No matter who you are - a designer, developer, 
product owner, UX Writer, tester etc. this guide have something for everyone.

# Why this guide?
From last few Months I am working on Design System at my workplace. There were challenges and lot of learnings too. 
I was sharing my experience on social media about it.Many people showed their interest in it. Hence, I have documented my learnings on the Design System.

## Key Terms:
- Presentational and Functional Components
- Open and close components or Flexible or non-flexible components
- Namespacing - CSS and React
- Performance Metrics
- Your DS's terminology guide
- Your DS's rules and scopes
- 360 degree consistancy (from style to documentation)

## Agenda
- What is Design System?
- Why you need a Design System?
- Why to and not to use available Design System?
- How to Start?
- How to define the scope of the Design System.
- Role of team members in Design System.
- Pre Design System guide for the team
- Post Design system
     - Release plans
     - Maintaince
     - Evangelism (Community Building)
     - Collabration
     - Metrics of the DS - use, etc.
     - Lifecycle of Design system
     - Team plan for the scalability
     - What is successful DS - KPI (Key performance Indicators - survey - speed, quality, ease of contributions and completness)
- Learnings
- Do's and Don'ts
- Portal and playground

## What is Design System?
A single source of the truth for the designers, developers, and the products.

## Why you need a Design System?
Design system is not a new thing. These are here from decadeds. Thanks to our very complex UI and UX as well as rapidly changing technology. Companies are moving towards the Design System to also make sure that :

1) Brand guidelines of the organization is followed by every product and project of the organization.
2) Code Guidelines of the organization should be followed by every product and project within the organization.
3) Designers and engineers can focus on more important and creative work rahter than just doing same task again.
4) Remove the redundant tasks.

## How to start?
This is the most important question for everyone who is new to design system. If you will Google Design System guide - the result you will get is what design system is, what it has etc. but no one explain - "How to start a design system" from a UX, UI, product Lead , or tester presepctive.Here is the process which I have followed and you can follow too:

For Developers: "Do not start with the code."
For Designers: "Do not start with the design."

Most important task is to understand clearly about the scope of the design system, problems you are trying to solve by Design System, requirements of the organiztion. But how to start to do this?

__1. Audit__

If you are not sure of the product or design decisions then the first step should be to meet the products and project teams.
Have a look at the existing proxuct's UX, UI, tech-stack, pain areas etc. Make notes from every product and try to look for common components, patterns, colors etc.

__2. Survey__

If meeting the team is not possible , then do the internal survey. Ask about the what kind of design system they would like to use? What makes them to use a design system? etc.

These 2 steps going to help you to understand about your organization's current product/projects current situation on the UX, UI, Design system etc. Most importantly to make them aware of design system and why it is important.

**NEXT STEP**

Once you have the list of the common components, patterns, etc. Now, is the time to UX team to look into the defining the scope. Remember one cannot have every component in the Design system. Why? because reason of design system to have 'reusable' components. The reusable components should be used by more than atleast 2 products. Otherwise every product/project will keep pushing their work on design system team as well as extra components will make the design system heavier.

__1. Scope__

Defining the scope of the DS is very important from the UX and UI. You should decide what all your DS should have from UX - styleguide, color palattes, design files, design specs, responsive, breakpoints , Dos and Don'ts, which all components etc. From UI, think about the tech stack, repos, architecture etc.

__2. Tech stack__

For developers this is the most important decision to make. If your company is using only 1 lib/framework then there is no decision to make. Otherwise do a good research of the industry and make list of the available options and their pros and cons. 
Few things which will help in making decisoions are:

- Community support
- Learning curve
- Stable version
- Team skills

So far you have done this:

1) Met your product/project teams and got the insight of the UX, UI etc.
2) Have the scope of the DS : what all we are going to have from UX and UI.
3) List of all components to be in the DS
4) Tech Stack for the development

**Milestone 2**

__1. Designers__
As a desginers of Design system you should have the list of the following:
- Colors - which all colors your design system will have? Primary colors, Alert colors, secondary color etc. Make sure that these colors are passing the contrast ratio.

- Typescale - What would be the typescale of the typography of your design system? There should be minimum font-size your design system should have. Decide on the Typescale - will there be fixed type sizes or user can have any.

- Spacing - 
- Responsive
- progressive enhancement
- Styleguide
- Micro-interactions
- Error stages
- Design Kit for scalability
- UX guides (Dos and Donts such as - when to use what? Accordion vs tabs, Color contast, tags vs chips)


 - Design audit
        - Design Tokens
        - Styleguide
        - Flexibility vs consistency
        - Design Kits
        - Color palatte
        - Micro-interaction(s)
        - Design language and tone


__2. Developers
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
- Reusability
     - Consistency
     - Scalability - SCSS, Methods, Kits, styleguide, React, namespacing
     - Archiecture
     - Tech Stack
     - Delivery the DS
     - Documentation
     - Examples
     - Design tokens
     - Multi Tech Stack + DS
     - Security


__3. Collabration__
- Product Audit
- Design tokens
- Namespacing
- progressive Enhancement
- Browsers + OS
- Patterns
- Dos and Donts
- Documentation






### Component's Requirement and list
Provide the list of the component which are production ready, work-in-progress, and under discussion.

### Tech Stack
It would be very tempting for the developers to pick the tech stack as per their skills convience but when you are developing design system you are building for the consumers to use them in their project. Hence, it is important to use the tech stack which is widely used not just in the world but in your organiztion too. The survey to get the requirements should have the field which tech is the product currently is on and are they planning to migrate to anyother tech if yes then name please.

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

### Architecture
The architecure of your DS will depende upon the tech-stack you have picked.One needs to get
into the depth of the tech-stack he/she has picked to design a good archietecture. The building blocks
of the DS is styling, Utilities, and components. Make sure that you are thinking about scaling and reusability around these
when you are desiging your DS.

One can pick SCSS solution over CSS-in-JS if one wants to reuse the styling as lib.

- Vanilla
- React
- Angular
- Vue



### Responsive
Always have the Mobile first approach. To support the responsive behaviour you should define the scope of it. You need to close:

1) Breakpoints and Devices
2) Font behaviour
3) Micro-interactions's behaviour

You can define these breakpoints:


### Accessibility
It doesn't matter accessibility is in the requirement or not. As developer you should support the accessibility. Every component should be accessible. The important thing here is to define the scope of the Accessibility and cleary mention in the documentation:

1) Keyboard support
2) Text-to-speech
3) Color contrast

### Reusability
Reusability is very important not just for the users but for the developers too.
Whenever you are developing anything keep thinking how it can be reuse not just by user but by developer too.


### CI/CD
[Diagram]

### Consumable Lib
[Diagram]

### Backward compatibility
[Content]

### Test cases
For smaller component you might feel that there is no need of test-cases
but as you move ahead it is important to take TDD.
[Content]

# Guides

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

# Quality
It is very important to maintain the quality of the code. When you have many developers working on one project it is good idea to enforce the code guidelines by using Prettier, CSSLint, JSLint, Formatting. These should be the part of the developers' IDE and to the readme of your design system. (This will gain the confidence of the consumer of DS)

TIP: Make these rules as the part of your build pipeline too.

# Documentation
No matter how good your design system is but if you don't have good documentation no one is going to use it.
As well as bad documentation will also lead to lot of issues in the Github full of queries. Hence, documentation is important.

Documentation is collabration work of UX Designers, UI developers, and UX writers. 

Create a template of documentation and share with the team to fill it - Images, examples, DoS and Donts, description of component, how to use, methods, props guide.

# Patterns or Examples
Build the ready to use patterns from your design system. It will help you to understand the gaps, fix the gaps and understand how easy is DS to use. As well as, these will interest lot of products who want to save the time.

No one is going to come and ask for 'I am looking for checkbox or button' but there is higher chance of developers coming and asking about I am looking 'Filter-able Data grid with pagination'.


# Post Design System
- Release plans
- Defect log
- New Feature Request
- Awarness and advocacy 
- X vs Y - Ask why? and then implement that in your DS.
- Community Building


# Learnings
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



# Dos and Dont's
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

# Where to Host?
You can pick either github or a dedicated website. It is always good to provide the website, the reason is non-tech people such as 
designers, UX writer, product owners can easily go and check the informationa and if you have clients then for them too. 

Website will become the 'Black Book' of your company work culture - UX, UI, Guidelines, the case styuides etc. 


## Thank you very much by reading till end.




