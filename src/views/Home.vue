<template>
  <div class="">

    <Deploy/>

    <!-- First screen -->
    <header class="relative overflow-hidden w-full h-auto lg:h-screen">

        <!-- Notes -->
        <img src="../assets/img/comment-note.png" alt="" class="hidden lg:block absolute top-32 left-32">
        <img src="../assets/img/add-note.png" alt="" class="hidden lg:block absolute right-32 top-52">
        <img src="../assets/img/rate-note.png" alt="" class="hidden lg:block absolute left-32 bottom-24 z-20">

        <!-- Decorative images -->
        <img src="../assets/img/books-bg-r.png" alt="" class="hidden lg:block absolute bottom-0 -left-4">
        <img src="../assets/img/books-bg-r.png" alt="" class="hidden lg:block absolute bottom-0 right-0">
        <div class="flex justify-center">

            <img src="../assets/img/main.png" alt="" class="hidden lg:block absolute main-book -bottom-20 xl:-bottom-44 2xl:-bottom-52 lg:-ml-32">

        </div>

        <!-- Navbar -->
        <Navbar/>

        <!-- Offer -->
        <div class="flex flex-col items-center px-6">
            <img src="../assets/img/near_logo_stack_2.png" alt="" class="near-logo-img lg:-mt-24">

            <h1 class="text-4xl lg:text-6xl font-bold">NEAR Library</h1>

            <p class="mt-4 text-sm text-center w-full  md:w-1/2 lg:w-1/3 xl:w-1/4">It is a Dapp where you can to create, rate, comment, store 
                and transfer books using the NEAR protocol, making a library online 
                where you can request one book and change the owner.
            </p>
            
            <div class="flex flex-col md:flex-row items-center mt-6">

                <!-- <a href="#" class="w-72 h-14 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5 transform active:scale-95 duration-100">
                </a> -->
                
                <button class="w-72 h-14 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5 transform active:scale-95 duration-100">
                    <div class="w-full h-full rounded-full bg-transparent hover:bg-white">
                        <p class="flex justify-center items-center h-full text-2xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-white to-white hover:from-orange-400 hover:text-orange-300">Read books</p>
                    </div>
                </button>

                <button class="flex items-center justify-center w-72 h-14 text-2xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-orange-400 to-orange-300 hover:from-gray-300 hover:to-gray-300 transform active:scale-95 duration-100">
                    Add book +
                </button>

            </div>

            <div class="lg:hidden relative z-10 flex justify-center">
                <img src="../assets/img/main.png" alt="" class="">
            </div>
        </div>

    </header>

    <!-- Second screen -->
    <section>
        <div class="container mx-auto px-6">

            <div class="flex items-center justify-between pt-4 lg:pt-9 pb-10 lg:pb-20">

                <!-- Title top books -->
                <div class="flex">

                    <div class="">
                        <p class="text-4xl lg:text-6xl font-bold">Top books</p>
                        <p class="text-sm lg:text-lg mt-3">Top books of this week by NEAR readers.</p>
                    </div>

                    <img src="../assets/img/Right_arrow_curved.png" alt="" class="w-20 md:w-auto">

                </div>
                <!-- Note image -->
                <img src="../assets/img/best-books-note.png" alt="" class="hidden md:block">

            </div>

            <!-- Mobile note image -->
            <div class="flex justify-end">
                <img src="../assets/img/best-books-note.png" alt="" class="-mt-10 md:hidden">
            </div>

            <div class="px-10 md:px-20 lg:px-10 xl:px-20 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 2xl:grid-cols-4 gap-x-20">

                <Book/>
                <Book/>
                <Book/>
                <Book/>

            </div>

        </div>
    </section>

    <!-- All books section -->
    <section>
        <div class="container mx-auto px-6 mt-20">

            <div class="flex items-baseline justify-between pt-4 lg:pt-9 pb-10 lg:pb-20">

                <!-- Title books -->
                <div class="flex">

                    <div class="">
                        <p class="text-4xl lg:text-6xl font-bold">books</p>
                        <p class="text-sm lg:text-lg mt-3">Everything what do you want!</p>
                    </div>

                    <img src="../assets/img/exc.png" alt="" class="ml-4">

                </div>
                
                <!-- Sort -->
                <div class="flex space-x-4">

                    <a href="#" class="flex text-lg font-bold hover:text-orange-400">
                        <svg xmlns="http://www.w3.org/2000/svg" class="mr-2" width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M13.4472 20.9051C13.786 20.7376 14 20.3951 14 20.0204V14.6999C14 14.4376 14.1054 14.186 14.2929 
                            14.0005L20.414 7.94576C20.789 7.57483 21 7.07135 21 6.54611V3.98915C21 3.44215 20.553 3 20 3H4C3.447 
                            3 3 3.44215 3 3.98915V6.54611C3 7.07135 3.211 7.57483 3.586 7.94576L9.70711 14.0005C9.89464 14.186 10 
                            14.4376 10 14.6999V21.0096C10 21.7449 10.7823 22.2231 11.4472 21.8943L13.4472 20.9051Z" fill="currentColor"/>
                        </svg>
                        Sort by Name
                    </a>
                    <a href="#" class="flex text-lg font-bold hover:text-orange-400">
                        <svg xmlns="http://www.w3.org/2000/svg" class="mr-2" width="24" height="24" viewBox="0 0 24 24" fill="none">
                            <path d="M13.4472 20.9051C13.786 20.7376 14 20.3951 14 20.0204V14.6999C14 14.4376 14.1054 14.186 14.2929 
                            14.0005L20.414 7.94576C20.789 7.57483 21 7.07135 21 6.54611V3.98915C21 3.44215 20.553 3 20 3H4C3.447 
                            3 3 3.44215 3 3.98915V6.54611C3 7.07135 3.211 7.57483 3.586 7.94576L9.70711 14.0005C9.89464 14.186 10 
                            14.4376 10 14.6999V21.0096C10 21.7449 10.7823 22.2231 11.4472 21.8943L13.4472 20.9051Z" fill="currentColor"/>
                        </svg>
                        Sort by Date
                    </a>

                </div>

            </div>

            <!-- Books -->
            <div class="px-10 md:px-20 lg:px-10 xl:px-20 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 2xl:grid-cols-4 gap-x-20 gap-y-8">

                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>
                <Book/>

            </div>

            <!-- Pagination -->
            <div class="flex justify-center items-center my-32">
                <ul class="flex text-lg font-bold">
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">Previous</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">1</a></li>
                    <!-- Active element (just need to add class - border-b-2 ) -->
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400 border-b-2">2</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">3</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">4</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">5</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">6</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">7</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">8</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">9</a></li>
                    <li><a href="#" class="pb-2 px-1 md:px-3 hover:border-b-2 border-orange-400">Next</a></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Second offer -->
    <section>
        <div class="container mx-auto px-6">

            <div class="flex flex-col md:flex-row">
                <div class="w-full md:w-1/2">
                    <div class="flex flex-col items-center px-10">
                        <img src="../assets/img/near_logo_stack_2.png" alt="" class="">
                        <p class="text-4xl lg:text-6xl font-bold">NEAR Library</p>
                        <p class="text-center mt-6 ">It is a Dapp where you can to create, rate, 
                            comment, store and transfer books using the NEAR protocol, 
                            making a library online where you can request one book and change 
                            the owner.
                        </p>
                        <button class="w-72 h-14 mt-7 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5 transform active:scale-95 duration-100">
                            <div class="w-full h-full rounded-full bg-transparent hover:bg-white">
                                <p class="flex justify-center items-center h-full text-2xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-white to-white hover:from-orange-400 hover:text-orange-300">Add books +</p>
                            </div>
                        </button>
                    </div>
                </div>
                <div class="w-full md:w-1/2">
                    <img src="../assets/img/main.png" alt="">
                </div>
            </div>

        </div>
    </section>

    <Footer/>

  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Deploy from '@/components/Deploy.vue'
import Footer from '@/components/Footer.vue'
import Book from '@/components/Book.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Deploy,
    Footer,
    Book,
  }
}
</script>
