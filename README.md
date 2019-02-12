# Udemy course: "Building Apps with Third Party Integrations" 

Companion repository for the Udemy course titled "Building Apps with Third Party Integrations", found [here](https://www.udemy.com/building-apps-with-third-party-integrations). This is the finished repository.

For those of you that learn better by hacking at an already-done repo, feel free to clone this!  It will work out of the box with your unmock key, which you can grab by registering at [unmock.io](https://www.unmock.io).

To get started [see below...](#Getting%20Started)

## About the Instructor
Mike Solomon, CEO of Meeshkan Machine Learning, where they use tons of 3rd party integrations in their award-winning app.

## Learning
Hi and welcome to Building Apps with Third Party API Integrations. 

In this course, you’re going to learn how to quickly build a web app that interfaces with third-party services like Behance and Sendgrid in a safe and scalable way.

At the end of this course, you will be able to develop bug-free apps blazingly fast using NextJs, Typescript and  and deploy them with confidence to the web, to Slack, or if you're a React Native developer, to the App Store or Google Play.

In the **first course**, we will explore why third party integrations are so important in the modern app-building landscape.  In the second course, we will set up our IDE, download all of the required dependencies, and survey the services we'll be integrating with.  Then, we will build a skeleton web app in record time thanks to awesome tools like mongo-mock and unmock.

The ideal student for this course is a professional developer or hobbyist that wants to use popular APIs like Facebook or Stripe.  This can be quite challenging because of the lack of control that comes with using 3rd party APIs.  We’re going to help you overcome those challenges, fast, and get you on the path towards building great apps.

Thanks a lot for your interest and I hope you sign up for [this free course](https://www.udemy.com/building-apps-with-third-party-integrations)!

### Content
- Web app development
- Unit testing (ts-jest)
- Using third party APIs
- React
- NextJS
- [unmock.io](https://www.unmock.io)

### Course Requirements
- Be conversant in JavaScript
- Be comfortable with NodeJS
- Have experience developing a website

### Who this course is for
- Intermediate JavaScript developers looking to build better apps with third party API integrations

## Getting started
1) clone repository
2) open command prompt and run `npm install`
3) `npm run build`
4) `npm run start`
5) Open browser to `localhost:3000`
6) `yarn test`, they will fail unless you do the following
  a) **pass** tests by getting unmock **API KEY**
  b) create an unmock account [here](https://www.unmock.io). Try it free for 30 days!
  c) install the unmock API KEY in your application. Read how to do that [here](https://www.unmock.io/docs#installing)
7) Now your tests will pass and you can see the mock data that is returned via unmock.io
