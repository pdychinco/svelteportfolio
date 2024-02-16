<script>
    export let filter = 'all'
</script>
  
<div class="filters btn-group stack-exception">
<button class="btn toggle-btn" class:btn__primary={filter === 'all'} aria-pressed={filter === 'all'} on:click={() => filter = 'all'} >
    <span class="visually-hidden">Focus on</span>
    <span>Experience</span>
</button>
<button class="btn toggle-btn" class:btn__primary={filter === 'active'} aria-pressed={filter === 'active'} on:click={() => filter = 'active'} >
    <span class="visually-hidden">Focus on</span>
    <span>Projects</span>
</button>
<button class="btn toggle-btn" class:btn__primary={filter === 'completed'} aria-pressed={filter === 'completed'} on:click={() => filter = 'completed'} >
    <span class="visually-hidden">Focus on</span>
    <span>Education</span>
</button>
</div>

<style>
    .visually-hidden {
        /* visibility: hidden; */
    }
</style>