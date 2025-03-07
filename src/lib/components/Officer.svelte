<script>
    let { officerName, officerTitle, officerImage } = $props();
</script>

<style>

    .officer {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 350px;
        max-width: 600px;
        background-color: var(--main-color);
        border-radius: 20px;
        padding: 0 40px;


        img {
            max-width: 300px;
            height: auto;
            border-radius: 50%;
        }

        .officerText {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: var(--secondary-color);
            h3 {
                font-size: 20px;
                margin-bottom: 10px;
            }
            p {
                margin: 0;
            }
        }
    }

</style>

<div class="officer">
    <img src="{officerImage}" alt="officer" />
    <div class="officerText">
        <h3>{officerName}</h3>
        <p>{officerTitle}</p>
    </div>
</div>