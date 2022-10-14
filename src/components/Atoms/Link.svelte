<script>
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let neutral = false;
    export let hover = false;
    export let href = null;
    export let onClick = null;
    
</script>

<a class="link" href={href} 
    class:link-primary={primary}
    class:link-secondary={secondary}
    class:link-accent={accent}
    class:link-neutral={neutral}
    class:link-hover={hover}
    on:click|preventDefault={onClick}
>
<slot></slot>
</a>

<!-- The link element needs to redirect to the appropriate domain provided (how to assign it a proper address?) -->