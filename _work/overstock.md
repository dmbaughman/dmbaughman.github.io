---
title: Overstock
order: 1
tags: [React, Redux, Preact, Jest, Enzyme]
images: [overstock-checkout.jpg, overstock-cart.jpg, overstock-login-modal.jpg, overstock-component-library.jpg]
link: https://www.overstock.com
---

My team at Overstock is responsible for the pages at the end of the shopping experience, primarily Login, Cart, Checkout and Order Confirmation.  Most of our applications are built with React + Redux and use server-side rendering to improve the user experience while our pages are loading.  When making improvements or adding new features to our pages, we typically test the changes using A/B or multivariate tests to ensure that the changes achieve the results we are targeting.  This data-driven approach helps us measure the improvements we make to the site and allow us to quantify the benefits of adding or improving features on our team's pages.

One of my proudest accomplishments was replacing a variety of different implementations of the login page with a single modern login application built with Preact.  When I was tasked to make some UI updates to the login page, I discovered that there were a total of 7 different instances of the login page that were used for a variety of different purposes.  Having so much unnecessary redundancy made maintaining these pages overly complicated, so I decided to consolidate everything to a single app where it could be maintained in a central location.  Additionally, the legacy pages were all written with static HTML, CSS, and JS, so they were not in a position to leverage the standardized components that we use across our site.  Updating to a tech stack that was more inline with the rest of our site ensures that the Login experience remains consistent with the rest of the site.

In addition to supporting my core team, I also volunteered to help build and maintain the internal React component library that is used by the front-end teams across the company.  The library was in a neglected state when I joined, and after identifying a variety of problems with lack of consistency and standardization, I helped implement patterns and processes that have helped get the library into a much better state and ensure its longevity long-term.  Some examples of improvements we made to the library include introducing compound components, 100% component test coverage, and implementing standardized documentation.
