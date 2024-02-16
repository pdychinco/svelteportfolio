<script>
    import Education from './education/+page.svelte'
    import Header from './header/+page.svelte'
    import FilterButtons from './filterbuttons/+page.svelte'
    import Projects from './projects/+page.svelte'
    import Experience from './experience/+page.svelte'
    import Footer from './footer/+page.svelte'
</script>

<Header />
<FilterButtons />
<h3>Experience</h3>
<Experience />
<h3>Projects</h3>
<Projects />
<h3>Education</h3>
<Education />
<Footer />