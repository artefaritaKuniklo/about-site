---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: One Among Us
  text: 那些秋叶
  tagline: 非营利组织，促进东亚和海外跨性别的交流互助。
  image: https://www.one-among.us/favicon-large.png
  actions:
    #- theme: brand
    #  text: Markdown Examples
    #  link: /markdown-examples
    #- theme: alt
    #  text: API Examples
    #  link: /api-examples
    - theme: brand
      text: 文章
      link: /zh-Hans/posts
    - theme: alt
      text: 链接
      link: /zh-Hans/links
    - theme: alt
      text: 联系方式
      link: /zh-Hans/contact
    - theme: brand
      text: 支持我们
      link: https://github.com/sponsors/one-among-us/

features:
  - icon: <img src="https://www.one-among.us/favicon-large.png" style="padding:8px;">
    title: 那些秋叶 One Among Us
    details: 去世跨性别者及友跨人士的纪念网站。
    link: https://one-among.us
  - icon: <img src="https://oau.edu.kg/logo.png">
    title: Trans in Academia! 跨性别学术小组
    details: 交流与跨性别有关的学术动态，帮助跨性别者及友跨人士求学、进修、工作，以跨性别学术人的视角发声。
    link: https://oau.edu.kg
  - title: 'Arts Among Us'
    details: 关于跨性别和酷儿艺术的线上展览馆，筹建中。
  - icon: <img src="https://oau.edu.kg/rxn-logo.jpg" style="mix-blend-mode:multiply;">
    title: 在地服务组
    details: 提供一些简单的社区互助服务。
    link: zh-Hans/contact#在地服务组
---

<div :class="$style.outerContent">
<div :class="$style.content" class="vp-doc">

## 活动日历

<script setup>
import Calendar from '../Calendar.vue'
</script>

<Calendar url="https://calendar.google.com/calendar/ical/c_def3dc162ddaf3b15b3ee419551a2b65068b2493c0ecbbdce7daa867f2bc0aeb%40group.calendar.google.com/public/basic.ics"></Calendar>

可以 [添加到你的 Google Calendar](https://calendar.google.com/calendar/u/1?cid=Y19kZWYzZGMxNjJkZGFmM2IxNWIzZWU0MTk1NTFhMmI2NTA2OGIyNDkzYzBlY2JiZGNlN2RhYTg2N2YyYmMwYWViQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20) 或者使用 [ICal (ics) 格式链接](https://calendar.google.com/calendar/ical/c_def3dc162ddaf3b15b3ee419551a2b65068b2493c0ecbbdce7daa867f2bc0aeb%40group.calendar.google.com/public/basic.ics)。

## 我们的历史

2021 年 11 月 20 日跨性别纪念日前夕，纪念网站「那些秋叶」上线。
网站的中文名「那些秋叶」是桂桂起的，而英文名 One Among Us 则是 Maura 的创作。
正如我们在网站的介绍中写道：

> 那些因为各种原因过早离开我们的生命，那些跨性别者和我们的顺性别伙伴们（allies），仍然是我们中的一员（one among us），在默默照顾着、陪伴着我们，赋予我们继续生活的勇气。或许现实中的纪念碑上写着的并不是 ta 们所中意的姓名，也未必体现了 ta 们真实的认同，但我们仍然可以在自己的纪念中实现这一切。

后来，在 2022 年 12 月 15 日，我们在加拿大多伦多成立了注册非营利组织，一方面是为了保护我们自己，和我们的工作；另一方面，也希望以成立组织的方式，为我们的跨性别社群多做一些事情。

2023 年 3 月 13 日，我们的成员 ArtsEpiphany 永远离开了我们。为了纪念她，我们正在筹建一个名叫 Arts Among Us 的线上艺术展览馆项目。

我们现在在加拿大多伦多有 2 个活动地点，在世界各地都有线上参与工作的成员们。

</div>
</div>

<style module>
.content {
  max-width: 1152px;
  margin: 0 auto 2rem auto;
}
.outerContent {
  padding: 0 1rem;
}
</style>
