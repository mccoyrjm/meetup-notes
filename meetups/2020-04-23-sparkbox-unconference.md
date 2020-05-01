# Sparkbox Unconference - April 23, 2020

## Event Details
* Hosted by [Rob Harr](https://robharr.com/) of Sparkbox
* [Eventbrite](https://www.eventbrite.com/e/sparkbox-unconference-tickets-100168119542)
* [Sparkbox Unconference 2020](https://seesparkbox.com/sparkbox_unconference_2020)


# Designing for Design Systems with [Ethan Muller](https://www.linkedin.com/in/ethan-muller-22461852/)

## What is a design system?
* Contains Style Guide and Pattern Library
* A style guide breaks down how things should look.
* A pattern library is a collection of UI chunks that can be put together to make something (ex. sprite sheet for game)
* Otherwise, any other docs it takes to get work done.

## What design systems accomplish?
* Address What and Why

## Creating a design system
Start general.
  1. Typography
  2. Color
  3. Buttons

General concepts are more portable across different platforms.

Invent design units other than components.
* Components are most common, but don't have to be only unit of design.
ex) Skin
```css
skin {
  background-color
  foreground-color
  link-color
}
```

Turn design into development.

# Selling Design Systems with [Ben Callahan](https://www.linkedin.com/in/bencallahan/)
TODO - see recording

## Resources
* [When NOT to use a Design System](https://seesparkbox.com/foundry/when_not_to_use_a_design_system)


# Design Systems
The following 3 talks focus on Design Systems.

# It Takes a Village: Building Organizational Buy-In For Your Design System with [Lina Calin](https://www.linkedin.com/in/lina-calin/)
One of the greatest challenges is building buy-in across teams in an org.

## Why is Buy-In Important?
* Design Systems Fail for people reasons:
  * Lack of executive champion
  * Adoption
  * Staffing
  * Funding
  * Maintenance
* Shows us that we built the right thing.
* Shows us we built the tool the right way.
* Leads us towards a better user experience.

## Steps to Build Investment
1. Document your "why"
    * What existing problems can a design system solve? (Have an   immediate example)
    * What future problems can a design system mitigate?
    * What other benfits can a design system bring?

2. Build Allies
    * Pick someone(s) powerful and influential
    * Pick someone(s) who, with access to a design system, will have a lot of impact
    * Pick someon(s) who can explain the technical benefits

3. Identify Key Stakeholders
    * Not necessarily allies, but affect budget and resources allocated towards efforts

4. Understand the build requirements
    * Any features need to get to integration quicker?
    * Any needs of your allies that should be prioritized?
    * Tech-specific or tech-agnostic?
    * Budget?
    * Urgency?

5. Make a Support Plan
    * Platform & browser support
    * Regular newsletter w/ updates
    * Dedicated Slack channel
    * "Office Hours" w/ support team
    * Versioning
    * Documented process for contribution
    * Regular user surveys

## Real Life Example
University of Georgia - Online Learning

# Accessibility
The following 2 talks focus on Accessibility.

# 5 Ways to Advocate for Accessibility with [Corinne Ling](https://www.linkedin.com/in/corinneling/)
*"Good products are also accessible ones."*

### 1. Add suggestions for accessibility solutions to tasks.
* Comment on cards through your task tracker.
* Developers more likely to fix issue if given feedback.

### 2. Add info on how to manually test with assistive technology
* These tests do **not** replace user testing with actual users with disabilities.

### 3. Offer to pair with someone on accessibility tasks
* If they are focused on main bug fix, pair with them if you notice an accessibility improvement opportunity.

### 4. Demo an accessibility fix
* Get accessibility on the radar for diff people at your company.
* After demo, if someone has Q's that can introduce you two to point #3.

### 5. Don't make "Accessibility" cards
* Mark it as a bug, because it is!
* Cards to make new features? Include accessibility requirements (Points #1 and #2).

## Resources
* [See Sparkbox Accessibility](https://seesparkbox.com/foundry/category/accessibility)
* [Test Color Contrast](https://bit.ly/test-color-contrast)
* [VO Shortcuts](https://bit.ly/vo-shortcuts)
* [NVDA Shortcuts](https://bit.ly/nvda-shortcuts)
* [Keyboard Testing](https://bit.ly/keyboard-testing)

# Understanding Accessibility: WCAG’s 13 Guidelines with [Kasey Bonafacio](https://www.linkedin.com/in/kaseybon/)
A lot of people ask: "How do I know if my website is accessible?"
* Compare against WCAG (current v2.1)

## The Structure
4 Principles
1. Perceivable
2. Operable
3. Understandable
4. Robust

Each principle is broken into Guidelines (13) and Success Criteria (78).

One more layer is **Levels of Conformance** (A, AA, and AAA)
A - Bare minimum level of accessibility
AA - Everything in level A plus a few additional requirements.
AAA - Everything in levels A and AA plus a few additional requirements.

## The Guidelines
### Perceivable
People must be able to find your content.

**1.1 Text Alternatives**
* Image hover text

**1.2 Time-Based Media**
* Subtitles on videos
* Narration on videos)

**1.3 Adaptable**
* Make content obtainable from different screen sizes

**1.4 Distinguishable**
* Contrast ratio (min ratio of 4.5 is accepted, 4.3 for large text)
* Background audio should be 20 decibels quieter than speaking voices

### Operable
TODO

**2.1 Keyboard Accessible**
* Keyboard accessible, tab+enter keys to navigate and activate elements

**2.2 Enough Time**
* Give user ability to start, stop, videos
* Any video that is more than 5s
* Present timer if time limit exists on submitting forms; warn user when an action will take place

**2.3 Seizures and Physical Reactions**
* Animations and video shouldn't flash more than 3 times/s
* ex) Pokemon episode of Pikachu using thunderbolt; caused seizures in 700+ children!

**2.4 Navigable**
* Focus state of element
* Breadcrumb navigation
* Table of Contents

2.5 Input Modalities
* web app works with mouse, touch screen, speech to text

### Understandable
TODO

**3.1 Readable**
* Use simple language and avoid jargon; if necessary, provide definition
* Screen readers
* `<html lang="en">` required to indicate page language
  * If other languages appear on page, you can wrap text is `<span lang="fr"></span>`

**3.2 Predictable**
* In a web app that hosts a lot of articles, the page structure should remain the same (elements remaining where they were on other articles, etc.)

**3.3 Input Assistance**
* Helper text on inputs to assist w/ format
* Validation error labels

### Robust
Your website must work with different technologies.

**4.1 Compatible**
* *"Build websites that work with current and future technologies."*
* Write valid, semantic HTML.
* Use ARIA to *extend* HTML.
* Incorporate accessibility testing into your build process.

## Resources
* [13 Days of Accessibility](http://a11ycalendar.kaseybon.com/)

## Q&A w/ Kasey
"How can I convince my team to care about Accessibility?"
* Scheduling talks
* Coding challenges

"How valuable is it to become IAAP certified and when do you recommend to be certified"
* When clients care about writing accessibility
* Have a base knowledge of Accessibility (Write blog posts, build things) before pursuing.

"Can you give a small overview of how you became certified?"
* Interest in accessibility
* Workshops
* Started preparing for months after learning about IAAP
TODO

"What are some often forgotten areas of inclusive design we can get better at?"
* A lot of people think about screen-reader users, but there's a whole lot more disabilities.
  * Keyboard accessibility
  * Cognitive (design & content will come into play)
  * Associate elements together (ex. learn more links being read out one after the other)

"What's the most annoying accessibility bug you've encountered?"
* Carosuels

"Is automated testing enough to say 'Your website is accessible'?
* No; it'll catch a lot of bugs, but it won't miss the nitty gritty details.
  * won't catch alt-text
  * won't say "your page isn't organized well"
* You need an actual user.

"When building a custom component, what process do you use to discover the specific applicable WCAG Success Criterion and which Techniques you will use to satisfy the identified criterion?"
* We talk about things first.
* W3 guideline has components that are built a lot and what it takes to make them accessible.

"Can you tell us about a positive experience where you had to convince a client to make a change, potentially a more expensive change, in order to make a more accessible product?"
* Navigation bar is a typical culprit
* No specific example comes to mind; explaining different options that are accessible to client is typically a good exp.

"Good tools to use with Accessibility Testing?"
* AXE
* WAVE
TODO

TODO - recommendations for older people

TODO - what other tools can disabled people use?

"Certifications for Designers"
* WAS
* CPAC

Recommended Resources
* [WebAim](https://webaim.org/)
* MDN Docs
* People to follow: Kerry Fisher, Marcy Setzer
TODO





# Putting the “User” in UX with [Julie Young](https://www.linkedin.com/in/juliemyoung/)

## User Interviews and Observations
The goal of user research is...
to not only understand the user better, TODO

## Why haven't you been doing user research?
* Expensive
* Time-consuming
* Difficult
* Been getting by without it

## How to make user research happen at your organization?
* Stop asking for permission.
* Start small. Be scrappy. Anything is better than the current nothing.
* "We always talk to users as part of our process..." - to clients
* "I'm doing some user research. I'm allocating this many hours of my UX budget TODO" - to PMs


## Finding People to Talk To
* Start by asking your client or stakeholder.
* Reach out via email note with incentive.
* Plan B is recruiting users directly w/o client involvement.

## When your user is a typical consumer...
* Ask friends, co-workers if they know anyone
* Post on social media
* TODO

## When your user is specialized...
* Ask client if there's a place online where this population hangs out.
* Cold call, email, DM on LinkedIn, Twitter, etc.
* Meetup.com

## When it's a sensitive subject
* ex) Addiction, mental health, money, sex, etc.
* Build up empathy before approaching

## If you have a $$ to burn
* Online ads LinkedIn, Facebook
* https://userinterviews.com
* Marketing Research and Analytics Firms

## Informed Consent:
Tell the user why you're talking to them, how you're using their information, and get their consent. **ALWAYS.**
* Ask permission for recordings
* Sign a consent form or email trail

## Thank Participants w/ Incentives
* Consumer: $1/min
* Specialized or Sensitive: $50-100, but depends; outweigh potential embarassment of discussion topic
* Captives or fans? Discounts and swag.
* No Budget? Be thankful and respectful.

## Q&A with Julie
"Surveys vs direct conversations?"

# A Project Manager’s Best Friend: The Technical Lead with [Austin Munhofen](https://www.linkedin.com/in/austin-munhofen-43b3b914/)

## What is a Tech Lead?
TODO



# How to Build a Zero-Maintenance Web Application with [Bryan Braun](https://www.linkedin.com/in/bryanbraun/)



## Foundations of Sustainable Software with [Ryan Cromwell](https://www.linkedin.com/in/cromwellryan/)
