<div align="center">
  <img height="200" src="./LOGO.png"> 
  <h1>You Don't Know UI</h1>
  <h3>You don't need to be a 10X designer to create universal user interfaces</h3>

---

<span>Inspired by [KYLE SIMPSON](https://github.com/getify)'s book [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS), I decided to create [You Don't Know UI](https://github.com/You-Dont-Know-UI) which is a DESIGN PRO TIPS dedicated for developers to learn, discuss, contribute together and share the best practices about designing user interfaces.

Back to 2017, I started to spent my spare time to learn in-depth about Web Design, Mobile Design, Animation, Micro-Interaction, User Experience and Design Systems by reading several books and articles such as [Refactoring UI](https://refactoringui.com/) by [Adam Wathan](https://github.com/adamwathan) & [Steve Shoger](https://www.steveschoger.com/), [Invision Design System Handbook](https://www.designbetter.co/design-systems-handbook), [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) by [Brad Frod](https://github.com/bradfrost), [Airbnb Design System](https://github.com/airbnb), asking questions on [User Experience Platform](https://ux.stackexchange.com/), and sharing my personal [prototypes](https://www.behance.net/menaialaeddine) on Behance. Also, I started sharing these Tips 2 months ago on [Linkedin](https://www.linkedin.com/in/alaedddine/) but they are not professional and more detailed like here.


From basic to advanced: test how well your UI is modern, consistent, universal, and accessible, refresh your workflow a bit, or enhance the product you're working on! :muscle: :rocket: I update this repo regularly with new PRO TIPS. I added examples to make the explanations more tangible. good luck! :heart:</span>

</div>

--- 

<details><summary><b>1. Think in a feature, not a layout</b></summary>
<p>

I've wasted months not just days trying to create an MVP ( Minimal  Viable Product ) for an idea. I spent nights and nights refactoring the user interfaces by changing just the places of the components and the layouts. Don't be stupid like me!

When you start designing a new user interface for a web or mobile application, most of the time you think about the **structure** or the **position** of your components, so you start designing the Header or the Top Navigation as your first component in your UI. Me too I was doing this mistake!

<img src="./assets/PRO_TIP_1_3.svg" width="100%"/>

Do you know why it's a mistake? Because you're limiting yourself from the beginning. Because you're seeing the App Design from Top-To-Down or Down-To-Top while the App Design is a **collection of features**. You're not building a house here using LEGO bricks! But you're building a car and you can start designing the engine or the wheels, right?

Most of the folks try to _copy & paste_ from popular websites and apps, without knowing the Standards or the Design Decisions for each product. This is the easiest way to find themselves _frustrated_, _limited_ and they figure out that they overthink only on _Generic Things_.

They focus on the _shape_ of their app but not the _core features_, and they start asking frequently these questions :

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Where should I put the Logo?</i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   How many items should I have in the navigation bar? </i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Should I have one or two sidebars?</i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Should I have a Grid Layout or a Table of items?</i>

<img src="./assets/PRO_TIP_1_1.svg" width="100%"/>

But, what you don't know ( maybe ) is UI Components are made to solve certain problems that's related to _user interaction_, _data displaying_ or _new device screen invention_, and you may be noticed that _Humburger_ element is started to be well-known in mobile devices.
 
Obviously, we are not designing user interfaces but we are designing and implementing features, and Top Navigation is just a _common feature_ that helps users to do quick navigation for certain and most important pages.

So, don't care about common features or what I call them _Generic features_ or _layouts_.

Instead of starting by a _layout_, start with a _feature_ or a _specific functionality_ , and not any _feature_ but the _core feature_ in your product.

Let's say you'll build the next-gen social media app for sharing videos. You could start with this **core feature** : Share a short-form video.

The UI will need :

<i><img src="./icons/icons8_checkmark_24px.png" width="16px"/>   Field for upload a video</i>

<i><img src="./icons/icons8_checkmark_24px.png" width="16px"/>   Field for the caption</i>

<i><img src="./icons/icons8_checkmark_24px.png" width="16px"/>   Field for the description</i>

<i><img src="./icons/icons8_checkmark_24px.png" width="16px"/>   Button for posting or sharing</i>

<i><img src="./icons/icons8_checkmark_24px.png" width="16px"/>   Button for saving in draft</i>

These are the requirements to design your UI.


<img src="./assets/PRO_TIP_1_2.svg" width="100%"/>

[Edit →](https://github.com/MenaiAla/You-Dont-Know-UI/pulls)

</p>
</details>

---

<details><summary><b>2. Design few, Implement few, Repeat</b></summary>
<p>

I have this question for you:

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Why do you need to design perfect UI with all details then implement it?</i>

I have another question for you:


<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Did you feel frustrated in the stage of implementation of a new feature because the design does not take programming limits in consideration?</i>

My last question is:

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Why do you focus on details in the early stage of the design?</i>

Ha! I know you're thinking in Agile but you're working with the Waterfall approach.

Indeed, people get confused when they switch from task to other per day even in the same domain, it happened to me usually, especially when it comes to designing different concepts of user interfaces per day.

Furthermore, people want to start a thing and finish it once time. They want to make it perfect from the beginning! Even with **low resource** and in **limited time**. It happens most of the time in early-stage **startups**.

So, let me tell you something: **Details do not matter when you start from scratch.**

The hard thing about the design is when someone asks you: Why you take this decision?

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Why you chose this palette of colors?</i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Why you chose this typface?</i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Why you chose this style of icons?</i>

If you have not a Design System in place, creating **consistent** user interfaces is very hard, and focusing in-depth on **details**, will lose **time**, **effort**, and of course the **consistency** of your user interfaces.

<img src="./assets/PRO_TIP_2_1.svg"/>

So, what's the solution here?

As I mentioned in the title: **Design few, Implement few, Repeat.**

In the earliest stage of the new design or new feature, you don't need to stick on the **high-level** decisions about the foundation of your design ( Spacing, Color, Typography, Iconography). I know they matter but not in the beginning, right?

Let's say, when you were having a shower you came up with an idea for a new killer feature, and you want to make it more tangible for your teammates and the stakeholders to get buy-in. Adding new features means a new investment of money and time and what's matter later for any company is: **Revenue**.

The first thing, you need to do is ignore all details ( nice-to-have ) and just focus on the requirements ( must-to-have ).

So, I recommend this workflow to get quick both of **internal** and **external** feedback:

<img src="./icons/icons8_1_key_24px.png" width="16px"/>  Create hand-drawn version.

<img src="./assets/PRO_TIP_2_2.svg"/>

As you see here, there are zero details about your user interface in production, but why this step matters?

This hand-drawn activity may take between 5min and 20mins if you want to make it **high-fidelity** draw! 

In fact, this step will help you to see other teammates and stakeholder's opinions and gather  **individual recommendations** from each member in your team. People could not recommend changes when they see a well-done thing. But they can tell you how can you make it better when you deliver it **clean** but **uncomplete** and **ugly**. It's human nature.


<img src="./icons/icons8_2_key_24px.png" width="16px"/>   Ignore colors.

<img src="./assets/PRO_TIP_2_3.svg"/>

When I was a kid, I remember my Dad when he was buying a paint book for me. The content was grayscale images and my mission was to colorize these images using wood colors. Sometimes, I and my friend have the same image but when we colorize we end up with different looks! After that, we go to family members and ask them which one is better.

But how can we adopt this workflow in our design?

The idea is to **hold the color** even if you'll refine your design in higher fidelity. Let people tell you how are the **shapes**, **sizes**, **spaces** and the **position** of your elements.

<img src="./icons/icons8_3_key_24px.png" width="16px"/>  Implement the UI.

Modern frameworks and libraries such as [Vue](https://vuejs.org/), [React](https://reactjs.org/) and [Svelte](https://svelte.dev/) were created for **Rapid Prototyping** which means you can implement one component and use it with **different looks** in **different positions**. So, you don't need to have a **full prototype** with all user interfaces to start the implementation.

It's a little bit challenging, but I can say that you don't need to regret the time you spent for designing **perfect UI** that you'll never see it on production.

The goal of this step is to test the **back functionality** ( How it works ) of the UI without sticking on how it looks for users.

<img src="./icons/icons8_4_key_24px.png" width="16px"/>  Colorize.

If you don't have a color palette in place, you can try several colors and see the consistency between them based on color theory rules.


<img src="./assets/PRO_TIP_1_2.svg"/>


<img src="./icons/icons8_5_key_24px.png" width="16px"/>  Repeat.

Our purpose here is to prevent the **over investing** and moving fast by doing **parallel iterations** on both design and code in **short time**, so you can build real thing as soon as possible. In the end, what matters is your UI in production.


<img src="./assets/PRO_TIP_2_4.svg"/>

[Edit →](https://github.com/MenaiAla/You-Dont-Know-UI/pulls)

</p>
</details>

---

<details><summary><b>3. Less is More</b></summary>
<p>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>   Which option will delight the users?</i>

This is the frequent question I ask myself in my work basis. Hope I'm not the only one!

Designers and engineers waste more time on details and minor decisions in the early stage of designing and implementing new UI but they should realize that designing UI is an **iterative process**. In fact, it's better for you to not stick on minor details in the early stage of any task. You don't want to hear from me how many hours or maybe days I spent changing the font size by adding or reducing **1px**.

<img src="./assets/PRO_TIP_3_1.svg"/> 


<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>  Do you think that users will notice these changes?</i>

<i> <img src="./icons/icons8_confusion_24px.png" width="16px"/>  Do you think that adding 1px will add more revenue to the company?</i>

Please, don't waste your time on these changes in the early-stage.

From [Speed Dating Decision Making – Why Less Is More:](http://www.scientificamerican.com/article.cfm?id=speed-dating-decision-making-why-less-is-more)

Yet new research does point out a different dating problem: being confronted with a **large number of choices can make it harder to make a good decision**. In fact, it can even prevent you from making a decision in the first place.

When you're designing without constraints, your process will be very slow, and you will never end up with a choice. Let me clarify with this example:


<img src="./assets/PRO_TIP_3_2.svg"/> 

As you see in the above image, the first scenario is for a buyer who wants to choose a flower for his wife but he's seeing flowers with different colors and they are almost similar which makes the decision so hard for him. The second scenario is for a designer who gets confused between these buttons where it's almost to see the difference between their background colors.

The fact is when there were **too many choices** people became confused and didn’t make a choice when there were too many options. People that had few options chose more often and were happier with their selection. So, you need to stick this rule in your head: **Limit your choices**.

So how can we limit our choices for our user interfaces?


<img src="./icons/icons8_1_key_24px.png" width="16px"/>  Systematize colors:

When I was a student, I remember when we were working on the design of the website with my teammate, and because we had not a system for the colors, we were picking a color randomly each time from the color picker and we see how the color looks in the UI. But after I discovered and read [Material Design](https://material.io/), I figure out how companies choose their colors.

So, instead of hand-picking values randomly, create your palette from the beginning, there are dozens of online generators that can help you to make your decision. You can choose from 6-8 shades and expand when you need more colors.

<img src="./assets/PRO_TIP_3_3.svg"/> 

<img src="./icons/icons8_2_key_24px.png" width="16px"/>  Choose one or two font families:

It's hard to achieve consistency in UI and most of the time **over designing** is the reason behind losing it.

Having more than two font families will make your brand less-memorable like the logo and the content becomes more inconsistent for the reader. Obviously, choosing the font family is very hard in the early stage and my recommendation is **to choose the one that fits the personality of the product.**


<img src="./icons/icons8_3_key_24px.png" width="16px"/>  Systematize font size:

Similarly, don't do what I was doing by adding or reducing 1px until it looks perfect. You may waste 2 hours without taking a decision. Instead, create a stylesheet for your typescale in advance.


<img src="./assets/PRO_TIP_3_4.svg"/>


<img src="./icons/icons8_4_key_24px.png" width="16px"/>  Systematize icon sizes:

Defining a system for the sizes of the icons in advance will save you time later.

For example, you can constraint yourself by 4-based or 6-based scale. Your options will be :

12px, 16px, 20px, 24px, 36px, 48px, 64px.


<img src="./assets/PRO_TIP_3_5.svg"/>


<img src="./icons/icons8_5_key_24px.png" width="16px"/>  Sytematize opacity values:

Opacity values confuse me a lot because it's so hard to see the difference between them.

Personnally, I choose a 5-based opacity-scale and I limit myself by 4 values:

12.5%, 25%, 50%, 75%.

In CSS3, this is equivalent to:

 ```css
    opacity:0.125;
    opacity:0.25;
    opacity:0.5;
    opacity:0.75;
 ```


<img src="./assets/PRO_TIP_3_6.svg"/>

Having some choice is better than having no choice at all. But there is a limit. As it turns out, having more choices isn’t always a good thing.

[Edit →](https://github.com/MenaiAla/You-Dont-Know-UI/pulls)

</p>
</details>

---
