<script>
    import github from '$lib/assets/github.png'
    import linkedin from '$lib/assets/linkedin.png'
</script>

<div class="Footer">
    <div class="links">
        <a href="https://www.github.com/pdychinco"><img id="github" src={github} alt="GitHub" width="64"
                                                        height="64"/></a>
        <a href="https://www.linkedin.com/in/prdychinco"><img id="linkedin" src={linkedin} alt="LinkedIn"
                                                              width="72" height="64"/></a>
    </div>
    <h4>604-379-3939 · PDYCHINCO@MY.BCIT.CA</h4>
    <p>© 2024 Princeton Dychinco</p>
</div>

<style>
    @media only screen and (max-width: 769px) {
        .Footer {
            display: grid;
            grid-template-columns: 1;
            grid-template-rows: 3;
        }
        .links {
            grid-row: 1;
            display: flex;
            justify-content: center;
        }
        h4 {
            grid-row: 2;
            display: flex;
            justify-content: center;
        }
        p {
            grid-row: 3;
            display: flex;
            justify-content: center;
        }
    }
    @media only screen and (min-width: 770px) {
        .Footer {
            display: grid;
            grid-template-columns: 2;
            grid-template-rows: 2;
        }
        .links {
            grid-row: 1;
            grid-column: 1;
            display: flex;
            justify-content: center;
        }
        h4 {
            grid-row: 1;
            grid-column: 2;
            display: flex;
            justify-content: center;
            padding-top: 0.5cm;
        }
        p {
            grid-row: 2;
            grid-column: 1 / 2;
            display: flex;
            justify-content: center;
        }
    }
</style>