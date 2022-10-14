<script>
    export let normal = false
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;
    export let disabled = false;
    export let checked = false;
</script>

<input type="checkbox" class="checkbox"
    class:checkbox-normal={normal}
    class:checkbox-primary={primary}
    class:checkbox-secondary={secondary}
    class:checkbox-accent={accent}
    class:checkbox-large={large}
    class:checkbox-medium={medium}
    class:checkbox-small={small}
    class:checkbox-tiny={tiny}
    bind:checked
    {disabled}
>

 
<!-- Need to add status checkboxes e.g., "disabled", "checked" (unresolved) 
update: Disabled works, disabled and checked does not
-->