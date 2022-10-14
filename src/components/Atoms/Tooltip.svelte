<script> 
    export let normal= false;
    export let open = false;
    export let bottom = false;
    export let left = false;
    export let right = false;
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let text = "";


</script>

<div class="tooltip"
    class:tooltip-normal={normal}
    class:tooltip-open={open}
    class:tooltip-bottom={bottom}
    class:tooltip-left={left}
    class:tooltip-right={right}
    class:tooltip-primary={primary}
    class:tooltip-secondary={secondary}
    class:tooltip-accent={accent}
    class:tooltip-info={info}
    class:tooltip-success={success}
    class:tooltip-warning={warning}
    class:tooltip-error={error}
    data-tip={text}
>
<slot></slot>
</div>

<!-- INQUIRY: Can't find a way to add text to tooltips (yet to be solved, adding a slot does not appear to solve it) -->