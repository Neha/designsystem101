# :star: Design System 101 :star:
Are you planning to develop a Design System or just curious to know what a Design System is? 
If yes, then here is a detailed guide for you. No matter who you are - a designer, developer, 
product owner, UX Writer, tester, etc. this guide has something for everyone.

# :thumbsup: Why this guide?
For the last few months, I am working on a Design System at my workplace. There were challenges and a lot of learnings too. I was sharing my experience on social media about it. Many people showed their interest in it. Hence, I have documented my learnings on the Design System.

## :bulb: Key Terms: :bulb:
- Presentational and Functional Components
- Open and close components or Flexible or non-flexible components
- Namespacing - CSS and React
- Performance Metrics
- Your Design System's terminology guide
- Your Design System's rules and scopes
- 360 degree consistency (from style to documentation)

## :green_book: TOC:
- [What is a Design System?](https://github.com/Neha/designsystemtemp#what-is-a-design-system)
- Why you need a Design System?
- [Why to and not to use 3rd party Design System?](https://github.com/Neha/designsystemtemp#why-to-and-not-to-use-available-a-design-system)
- [How to Start?](https://github.com/Neha/designsystemtemp#how-to-start)
- [How to define the scope of the Design System](https://github.com/Neha/designsystemtemp#how-to-define-the-scope-of-the-design-system)
- [Role of team members in Design System](https://github.com/Neha/designsystemtemp#role-of-team-members)
- Pre Design System guide for the team
- [Post Design system:](https://github.com/Neha/designsystemtemp#post-design-system)
     - Release plans
     - Maintenance
     - Evangelism (Community Building)
     - Collaboration
     - Metrics of the DS - use, etc.
     - Lifecycle of a Design system
     - Team plan for the scalability
     - What is successful DS - KPI (Key Performance Indicators - survey - speed, quality, ease of contributions and completeness)
- [Learnings](https://github.com/Neha/designsystemtemp#learnings)
- [Do's and Don'ts](https://github.com/Neha/designsystemtemp#dos--for-developers)
- [Portal and playground](https://github.com/Neha/designsystemtemp#storybook)

## What is a Design System?
A single source of the truth for the designers, developers, and the products.

## Why you need a a Design System?
Design system is not a new thing. These are here for decades. Thanks to our very complex UI and UX as well as rapidly changing technology. Companies are moving towards the Design System to also make sure that :

1) Brand guidelines of the organization are followed by every product and project of the organization.
2) Code Guidelines of the organization should be followed by every product and project within the organization.
3) Designers and engineers can focus on more important and creative work rather than just doing the same task again.
4) Remove the redundant tasks.

## Why to and not to use available a Design System?
Right now we have a lot of options available in the market of the ready-to-use design system. There are 3 options:

1) Use the existing ones such as ReactUI, MaterialU, etc.
2) Use the existing as the base and above that build your new component and theme
3) Make 100% your own from scratch

| 3rd Party      | Make your own |
| ----------- | ----------- |
| If you don't have time. Go for it      | If you have time for development go for it       |
| Already tested, used by many folks. Hence, safe to use   | You need to do everything by yourself        |
| Already a community is there to help you 
if you stuck somewhere   | You need to do everything by yourself        |
| UX, Documentation, security, accessibility, testing etc, has been taken care already and own by someone else. | You need to do everything by yourself        |
| You have less control as you will be dependent on the owner | 100% control you have       |
| If there is a known bug then you need to wait until it is fixed and merged by the owner | 100% control you have       |
## How to start?
This is the most important question for everyone new to the design system. **If you will Google Design System guide - the result you will get is what design system is, what it has, etc. but no one explains - "How to start a design system"** from a UX, UI, Product Lead , or tester perspective. Here is the process which I have followed and you can follow too:

> For Developers: "Do not start with the code."
> For Designers: "Do not start with the design."

The most important task is to understand clearly about:

1) The scope of the design system
2) Problems you are trying to solve by Design System
3) Requirements of the organization

But how to start to do this?

**1. Audit**

If you are not sure of the product or design decisions then the first step should be to meet the products and project teams.

Have a look at the existing product's UX, UI, tech-stack, pain areas, etc. Make notes from every product and try to look for common components, patterns, colors, etc.

**2. Survey**

If meeting the team is not possible, then do the internal survey. Ask about what kind of design system they would like to use? What makes them use a design system? etc.

These 2 steps going to help you to understand your organization's current product/project's current situation on the UX, UI, Design system, etc. Most importantly to make them aware of the design system and why it is important.


_Once you have the list of the common components, patterns, etc. Now, is the time for the UX team to look into defining the scope. Remember you cannot have every component in the Design system. Why? because the reason for the design system to have  'reusable' components. The reusable components should be used by more than at least 2 products. Otherwise, every product/project will keep pushing their work on the design system team as well as extra components will make the design system heavier._

**3. Scope**

Defining the scope of the DS is very important from the UX and UI. You should decide what all your DS should have from UX - style guide, color palettes, design files, design specs, responsive, breakpoints, Dos and Don'ts, which all components, etc. From UI, think about the tech stack, repos, architecture, etc.

**4. Tech stack**

For developers, this is the most important decision to make. If your company is using only 1 lib/framework then there is no decision to make. Otherwise, do good research of the industry and make a list of the available options and their pros and cons. 

Few things which will help in making decisions are:

-  Community support
-  Learning curve
-  Stable version
-  Team skills

> Summary:

> 1. Met your product/project teams and got an insight into the UX, UI, etc.
> 2. Have the scope of the DS : what all we are going to have from UX and UI.
> 3. List of all components to be in the DS
> 4. Tech Stack for the development

---

# Role of Team Members:

Every project team has: UX, UI Developer, Tester,  Product Manager (optional). Everyone plays role in building the design system. Here is the guide for designers (UX) and developers:

### :art: **UX (Designers)**

As a desginers of Design system you should have the list of the following:

1) Colors 

Which all colors your design system will have? Primary colors, Alert colors, secondary color etc. Make sure that these colors are passing the contrast ratio.

2) Type scale

What would be the type scale of the typography of your design system? There should be a minimum font-size your design system should have. Decide on the Typescale - will there be fixed type sizes or user can have any.

3) Spacing 

what would be the spacing (padding and margin) guide your design system will have? For example, can the user decide the space (margin) between the elements or there will be some pre-decided space-numbers (classes) the user needs to pick from? The same goes with padding. To have consistency better to have the fixed space scale.

4) Responsive

It is very important to have a responsive design system. "Why?" I will ask - "Why not"?. This is the mobile and tabs era. Every component in your design system should be responsive by default. As a designer decide the breakpoints your design system is going to support (your design audit will help you here). Once the breakpoints are decided. Start thinking about the behavior of the components on the responsive state. Components behavior can be handle component by component but few things you need to close initially:

1. Will the font-size will change in responsive?

2. What will be the UX of the touch screen?

3. How the active, focus, etc state will be on the touch screen?


5) Progressive enhancement & Browsers

This would be the collaboration work of the UX, UI, etc. To decide the browsers and devices your design system is going to support. As a designer, you need to involve in this decision as devs will keep you updated on the limitations of the version of the browser. Eg: a particular property will work on all browsers or not? and as a designer, you need to decide to keep such a design or not. As well as, do we have progressive enhancement or graceful degradation.


6) Micro-interactions

Micro-interactions are very important. This is the part of the UX which engages the users. Sadly, this is the section that is most ignorant too. Micro-interactions are the small animations, effects, UX very interaction of the user with the component will have. As a designer Micro-interactions define the UX of interacting with any components. Such as on hover on a button what all property will change and how they will change, in design system on closing any open element - how it is going to close - with transition or fade, etc. These micro-interactions should be global and consistent throughout your design system. Few interactions are:

.hover

.active

.select

.delete

.open 

.close

.scroll

.drag

.drop

.errors

.notifications

- UX Guide

A lot of non-designer folks will be using your design system and it is an opportunity for UX to advocate the non-UX folks about the UX guidelines. Give the UX guide with every component such as:

1. When to use this component?
2. Where to use this component?
3. What are the things that need to take care of to have the best UX for users.

Eg: When to use the button and when to use the anchor tag.

7) Error stages

Sadly there is no component in the error stage. hence as a designer you need to make sure you will define the style of the error or notification states such as error, alert, success, etc. Again there needs to define global and should be consistent too.

8) Design Kit for scalability

To gain the trust of your users as well as to have the collaboration. Open all your design kits for the users.

9) Styleguide

Styleguide is the summary of the Design system's UX decision. Always have a styleguide, this will help the users to look into the design system's UI and UX in one go.

10) Design tokens

11) Decide Flexibility vs consistency

12) Themes
### :computer: **Developers**

**1. Tech stack**

This is the first step to decide on which tech stack you will be building your design system. There are many options available. As well, from the audit or meeting to the products/project teams you can get the idea of which tech stack to follow. If you need to decide the tech stack for the design system considers the following points:

. Team skills

. Migration

. Learning curve

. Browser and OS support

. Open issues

and few more...

. Vanilla

. Reactjs

. Angular

. Vuejs

. Web components

. Stencils

**2. Architecture**

Once the tech-stack is finalized, the next step is to work on the architecture of the design system. This is important because before sharing with your rest of the development team and starting coding you have the base ready. While working on the architecture you need to also consider scalability, where the styling would be, where the utlis will be, etc.

The architecture of your DS will depend upon the tech-stack you have picked. One needs to get into the depth of the tech-stack he/she has picked to design a good architecture. The building blocks of the DS are HTML(view), styling, Utilities, and components. Make sure that you are thinking about scaling and reusability around these when you are designing your DS.

One can pick SCSS solution over CSS-in-JS if one wants to reuse the styling as lib.
Please check here the things to consider for styling:

1) Vanilla
2) React
3) Angular
4) Vue

**3. Environments**

A design system is a team effort and requires the team to work in collaboration. As well as, we know the importance of creating different environments from dev, QA, UAT (Staging), to Prod. 

As a team think about the environment and how the build process will work

. dev

. QA 

. staging 

. prod

**4. CI/CD**

Next thing is to look into the CI/CD process. Try to do automation of every task and especially of the builds. 

You need to work on the pipelines and what all tasks will it do.


Now, you got the components to design from the designer. Your next steps should be:

1. The look and feel is from CSS hence decide are you using some lib, CSS-in-js solution
2. Design token - create the design token files
3. Create your first component
4. Test pipelines and TDD 
5. Tech documentation
6. consumable build
7. Release for QA - playground, and repos
8. Examples 


**CODE:**
- sample components template
- Guidelines
- Namespacing
- Unit testing
- Reusability
- PR guidelines
- Accessibility
- type checking

It doesn't matter accessibility is the requirement or not. As a developer, you should support accessibility. Every component should be accessible. The important thing here is to define the scope of the Accessibility and clearly mention in the documentation: Keyboard support, Text-to-speech, Color contrast

**Guides**
As a Deisgn system developer below points to be consider:
### CSS Guide
- BEM or not?
- Modules - SCSS or utility classes?
- Namespace
- Naming convention
- Breakpoints
- Colors
- Font-family
- Typescale

### Markup
- Semantic
- Avoid a lot of code
- Markup with classname should not be tightly coupled
- Closed vs open Markup
- Data-attributes

### Javascript
- How to initialize
- Repaint vs reflow
- Memory leaks
- Data-attributes vs classname/ID
- Dynamic Binding
- Event delegation + binding

### React
- Separation simple to complex
- props: required, default, validation
- Flexibility vs consistency
- JS event lib or React State?
- children, HOC, etc.
- Playground to play with components states and propos
- TDD
- Accessibility
- Naming convention
- Folder structure

## Reusability
- Styling
- Markup
- Methods and props names
- Documentation template
- Global Methods
- CSS Styling
- Design Kit
- Styleguide
- Decide between flexibility vs consistency
- Components within components
- Modules - SCSS 

# :clipboard: Product Managers
Product managers should be providing the requirement of the design system. PM should create the stories in JIRA with clear acceptance criteria.

# :pencil: UX Writers
UX writers are important to help in the documentation of the design system

# :mag_right: Testers
The tester should be involved from the 0-day and is responsible for testing the components in isolation as well as by building the applications.

# How to define the scope of the Design System.
It is important to define the scope of the components and design system. Scope means: what is NOT INCLUDED.
It is important to put examples and patterns to show this as well as your design system introduction should have that what you are offering example: theming components, UI interactions components, or graphical components.

### Component's Requirement and list
Provide the list of the component which are production-ready, work-in-progress, and under discussion.
[Diagram]

### Test cases
Test-cases are very important as a developer you can agree. In design system, test-cases are the most important part to create trust in the open-source community as well as pitch the users.

If you are using React then Jest and Enzyme are the most commonly used ones or you can use whichever testing library you and your team are confident. 

# Quality
It is very important to maintain the quality of the code. When you have many developers working on one project it is good idea to enforce the code guidelines by using Prettier, CSSLint, JSLint, Formatting packages. These should be the part of the developers' IDE and the readme of your design system. (This will gain the confidence of the consumer of DS)

> TIP: Make these rules as the part of your build pipeline too.

# Documentation
No matter how good your design system is but if you don't have good documentation no one is going to use it.
As well as bad documentation will also lead to a lot of issues in Github full of queries. Hence, documentation is important.

Documentation is the collaboration work of UX Designers, UI developers, and UX writers. 

Create a template of documentation and share it with the team to release it with every component or use any automated tool* to create documentation:  

- Description of component

- Images

- Examples

- Do's and Dont's

- How to use: methods, props guide.

# Patterns or Examples
Build the ready-to-use patterns from your design system. It will help you to understand the gaps, fix the gaps, and understand how easy is DS to use. As well as, these will interest a lot of products who want to save time.

No one is going to come and ask for 'I am looking for checkbox or button' but there is a higher chance of developers coming and asking about I am looking 'Filter-able Data grid with pagination.

# Post Design System
Once the design system is ready the job of the design system team doesn't end here. Now, the team needs to work on the new areas. 

**My Advice: Consider the below questions while you are starting your design system to avoid last-minute surprises**

**- Release plans**
How soon the team will release the new version of components? or the big fixes etc. How the communication will be done?

**- Defect log**
Where the users can log the defects? How the priorities will be decided? 

**- New Feature Request**
Where the users can request the new feature?

**- Awareness and advocacy**
What is your plan for creating awareness about your design system and how you are going to advocate to the teams how and why to use your design system?

**- X vs Y**
Ask why? and then implement that in your DS. Keep checking other design systems and look for your USP and their USP. 

**- Metrics**
Work on getting the analytics of the design system by using analytics which components are getting used and which are not? How many users are we having? etc. This will help you to track DS's success and improvement. 

**- Lifecycle of a Design system**
Have a plan and communicate clearly when the new version is getting deprecated or which component is. When the new version is coming and if there are breaking changes then what are those?

**- Team plan for the scalability**
As DSM (design system manager) you should work on the team structure - how many will work on new features and how many on bugs.

**- What is successful DS**
KPI (Key Performance Indicators - survey - speed, quality, ease of contributions and completeness): Work on preparing metrics to show how you are defining the success of your design system.

# Learnings
Below are learning from my experience while working on the design system:

- Migration is tough
- Every product is a new case study
- You need to taste your own medicine
- UX always take priority
- Defining the scope is important of design system and component(s)
- Patterns are very important
- Start always from the small
- You should not add a component in your DS coz X product is asking
- To gain the trust about DS talk about how we are checking the quality and maintaining the testing, as well as the build process, release plans, etc.  



# Do's  for Developers
- Start from small
- Think about reusability
- Always consider the flexibility from user's POV
- Create the scope of the DS and components
- Have consistency in units, spacing, colors, etc.
- Use React children
- Namespacing - class name as well as props
- Props validations
- Closed vs open components

# :exclamation: Dont's for Developers :exclamation:
Do not release without documentation


# Where to Host?
You can pick either GitHub or a dedicated website. It is always good to provide the website, the reason is non-tech people such as designers, UX writers, product owners can easily go and check the information, and if you have clients then for them too. 

Website will become the 'Black Book' of your company work culture - UX, UI, Guidelines, the case studies, etc. 
# Storybook
It is important to provide a playground such as storybook for the users to see how the component will look and how many different types design system has. This is super helpful and popular between the tech and non-tech folks reason is they can take the feel of the design system without installing anything.


## Thank you very much for reading till the end.




