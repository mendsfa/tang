---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'TANG'
info: 'Student at the University of Aizu'
interests: 'Interests: Playing games.'
socials:
- title: github
  link: https://github.com
- title: linkedin
  link: https://www.linkedin.com
- title: instagram
  link: https://www.instagram.com
- title: email
  link: 'mailto:xxxxxxxx[at]gmail.com'
actions:
- text: Projects
  link: /projects/
- text: CV
  link: /article/
footer: Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

I attended [the University of Aizu](https://www.u-aizu.ac.jp/en/) to study CS, balabalabala

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>