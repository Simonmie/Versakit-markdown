---
layout: page
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://avatars.githubusercontent.com/u/122306263?v=4',
    name: 'JustHappy',
    title: ' Creator',
    links: [
      { icon: 'github', link: 'https://github.com/Simonmie' },
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/74483049?s=400&u=102dfac48d0067d9d7a5576134e409590bbfaafe&v=4',
    name: 'Jannik',
    title: 'Developer',
    links: [
      { icon: 'github', link: 'https://github.com/lenran659' },
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/131731035?v=4',
    name: 'Pei',
    title: 'UI Designer | Developer',
    links: [
      { icon: 'github', link: 'https://github.com/Dream-2022' },
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/184910937?v=4',
    name: 'StriveToLearnCode',
    title: 'Developer',
    links: [
      { icon: 'github', link: 'https://github.com/StriveToLearnCode' },
    ]
  },
  {
    avatar: 'https://avatars.githubusercontent.com/u/86543671?v=4',
    name: 'abining',
    title: 'Developer',
    links: [
      { icon: 'github', link: 'https://github.com/abining?tab=repositories' },
    ]
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>团队成员</template>
    <template #lead>
      我们是一群热爱开源的人。
    </template>
  </VPTeamPageTitle>

<VPTeamMembers size="small" :members="members" />

</VPTeamPage>
