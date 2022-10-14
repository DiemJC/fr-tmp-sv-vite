<script>
    export let primary = false;
    export let secondary = false;
    export let ghost = false;
    export let bordered = false;
    export let accent = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let large = false;
    export let medium = false;
    export let small = false;
    export let tiny = false;
    export let disabled = false;
      
</script>

<input placeholder="Enter text" class="input"
    class:input-primary={primary}
    class:input-secondary={secondary}
    class:input-ghost={ghost}
    class:input-bordered={bordered}
    class:input-accent={accent}
    class:input-info={info}
    class:input-success={success}
    class:input-warning={warning}
    class:input-error={error}
    class:input-large={large}
    class:input-mediumg={medium}
    class:input-small={small}
    class:input-tiny={tiny}
    {disabled}
>

