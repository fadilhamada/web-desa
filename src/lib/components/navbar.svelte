<script>
    const hover = () => {
        document.getElementById('dropdown').classList.toggle('hidden')
    }

    const menu = () => {
        document.getElementById('dropdown-desa').classList.add('hidden')
        document.getElementById('menu').classList.toggle('hidden')
    }

    const toggleProfil = () => {
        document.getElementById('dropdown-desa').classList.toggle('hidden')
    }
</script>
<div class="container max-w-full bg-[#06D001] fixed z-10 border-b border-black">
    <div class="px-7 lg:px-20 lg:py-0 py-5">
        <div class="flex items-center justify-between">
            <div class="text-lg text-white lg:text-4xl font-bold outline-none">
                <a href="/">Desa Pandan</a>
            </div>
            <div class="lg:flex gap-4 text-white font-semibold text-xl hidden">
                <a href="/" class="hover:text-black py-5">Beranda</a>
                <button on:mouseenter={() => {hover()}} on:mouseleave={() => {hover()}} class="hover:text-black py-5">Tentang Desa</button>
                <ul on:mouseenter={()=>hover()} on:mouseleave={() => {hover()}} class="absolute bg-white px-6 py-2 top-full right-[31.7rem] text-black hidden rounded-md shadow-md" id="dropdown">
                    <li class="py-2"><a href="/profile" class="text-lg hover:text-[#06D001]">Profil Desa</a></li>
                    <li class="py-2"><a href="/visi-misi" class="text-lg hover:text-[#06D001]">Visi & Misi</a></li>
                    <li class="py-2"><a href="/" class="text-lg hover:text-[#06D001]">Perangkat</a></li>
                </ul>
                <a href="/" class="hover:text-black py-5">Potensi dan Pariwisata</a>
                <a href="/" class="hover:text-black py-5">Berita</a>
                <a href="/" class="hover:text-black py-5">Galeri</a>
                <a href="/" class="hover:text-black py-5">Kontak</a>
            </div>
            <!-- start hamburger menu -->
             <button on:click|preventDefault={menu} class="lg:hidden"><i class="fa-solid fa-bars text-white"></i></button>
            <!-- end hamburger menu -->

            <!-- start menu -->
            <div class="absolute bg-white py-2 top-full right-0 text-black rounded-md shadow-md hidden" id="menu">
                <a href="/" class="py-2 px-6 text-base hover:text-[#06D001] block">Beranda</a>
                <button on:click|preventDefault={toggleProfil} class="py-2 px-6 text-base hover:text-[#06D001]">Tentang Desa <i class="fa-solid fa-caret-down ml-10"></i></button>
                <div class="top-full left-20 text-black hidden" id="dropdown-desa">
                    <a href="/profile" class="py-2 text-base hover:text-[#06D001] block px-5">Profil Desa</a>
                    <a href="/visi-misi" class="py-2 text-base hover:text-[#06D001] block px-5">Visi & Misi</a>
                    <a href="/" class="py-2 text-base hover:text-[#06D001] block px-5">Perangkat</a>
                </div>
                <a href="/visi-misi" class="py-2 px-6 text-base hover:text-[#06D001] block">Potensi dan Pariwisata</a>
                <a href="/" class="py-2 px-6 text-base hover:text-[#06D001] block">Berita</a>
                <a href="/" class="py-2 px-6 text-base hover:text-[#06D001] block">Galeri</a>
                <a href="/" class="py-2 px-6 text-base hover:text-[#06D001] block">Kontak</a>
            </div>
            <!-- end menu -->
        </div>
    </div>
</div>