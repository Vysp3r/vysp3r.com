<script lang="ts">
    export let title = "";
    export let description = "";
    export let url = "";
</script>

<div>
    <a href={url}>{title}</a>
    <p>{description}</p>
</div>
