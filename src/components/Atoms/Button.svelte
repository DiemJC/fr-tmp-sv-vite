<script>
    export let primary = false;
    export let secondary = false;
    export let accent = false;
    export let ghost = false;
    export let link = false;
    export let outline = false;
    export let active = false;
    export let info = false;
    export let success = false;
    export let warning = false;
    export let error = false;
    export let large = false;
    export let small = false;
    export let tiny = false;
    export let wide = false;
    export let glass = false;
    export let disabled = false;
    export let square = false;
    export let circle = false;
    export let block = false;
    export let loading = false;
    export let noAnimate = false;
</script>

<button 
    class="btn"
    class:btn-primary={primary}
    class:btn-secondary={secondary}
    class:btn-accent={accent}
    class:btn-ghost={ghost}
    class:btn-link={link}
    class:btn-outline={outline}
    class:btn-active={active}
    class:btn-info={info}
    class:btn-success={success}
    class:btn-warning={warning}
    class:btn-error={error}
    class:btn-lg={large}
    class:btn-sm={small}
    class:btn-xs={tiny}
    class:btn-wide={wide}
    class:btn-square={square}
    class:btn-circle={circle}
    class:btn-block={block}
    class:no-animation={noAnimate}
    class:glass
    class:loading
    {disabled}
>
    <slot></slot>
</button>