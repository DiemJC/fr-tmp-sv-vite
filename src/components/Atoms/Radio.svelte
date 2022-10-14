<script>
    export let normal = false;
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;
</script>

<input type="radio" class="radio"
    class:radio-normal={normal}
    class:radio-primary={primary}
    class:radio-secondary={secondary}
    class:radio-accent={accent}
    class:radio-large={large}
    class:radio-medium={medium}
    class:radio-small={small}
    class:radio-tiny={tiny}
>

<!-- Missing the label and form control -->