---
layout: 'actionleft'
name: 'Coming Soon'
permalink: '/landers/coming-soon/'
exclude_from_nav: true
style:
  media:
    img:
      url_path: '/img/backgrounds/launch.jpg'
      pattern: false
      parallax: true
      overlay: 'light'
      blur: false
    tint_color: false
  sectioncolor: 'bgclear'
  tint_color: rgba(0,0,0,.2)
  stickyfooter: true
  footer_color: "#fff"

element:
  headline: 'Coming Soon'
  copy: 'We are excited to bring to you an amazing web app in the very near future. '
  type: 'countdown'
  font_color: "#fff"
  countdown:
    date: '2017/01/01'  
    complete: 'Launch Day!'

action:
  heading: 'Be the First to Visit'
  subhead: 'Sign Up for Notification of Site Launch'
  subtext: '* We will not sell your email'
  type: 'form'
  form:
    email: true
    optIn: true
    btnText: 'Notify Me'
    btnType: 'success'
    complete: 'Thank You! An email confirmation should be arriving soon.'

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
