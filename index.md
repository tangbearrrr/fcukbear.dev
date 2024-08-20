---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "fcukbear.dev"
  text: "\"Nothing in my mind\""
  tagline: "a website about software engineering and some \"stupid stuff\""
---

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://avatars.githubusercontent.com/u/61175951?v=4',
    name: 'Rahat Sarawasee',
    title: 'Developer Advocate',
    links: [
      { icon: 'github', link: 'https://github.com/tangbearrrr' },
      { icon: 'linkedin', link: 'https://www.linkedin.com/in/rahat-sarawasee/' },
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/130965011?v=4',
    name: 'Bhijak Petchsuksan',
    title: 'Back-end Developer',
    links: [
      { icon: 'github', link: 'https://github.com/lamoon-p' },
      { icon: 'linkedin', link: 'https://www.linkedin.com/in/bhijak-petchsuksan-0715771b7/' }
    ]
  },
]
</script>


## Our Team

Say hello to our awesome friends.

<VPTeamMembers size="small" :members="members" />