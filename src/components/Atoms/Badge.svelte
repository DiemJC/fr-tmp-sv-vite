<script>
    export let outline = false;
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let ghost = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;

</script>

<div class="badge"
    class:badge-outline={outline}
    class:badge-primary={primary}
    class:badge-secondary={secondary}
    class:badge-accent={accent}
    class:badge-ghost={ghost}
    class:badge-info={info}
    class:badge-success={success}
    class:badge-warning={warning}
    class:badge-error={error}
    class:badge-large={large}
    class:badge-medium={medium}
    class:badge-small={small}
    class:badge-tiny={tiny} 
>
<slot></slot>
</div>
