<script>
    import Officer from '$lib/components/Officer.svelte';
</script>

<style>

    h2 {
        text-align: center;
        color: var(--secondary-color);
        background-color: var(--main-color);
        padding: 20px;
        font-size: 28px;
    }
    
    .officers {
        display: grid;
        grid-template-columns: 50% 50%;
        grid-template-rows: 50% 50%;
        gap: 20px;
        padding: 40px;
    }

</style>

    

<h2>Meet the Officers!</h2>

<section class="officers">
    <Officer officerName="John Doe" officerTitle="President" officerImage="https://picsum.photos/300" />
<Officer officerName="Jane Doe" officerTitle="Vice President" officerImage="https://picsum.photos/300" />
<Officer officerName="John Smith" officerTitle="Treasurer" officerImage="https://picsum.photos/300" />
<Officer officerName="Jane Smith" officerTitle="Secretary" officerImage="https://picsum.photos/300" />
</section>
