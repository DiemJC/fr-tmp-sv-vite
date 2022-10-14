<script>
    export let squircle = false;
    export let heart = false;
    export let hexagon = false;
    export let hexagon2 = false;
    export let decagon = false;
    export let pentagon = false;
    export let diamond = false;
    export let square = false;
    export let circle = false;
    export let parallelogram = false;
    export let parallelogram2 = false;
    export let parallelogram3 = false;
    export let parallelogram4 = false;
    export let star = false;
    export let star2 = false;
    export let triangle = false;
    export let triangle2 = false;
    export let triangle3 = false;
    export let triangle4 = false;
    export let half1 = false;
    export let half2 = false;
    export let alt = "some info about something"
    export let src = "https://placeimg.com/192/192/people"
</script>

<img class="mask" src={src} alt={alt}
    class:mask-squircle={squircle}
    class:mask-heart={heart}
    class:mask-hexagon={hexagon}
    class:mask-hexagon-2={hexagon2}
    class:mask-decagon={decagon}
    class:mask-pentagon={pentagon}
    class:mask-diamond={diamond}
    class:mask-square={square}
    class:mask-circle={circle}
    class:mask-parallelogram={parallelogram}
    class:mask-parallelogram-2={parallelogram2}
    class:mask-parallelogram-3={parallelogram3}
    class:mask-parallelogram-4={parallelogram4}
    class:mask-star={star}
    class:mask-star-2={star2}
    class:mask-triangle={triangle}
    class:mask-triangle-2={triangle2}
    class:mask-triangle-3={triangle3}
    class:mask-triangle-4={triangle4}
    class:mask-half-1={half1}
    class:mask-half-2={half2}
>

<!-- How to add an image to the mask style without hardcoding it? -->