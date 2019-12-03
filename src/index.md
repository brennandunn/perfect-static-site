---
title: Welcome to RightMessage
layout: default

hero:
  title: Turn random site visitors into highly segmented email subscribers
  description: RightMessage surveys and segments your audience, giving them a more personalized experience that leads to more opt-ins and sales.

cta_funnel:
  headline: Customer journeys, not forms.
  description: Ditch "form overload" in favor of journeys for each visitor, subscriber, and customer.
  direction: left
  features:
    - name: Visually map your journey
      description: A birds eye view of how you're surveying and pitching website visitors
    - name: Subscriber awareness
      description: Ensure returning subscribers never see another opt-in form
    - name: Deep integrations with your email database
      description: Change survey questions or offers based on what you know about visitors
    - name: Unified widgets
      description: Every widget and form on your website will be in harmony
    - name: Enrich your ESP
      description: When visitors are surveyed or key actions are taken on your website, we'll sync that data up to your email database

form_content:
  direction: right
  headline: All the widgets you need (and more!)
  content: >
    Our beautifully designed (and conversion-optimized) widget designs ensure
    that, no matter _how_ you want to get people onto your email list, we've got
    you covered.


    Your RightMessage account includes floating bars, full screen takeovers, exit popups, slide ins, and more.
  testimonial:
    content: >
      RightMessage is a game-changer. By personalizing our offer pages (using data RightMessage helped collect), we were able to add more than $100k in net new revenue to our last big promotion.
    name: Pat Flynn

personalization:
  headline: Personalize your entire site.
  description: "Point-and-click personalize any and all content on your website: headlines, copy, images, and more. Zero coding required."
  direction: right
  features:
    - name: Give each persona their own experience
      description: A birds eye view of how you're surveying and pitching website visitors
    - name: Click-and-change anything on your site
      description: Ensure returning subscribers never see another opt-in form
    - name: Greet visitors by name
      description: Change survey questions or offers based on what you know about visitors
    - name: A/B test
      description: Every widget and form on your website will be in harmony
    - name: Enrich your ESP
      description: When visitors are surveyed or key actions are taken on your website, we'll sync that data up to your email database

works_anywhere:
  direction: left
  headline: RightMessage works on _any_ website
  content: >
    No matter what your website is built in or where you host it, RightMessage works by just adding a single line of JavaScript code to your site's template. While it won't slow down your website, it **will** help you increase conversions and sales.
  testimonial:
    content: >
      For marketers ahead of the curve the challenge up to now has not been *why* to focus on personalization, but *how.*


      RightMessage finally removes the marketer’s biggest barrier to personalization — heavy reliance on an engineering team.
    name: Claire Suellentrop

dashboard:
  headline: Better understand your audience.
  description: "Point-and-click personalize any and all content on your website: headlines, copy, images, and more. Zero coding required."
  direction: left
  features:
    - name: Give each persona their own experience
      description: A birds eye view of how you're surveying and pitching website visitors
    - name: Click-and-change anything on your site
      description: Ensure returning subscribers never see another opt-in form
    - name: Zero impact on load speeds
      description: Change survey questions or offers based on what you know about visitors
    - name: A/B test
      description: Every widget and form on your website will be in harmony
    - name: Enrich your ESP
      description: When visitors are surveyed or key actions are taken on your website, we'll sync that data up to your email database
---

{% include marketing-blocks/hero.html %}

{% include marketing-blocks/use-cases.html %}

{% include marketing-blocks/feature-carousel.html content=page.cta_funnel %}

{% include marketing-blocks/content-and-testimonial.html content=page.form_content %}

{% include marketing-blocks/feature-carousel.html content=page.personalization %}

{% include marketing-blocks/content-and-testimonial.html content=page.works_anywhere %}

{% include marketing-blocks/feature-carousel.html content=page.dashboard %}

{% include marketing-blocks/integrations.html %}
