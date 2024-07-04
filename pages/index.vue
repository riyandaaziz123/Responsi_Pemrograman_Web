<template>
  <div>
    <HeroSection/>
  </div>
  <div>
    <AboutSection/>
  </div>
  <div>
    <SkillSection/>
  </div>
  <div>
    <ProjectsSection/>
  </div>
  <div>
    <ContactSection/>
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import SkillSection from '~/components/SkillSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';


export default {
  components: {
    HeroSection,
  }
}
</script>./Index.vue
