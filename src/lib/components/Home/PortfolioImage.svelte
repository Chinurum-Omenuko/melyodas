<script lang="ts">
    import melyodas from "../../../images/melyodas.jpg"
    type ImageSource = string;
    const portfolioImage: ImageSource = "src/images/melyodas.jpg"
</script>

<div id="image" class="flex-col w-full">
    <img src={melyodas} alt="Hero">
</div>

<style lang="scss">
    #image{
        width: 100%;
        padding: em;
    }
</style>