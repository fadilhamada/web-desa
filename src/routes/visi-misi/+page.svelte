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
            <p class="text-[#06D001] text-sm lg:text-base">Visi & Misi</p>
        </div>
        <div class="py-6">
            <h1 class="text-xl font-bold lg:text-3xl uppercase">Visi & Misi</h1>
            <div class="w-32 border-t border-black lg:w-[22rem] my-2"></div>
            <div class="w-40 border-t border-black lg:w-96 my-2"></div>
        </div>
    </div>
</div>

<div class="mx-w-full bg-slate-50 py-8">
    <div class="px-7 lg:px-20">
        <div>
            <h1 class="text-xl font-semibold lg:text-3xl pb-2">Visi</h1>
            <p class="text-sm lg:text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem labore necessitatibus quisquam deleniti ab neque adipisci est in. Quasi, quisquam quo molestiae inventore nostrum impedit iste praesentium doloremque reprehenderit iusto!</p>
        </div>
        <div class="mt-10">
            <h1 class="text-xl font-semibold lg:text-3xl pb-2">Misi</h1>
            <p class="text-sm lg:text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem labore necessitatibus quisquam deleniti ab neque adipisci est in. Quasi, quisquam quo molestiae inventore nostrum impedit iste praesentium doloremque reprehenderit iusto!</p>
        </div>
    </div>
</div>

<Footer/>