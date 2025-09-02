---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /tzw.jpg
head: 'Zhongwen Tu'
info: 'Communication University of China'
interests: 'Interest:Basketball'
socials:
- title: xintong
  link: https://ices.cuc.edu.cn/2019/0917/c5332a135499/page.htm
- title: linkedin
  link: https://www.linkedin.com
- title: email
  link: 'bytuzhongwen@cuc.edu.cn'
actions:
- text: Projects
  link: /projects/
footer: Made with ♥ by Fing. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

I am currently admitting academic master's students in **Information and Communication Engineering** with a focus on **Intelligent Video Processing**, and professional master's students in **Artificial Intelligence** with a focus on **Intelligent Audio-Visual Technology**.

My primary professional work involves the design, operation, management, and maintenance of studios, audio production rooms, and multimedia systems. My research interests include converged media technologies, speech modeling, and virtual reality. I am the instructor for the course *Introduction to Radio and Television Technology*.	

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)

  .last-updated
    display none

</style>