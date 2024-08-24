<script>
  import HeaderProfile from "../components/layouts/HeaderProfile.svelte";
  import AboutMe from "../components/layouts/AboutMe.svelte";
  import WorkExperience from "../components/layouts/WorkExperience.svelte";
  import Education from "../components/layouts/Education.svelte";
  import Language from "../components/layouts/Language.svelte";
  import Contact from "../components/layouts/Contact.svelte";
</script>

<main
  class="mx-auto max-w-[920px] px-2 md:px-4 py-10 bg-gray-100 text-gray-800 shadow shadow-lg"
>
  <div>
    <HeaderProfile />
    <AboutMe />
    <WorkExperience />
    <Education />
    <Language />
    <Contact />
  </div>
</main>
