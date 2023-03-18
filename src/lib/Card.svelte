<script lang="ts">
    export let imageSrc: string
    export let imageAlt: string = ''
    export let heading: string = ''
    export let text: string = ''
</script>

<article class="card">
    <img src={imageSrc} alt={imageAlt} class="card__image">
    <h1 class="card__heading">{heading}</h1>
    <p>{text}</p>
</article>

<style>

.card {
	padding: 1rem;
	padding-block-end: 2.5rem;
	max-width: 20rem;

	text-align: center;
	background-color: var(--clr-neutral-100);
	border-radius: var(--borr-400);
	filter: drop-shadow(0 1.5625rem 1.5625rem hsl(0deg 0% 0% / 0.05));
}

.card__image {
	margin-bottom: 1.5rem;
	border-radius: var(--borr-200);
}

.card__heading {
	margin-bottom: 1rem;
	font-size: var(--fz-700);
	color: var(--clr-primary-400);
	line-height: 1.1;
}

.card > p {
	padding-inline: 1rem;
}

</style>