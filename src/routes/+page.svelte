<script lang="ts">
    import melyodas from '../images/melyodas.jpg'
    import Resume from '../lib/components/Resume.svelte'
</script>

<section class="h-screen bg-black w-screen px-0">
    <div class="canvas h-screen w-screen">
        <div class="img-container overflow-hidden relative w-screen">
            <img src={melyodas} alt="" class="object-cover">
        </div>
        <div class="content">
            <h1>@melyodas</h1>
            <div class="socials flex flex-row justify-around">
                <svg fill="#ffffff" width="24px" height="24px" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" stroke="#ffffff">
                    <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                    <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                    <g id="SVGRepo_iconCarrier">
                        <path d="M19.589 6.686a4.793 4.793 0 0 1-3.77-4.245V2h-3.445v13.672a2.896 2.896 0 0 1-5.201 1.743l-.002-.001.002.001a2.895 2.895 0 0 1 3.183-4.51v-3.5a6.329 6.329 0 0 0-5.394 10.692 6.33 6.33 0 0 0 10.857-4.424V8.687a8.182 8.182 0 0 0 4.773 1.526V6.79a4.831 4.831 0 0 1-1.003-.104z"></path>
                    </g>
                </svg>
                <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                    <path fill-rule="evenodd" d="M21.7 8c0-.7-.4-1.3-.8-2-.5-.5-1.2-.8-2-.8C16.2 5 12 5 12 5s-4.2 0-7 .2c-.7 0-1.4.3-2 .9-.3.6-.6 1.2-.7 2l-.2 3.1v1.5c0 1.1 0 2.2.2 3.3 0 .7.4 1.3.8 2 .6.5 1.4.8 2.2.8l6.7.2s4.2 0 7-.2c.7 0 1.4-.3 2-.9.3-.5.6-1.2.7-2l.2-3.1v-1.6c0-1 0-2.1-.2-3.2ZM10 14.6V9l5.4 2.8-5.4 2.8Z" clip-rule="evenodd"/>
                </svg>
                  
                <svg class="w-6 h-6 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                    <path fill-rule="evenodd" d="M12.5 8.8v1.7a3.7 3.7 0 0 1 3.3-1.7c3.5 0 4.2 2.2 4.2 5v5.7h-3.2v-5c0-1.3-.2-2.8-2.1-2.8-1.9 0-2.2 1.3-2.2 2.6v5.2H9.3V8.8h3.2ZM7.2 6.1a1.6 1.6 0 0 1-2 1.6 1.6 1.6 0 0 1-1-2.2A1.6 1.6 0 0 1 6.6 5c.3.3.5.7.5 1.1Z" clip-rule="evenodd"/>
                    <path d="M7.2 8.8H4v10.7h3.2V8.8Z"/>
                </svg>       
            </div>
        </div>
        <h1 class="textcontent">Content Coming soon..</h1>
    </div>
</section>

<style>
    .textcontent{
        color: white;
        position: absolute;
        top: 70vh;
        text-align: center;
        width: 100%;
    }

    h1{
        color: white;
    }
    img {
        width: 100%;
        height: inherit;
        -webkit-mask-image: linear-gradient(to top, transparent, black);
        mask-image: linear-gradient(to top, transparent, black);
    }


    .img-container{
        max-height: 60vh;
    }

    .canvas{
        width: 100%;
    }

    .content{
        display: grid;
        grid-auto-rows: 50px 50px;
        text-align: center;
        position: absolute;
        top: 50vh;
        width: 100%;
    }
</style>