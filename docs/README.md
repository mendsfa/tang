---
pageClass: home-page
# some data for the components

name: TANG
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com

cv: https://www.u-aizu.ac.jp/
bio: Student at the University of Aizu
email: mxxxxx@u-aizu.ac.jp
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I attended [the University of Aizu](https://www.u-aizu.ac.jp/en/) to study CS, balabalabala


## Education & Experiences

- **The University of Aizu** <br/>
Oct 2016 - Sept 2020
- **The University of Aizu** <br/>
Mar 2021


## Projects & Publications


[→ Full list](/projects/)

<ProjectCard image="/projects/2.png" hideBorder=true>

  **Project description**

  A project description is a formal document that provides key information about strategic planning and development. Project managers create this document to depict that a project meets business objectives, is financially viable, and is worth investing in.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **吃饭**
  
  吃饭，乃是天大的事。 胖妈说，有个地方，叫“伊登”，那里人人不愁饭吃。东东把“伊登”在心里记挂了许多年，终于背起累赘的行囊，从东到西辛苦地寻找吃饭。她曾以为在美国找到了“伊登”，在那里，吃饭把一家三口紧紧维系。东东的一手好菜抹平了生活的艰辛，也让她见证了吃饭的严酷和残忍。 时光流逝，吃饭从这个家庭的最低需求变成了最高享受，东东却发觉“伊登”依然遥远，在追寻“伊登 ”的几十年里，她找到了吃饭，却丢失了味道——那是家的味道、故乡的味道、小时候的味道。

  [[Link](https://www.google.com)]

</ProjectCard>


## Awards & Honors

### Contests

- haha, **none**.


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
