---
name: 'Simple Countdown'
permalink: '/'
exclude_from_nav: true
style:
  media:
    img:
      url_path: '/img/backgrounds/winter-cabin.jpg'
      pattern: false
      parallax: true
      overlay: 'dark'
      blur: false
  sectioncolor: 'bgclear'
  tint_color:
  stickyfooter: true
  footer_color: '#222'
  blog_link: false

element:
  headline: 'Winter is Coming'
  copy: 'Have you ever built a snowman?  This winter you can stay in our beautiful cabin with enough snow to build a team of snowmen.'
  font_color: '#fff'
  type: 'countdown'
  countdown:
    date: '2017/01/01'
    complete: 'Winter is here!'

action:
  heading: 'Enter your email address to find out as soon as our service is available.'
  subtext: null
  type: 'popupform'
  popupform:
    name: true
    email: true
    optIn: false
    btnText: 'Sign Up'
    btnType: 'warning'
    complete: null

seo:
  title: null
  description: null
  canonical: null
  noindex: false

social:
  title: null
  description: null
  img_path: null

---

{% include section.html location="simple-countdown" %}
