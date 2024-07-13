<script>
    import Navbar from "../lib/components/navbar.svelte";
    import Hero from "../lib/assets/alam.jpg"
    import Wali from "../lib/assets/walidanwakil.png"
    import desa from "../lib/assets/desa-pandan.jpg"
    import image from "../lib/assets/imgae3.jpg"
    import image2 from "../lib/assets/image2.jpg"
    import image3 from "../lib/assets/image3.jpeg"
    import image4 from "../lib/assets/image4.jpg"
    import image5 from "../lib/assets/image5.jpg"
    import Footer from "../lib/components/footer.svelte";
</script>

<Navbar/> 
<!-- Start Hero Section -->
<div class="max-w-full relative pt-16">
    <div>
        <img src="{Hero}" alt="" >
    </div>
    <div class="flex items-center justify-center w-full h-[14.5rem] lg:h-full absolute top-12 lg:top-0" id="bg">
        <div class="w-full h-full flex flex-col justify-center items-center lg:items-start">
            <p class="text-sm uppercase text-white px-20 font-semibold lg:text-xl">Selamat Datang Di Website Resmi</p>
            <h1 class="text-xl text-white px-16 uppercase lg:text-7xl font-bold">Desa Pandan</h1>
            <span class="text-sm uppercase lg:text-xl px-20 text-white lg:mt-4">Kec. Galis Kabupaten Pamekasan</span>
        </div>
    </div>
</div>
<!-- End Hero Section -->

<!-- Start Fitur Section -->
<div class="max-w-full my-12">
    <div class=" px-2 lg:px-20">
        <div class="flex justify-center flex-wrap gap-2 lg:gap-5">
            <a href="/">
                <div class="bg-[#06D001] flex flex-col items-center lg:w-52 w-36 rounded-lg lg:py-5 py-2 shadow-lg">
                    <div class="text-base lg:text-2xl bg-white rounded-full lg:px-4 lg:py-4 px-3 py-2">
                        <i class="fa-solid fa-users"></i>   
                    </div>
                    <h1 class="text-base lg:text-xl font-bold text-white mt-3">Profil Desa</h1>
                </div>
            </a>
            <a href="/">
                <div class="bg-[#06D001] flex flex-col items-center lg:w-52 w-36 rounded-lg lg:py-5 py-2 shadow-lg">
                    <div class="text-base lg:text-2xl bg-white rounded-full lg:px-4 lg:py-4 px-3 py-2">
                        <i class="fa-solid fa-users"></i>   
                    </div>
                    <h1 class="text-base lg:text-xl font-bold text-white mt-3">Profil Desa</h1>
                </div>
            </a>
            <a href="/">
                <div class="bg-[#06D001] flex flex-col items-center lg:w-52 w-36 rounded-lg lg:py-5 py-2 shadow-lg">
                    <div class="text-base lg:text-2xl bg-white rounded-full lg:px-4 lg:py-4 px-3 py-2">
                        <i class="fa-solid fa-users"></i>   
                    </div>
                    <h1 class="text-base lg:text-xl font-bold text-white mt-3">Profil Desa</h1>
                </div>
            </a>
            <a href="/">
                <div class="bg-[#06D001] flex flex-col items-center lg:w-52 w-36 rounded-lg lg:py-5 py-2 shadow-lg">
                    <div class="text-base lg:text-2xl bg-white rounded-full lg:px-4 lg:py-4 px-3 py-2">
                        <i class="fa-solid fa-users"></i>   
                    </div>
                    <h1 class="text-base lg:text-xl font-bold text-white mt-3">Profil Desa</h1>
                </div>
            </a>
            <a href="/">
                <div class="bg-[#06D001] flex flex-col items-center lg:w-52 w-36 rounded-lg lg:py-5 py-2 shadow-lg">
                    <div class="text-base lg:text-2xl bg-white rounded-full lg:px-4 lg:py-4 px-3 py-2">
                        <i class="fa-solid fa-users"></i>   
                    </div>
                    <h1 class="text-base lg:text-xl font-bold text-white mt-3">Profil Desa</h1>
                </div>
            </a>
          
        </div>
    </div>
</div>
<!-- End Fitur Section -->

<!-- Start Profil Singkat Section -->
<div class="mx-w-full bg-slate-50 py-8">
    <h1 class="text-xl text-center uppercase text-[#06D001] pb-5 font-bold lg:text-3xl">Profil Singkat</h1>
    <div class="px-7 lg:px-20">
        <div class="flex flex-col lg:flex-row lg:justify-between pt-7 border-t border-black">
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
<!-- End Profil Singkat Section -->

<!-- Start Galeri Section -->
<div class="max-w-full my-16 bg-[#06D001] py-10">
    <h1 class="text-xl text-center uppercase text-white font-bold pb-6 lg:text-3xl">Galeri Desa Pandan</h1>
    <div class="px-7 lg:px-20">
        <div class="flex justify-center gap-7 flex-wrap w-full border-t border-black py-10">
            <div class="py-1">
                <img src={image} alt="" class="w-48 lg:w-72 h-36 lg:h-56 border border-black rounded-lg">
            </div>
            <div class="py-1">
                <img src={image4} alt="" class="w-48 lg:w-72 h-36 lg:h-56 border border-black rounded-lg">
            </div>
            <div class="py-1">
                <img src={image3} alt="" class="w-48 lg:w-72 h-36 lg:h-56 border border-black rounded-lg">
            </div>
            <div class="py-1">
                <img src={image5} alt="" class="w-48 lg:w-72 h-36 lg:h-56 border border-black rounded-lg">
            </div>
            <div class="py-1">
                <img src={image2} alt="" class="w-48 lg:w-72 h-36 lg:h-56 border border-black rounded-lg">
            </div>
        </div>
    </div>
</div>
<!-- End Galeri Section -->

<!-- Start Agenda Section -->
<div class="max-w-full">
    <h1 class="text-xl text-center uppercase font-bold pb-6 lg:text-3xl">Berita Desa Pandan</h1>
    <div class="px-7 lg:px-20">
        <div class="flex flex-col border-t border-black">
            <div class="flex flex-col lg:flex-row lg:justify-between py-10">
                <div class="w-full lg:w-[40%]">
                    <img src={image4} alt="" class="w-full mx-auto rounded-md shadow-md">
                </div>
                <div class="w-full mt-5 lg:mt-0 lg:w-[80%]">
                    <div class="flex flex-col lg:justify-center lg:pl-10 mb-6">
                        <h1 class="text-xl font-bold text-[#06D001] lg:text-2xl mb-1">Penerimaan Bantuan</h1>
                        <span class="text-sm font-semibold my-2 lg:text-base">Desa Pandan : 15 Agustus 2024</span>
                        <p class="text-sm lg:text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit sit quasi, id aspernatur ratione cumque deserunt odit tempore officia cum quos vero adipisci fugiat, dolore harum fuga dolor quaerat aperiam?</p>
                    </div>
                    <a href="/" class="lg:ml-10 px-3 py-2 bg-[#06D001] text-white rounded-lg font-semibold shadow-lg">Baca Selengkapnya</a>
                </div>
            </div>
            <div class="flex flex-col lg:flex-row lg:justify-between py-10">
                <div class="w-full lg:w-[40%]">
                    <img src={image4} alt="" class="w-full mx-auto rounded-md shadow-md">
                </div>
                <div class="w-full mt-5 lg:mt-0 lg:w-[80%]">
                    <div class="flex flex-col lg:justify-center lg:pl-10 mb-6">
                        <h1 class="text-xl font-bold text-[#06D001] lg:text-2xl mb-1">Penerimaan Bantuan</h1>
                        <span class="text-sm font-semibold my-2 lg:text-base">Desa Pandan : 15 Agustus 2024</span>
                        <p class="text-sm lg:text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit sit quasi, id aspernatur ratione cumque deserunt odit tempore officia cum quos vero adipisci fugiat, dolore harum fuga dolor quaerat aperiam?</p>
                    </div>
                    <a href="/" class="lg:ml-10 px-3 py-2 bg-[#06D001] text-white rounded-lg font-semibold shadow-lg">Baca Selengkapnya</a>
                </div>
            </div>
            <div class="flex flex-col lg:flex-row lg:justify-between py-10">
                <div class="w-full lg:w-[40%]">
                    <img src={image4} alt="" class="w-full mx-auto rounded-md shadow-md">
                </div>
                <div class="w-full mt-5 lg:mt-0 lg:w-[80%]">
                    <div class="flex flex-col lg:justify-center lg:pl-10 mb-6">
                        <h1 class="text-xl font-bold text-[#06D001] lg:text-2xl mb-1">Penerimaan Bantuan</h1>
                        <span class="text-sm font-semibold my-2 lg:text-base">Desa Pandan : 15 Agustus 2024</span>
                        <p class="text-sm lg:text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit sit quasi, id aspernatur ratione cumque deserunt odit tempore officia cum quos vero adipisci fugiat, dolore harum fuga dolor quaerat aperiam?</p>
                    </div>
                    <a href="/" class="lg:ml-10 px-3 py-2 bg-[#06D001] text-white rounded-lg font-semibold shadow-lg">Baca Selengkapnya</a>
                </div>
            </div>
           
            
        </div>
    </div>
</div>
<!-- End Agenda Section -->

<div class="max-w-full">
    <iframe class="w-full" 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7917.355387688918!2d113.54416368899935!3d-7.1632089762276525!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dd77d4003151e3f%3A0x39c459789a15abb9!2sPandan%2C%20Kec.%20Galis%2C%20Kabupaten%20Pamekasan%2C%20Jawa%20Timur!5e0!3m2!1sid!2sid!4v1720523011102!5m2!1sid!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" title="Pandan" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<Footer/>