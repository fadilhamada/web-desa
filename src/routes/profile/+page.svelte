<script>
    import Navbar from "../../lib/components/navbar.svelte";
    import Footer from "../../lib/components/footer.svelte";
    import desa from "../../lib/assets/desa-pandan.jpg"
</script>

<Navbar/>

<div class="max-w-full pt-24">
    <div class="px-7 lg:px-20">
        <div class="flex items-center gap-3 font-semibold">
            <a href="/" class="text-sm lg:text-base">Beranda</a>
            <p>></p>
            <p class="text-[#06D001] text-sm lg:text-base">Profil Desa</p>
        </div>
        <div class="py-6">
            <h1 class="text-xl font-bold lg:text-3xl uppercase">Profil Desa Pandan</h1>
            <div class="w-60 border-t border-black lg:w-[22rem] my-2"></div>
            <div class="w-64 border-t border-black lg:w-96 my-2"></div>
        </div>
    </div>
</div>

<div class="mx-w-full bg-slate-50 py-8">
    <div class="px-7 lg:px-20">
        <div class="flex flex-col lg:flex-row lg:justify-between">
            <div class="text-black mt-3 lg:w-1/2 flex flex-col justify-center order-2 lg:order-1">
                <h1 class="py-2 font-bold text-xl lg:text-3xl text-[#06D001]">Desa Pandan</h1>
                <p class="text-sm text-slate-500 lg:text-base">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cum esse repudiandae, obcaecati praesentium adipisci recusandae modi officia soluta distinctio, ullam blanditiis in molestiae similique asperiores consequuntur doloribus sequi fugit iusto.</p>
            </div>
            <div class="lg:w-1/2 order-1 lg:order-2">
                <img src="{desa}" alt="" class="mx-auto rounded-lg shadow-md w-full">
            </div>
        </div>
    </div>
</div>

<Footer/>