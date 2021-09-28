# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

  - [Useful resources](#useful-resources)

- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](images/Mobile.PNG)
![](images/Desktop.PNG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<section>
  <div class="wrap">
    <div class="grid-container">
      <div class="box1">
        <div class="box-wrap">
          <div class="box-header">
            <img src="images/image-daniel.jpg" alt="user-face" class="avatar" />
            <div class="name-graduate">
              <p class="name">Daniel Clifford</p>
              <p class="graduate">Verified Graduate</p>
            </div>
          </div>
          <div class="box-content">
            <p class="main">
              I received a job offer mid-course, and the subjects I learned were
              current, if not more so, in the company I joined. I honestly feel
              I got every penny’s worth.
            </p>
            <p class="sub">
              “ I was an EMT for many years before I joined the bootcamp. I’ve
              been looking to make a transition and have heard some people who
              had an amazing experience here. I signed up for the free intro
              course and found it incredibly fun! I enrolled shortly thereafter.
              The next 12 weeks was the best - and most grueling - time of my
              life. Since completing the course, I’ve successfully switched
              careers, working as a Software Engineer at a VR startup. ”
            </p>
          </div>
        </div>
      </div>
      <div class="box2">
        <div class="box-wrap small-wrap">
          <div class="box-header">
            <img
              src="images/image-jonathan.jpg"
              alt="user-face"
              class="avatar"
            />
            <div class="name-graduate">
              <p class="name">Jonathan Walters</p>
              <p class="graduate">Verified Graduate</p>
            </div>
          </div>
          <div class="box-content">
            <p class="main">
              The team was very supportive and kept me motivated
            </p>
            <p class="sub small-sub">
              “ I started as a total newbie with virtually no coding skills. I
              now work as a mobile engineer for a big company. This was one of
              the best investments I’ve made in myself. ”
            </p>
          </div>
        </div>
      </div>
      <div class="box3">
        <div class="box-wrap small-wrap">
          <div class="box-header">
            <img
              src="images/image-jeanette.jpg"
              alt="user-face"
              class="avatar"
            />
            <div class="name-graduate">
              <p class="name">Jeanette Harmon</p>
              <p class="graduate">Verified Graduate</p>
            </div>
          </div>
          <div class="box-content">
            <p class="main">
              An overall wonderful<br />
              and rewarding<br />
              experience
            </p>
            <p class="sub small-sub">
              “ Thank you for the wonderful experience! I now have a job I
              really enjoy, and make a good living while doing something I love.
              ”
            </p>
          </div>
        </div>
      </div>
      <div class="box4">
        <div class="box-wrap">
          <div class="box-header">
            <img
              src="images/image-patrick.jpg"
              alt="user-face"
              class="avatar"
            />
            <div class="name-graduate">
              <p class="name">Patrick Abrams</p>
              <p class="graduate">Verified Graduate</p>
            </div>
          </div>
          <div class="box-content">
            <p class="main">
              Awesome teaching support from TAs who did the bootcamp themselves.
              Getting guidance from them and learning from their experiences was
              easy.
            </p>
            <p class="sub">
              “ The staff seem genuinely concerned about my progress which I
              find really refreshing. The program gave me the confidence
              necessary to be able to go out in the world and present myself as
              a capable junior developer. The standard is above the rest. You
              will get the personal attention you need from an incredible
              community of smart and amazing people. ”
            </p>
          </div>
        </div>
      </div>
      <div class="box5">
        <div class="box-wrap small-wrap">
          <div class="box-header">
            <img src="images/image-kira.jpg" alt="user-face" class="avatar" />
            <div class="name-graduate">
              <p class="name">Kira Whittle</p>
              <p class="graduate">Verified Graduate</p>
            </div>
          </div>
          <div class="box-content">
            <p class="main">
              Such a life-changing experience. Highly recommended!
            </p>
            <p class="sub">
              “ Before joining the bootcamp, I’ve never written a line of code.
              I needed some structure from professionals who can help me learn
              programming step by step. I was encouraged to enroll by a former
              student of theirs who can only say wonderful things about the
              program. The entire curriculum and staff did not disappoint. They
              were very hands-on and I never had to wait long for assistance.
              The agile team project, in particular, was outstanding. It took my
              learning to the next level in a way that no tutorial could ever
              have. In fact, I’ve often referred to it during interviews as an
              example of my developent experience. It certainly helped me land a
              job as a full-stack developer after receiving multiple offers.
              100% recommend! ”
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by <a href="#">Your Name Here</a>.
    </div>
  </div>
</section>
```

```css
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto 20%;
  grid-template-rows: auto auto;
  grid-column-gap: 3%;
  grid-row-gap: 6%;
  grid-template-areas:
    "box1 box1 box2 box5"
    "box3 box4 box4 box5";
  align-content: center;
}
```

```js
  no js use
```

### Useful resources

- [Stackoverflow](https://stackoverflow.com/) - The easiest way to find answer to your problem

## Author

- Website - [TrnLinh](https://trnlinh.github.io/Portfolio.github.io/)
- Frontend Mentor - [@TrnLinh](https://www.frontendmentor.io/profile/TrnLinh)
