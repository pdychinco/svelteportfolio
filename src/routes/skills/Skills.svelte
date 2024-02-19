<div class="Skills">
    <div id="pgrm">
        <h5>Programming Langauges</h5>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>C</li>
            <li>Scala</li>
        </ul>
    </div>
    <div id="web">
        <h5>Web Development</h5>
        <ul>
            <li>HTML5</li>
            <li>CSS5</li>
            <li>JavaScript (Client/Server)</li>
            <li>Node.js</li>
            <li>Svelte</li>
        </ul>
    </div>
    <div id=db>
        <h5>Databases</h5>
        <ul>
            <li>MySQL</li>
            <li>FireBase (NoSQL)</li>
        </ul>
    </div>
    <div id=workflow>
        <h5>Workflow</h5>
        <ul>
            <li>GitHub</li>
            <li>Agil Scrum Methodology</li>
            <li>Kanban Methodology</li>
        </ul>
    </div>
</div>
<style>

@media only screen and (max-width: 769px) {
    .Skills{
        display: grid;
        grid-template-columns: 50% 50%;
        grid-template-rows: auto;
        margin: 0 auto;
    }
    #pgrm {
        grid-row: 1;
        grid-column: 1;
    }
    #web {
        grid-row: 1;
        grid-column: 2;
    }
    #db{
        grid-row: 2;
        grid-column: 1;
    }
    #workflow{
        grid-row: 2;
        grid-column: 2;
    }
    ul {
        margin-left: 15px;
    }
}

@media only screen and (min-width: 770px) {
    .Skills{
        display: grid;
        grid-template-columns: 25% 25% 25% 25%;
        grid-template-rows: auto;
        margin: 0 auto;
    }
    #pgrm {
        grid-row: 1;
        grid-column: 1;
    }
    #web {
        grid-row: 1;
        grid-column: 2;
    }
    #db{
        grid-row: 1;
        grid-column: 3;
    }
    #workflow{
        grid-row: 1;
        grid-column: 4;
    }
    ul {
        margin-left: 15px;
    }
}

</style>