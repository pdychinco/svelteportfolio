<script>
    import Education from './education/Education.svelte'
    import Header from './header/Header.svelte'
    import Nav from './nav/Nav.svelte'
    import Projects from './projects/Projects.svelte'
    import Experience from './experience/Experience.svelte'
    import Footer from './footer/Footer.svelte'
    import MediaQuery from './mediaQuery/MediaQuery.svelte'
    import Skills from './skills/Skills.svelte'
</script>

<MediaQuery query="(min-width: 770px)" let:matches>
    {#if matches}
        <Nav />
    {:else}
        
    {/if}
</MediaQuery>
<Header />
<h3 class="header">Projects</h3>
<Projects />
<h3 class="header">Technical Skills</h3>
<Skills />

<Footer />