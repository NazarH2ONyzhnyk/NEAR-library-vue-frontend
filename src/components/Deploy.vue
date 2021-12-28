<template>
    <div class="relative w-full flex flex-col items-center">
        <div class="absolute z-10 w-74 h-37 bg-gradient-to-r from-orange-400 to-orange-400 rounded-b-full opacity-50 pulsing"></div>
        <button class="relative z-20 w-60 h-30 flex items-center justify-center bg-gradient-to-r from-orange-400 to-orange-300 hover:from-gray-24 hover:to-gray-24 rounded-b-full">
            <svg xmlns="http://www.w3.org/2000/svg" class="mb-1" width="20" height="13" viewBox="0 0 20 13" fill="none">
                <path d="M1.8701 0.490034L0.100098 2.27003L10.0001 12.16L19.9001 2.26003L18.1301 0.490034L10.0001 8.62003L1.8701 0.490034Z" fill="white"/>
            </svg>
        </button>
        
        <p class="mt-2 font-semibold">Try frontend with your deployed contract ID</p>

        <!-- <div class="text-center">
            <p class="inline-block text-transparent bg-clip-text bg-gradient-to-r from-orange-400 to-orange-300  mt-2 font-semibold">Current ID</p>
            <p class="font-semibold">“dev-1635829277525-2258924695353”</p>
        </div> -->

        <div class="absolute z-30 w-374 flex flex-col items-center bg-white px-4 pb-10 rounded-xl shadow-xl">
            <div class="absolute z-10 w-74 h-37 bg-gradient-to-r from-orange-400 to-orange-400 rounded-b-full opacity-50 pulsing"></div>
            <button class="relative z-20 w-60 h-30 mx-auto flex items-center justify-center bg-gradient-to-r from-orange-400 to-orange-300 hover:from-gray-24 hover:to-gray-24 rounded-b-full">
                <svg xmlns="http://www.w3.org/2000/svg" class="mb-2 transform rotate-180" width="20" height="13" viewBox="0 0 20 13" fill="none">
                    <path d="M1.8701 0.490034L0.100098 2.27003L10.0001 12.16L19.9001 2.26003L18.1301 0.490034L10.0001 8.62003L1.8701 0.490034Z" fill="white"/>
                </svg>
            </button>

            <!-- NEAR Logo -->
                <svg xmlns="http://www.w3.org/2000/svg" class="mx-auto mt-4" width="151" height="40" viewBox="0 0 151 40" fill="none">
                    <g clip-path="url(#clip0_209_7034)">
                    <path d="M75.588 8.30057V31.4804C75.588 31.657 75.4555 31.8336 75.2348 31.8336H72.8064C71.7026 31.8336 70.643 31.2596 70.0248 30.3324L59.0751 13.4222L59.4284 21.8553V31.5246C59.4284 31.7012 59.2959 31.8778 59.0751 31.8778H55.8962C55.7196 31.8778 55.543 31.7453 55.543 31.5246V8.30057C55.543 8.12397 55.6754 7.94736 55.8962 7.94736H58.2804C59.3842 7.94736 60.4438 8.52133 61.062 9.44853L72.0117 26.3146L71.6585 17.8816V8.30057C71.6585 8.12397 71.7909 7.94736 72.0117 7.94736H75.1906C75.4555 7.94736 75.588 8.07981 75.588 8.30057Z" fill="black"/>
                    <path d="M108.172 31.7895H104.817C104.596 31.7895 104.419 31.5687 104.508 31.3479L113.426 8.25642C113.515 8.07981 113.691 7.94736 113.868 7.94736H118.106C118.327 7.94736 118.504 8.07981 118.548 8.25642L127.511 31.3479C127.599 31.5687 127.423 31.7895 127.202 31.7895H123.846C123.714 31.7895 123.581 31.7012 123.537 31.5687L116.34 12.5833C116.252 12.3184 115.811 12.3184 115.722 12.5833L108.525 31.5687C108.437 31.7012 108.305 31.7895 108.172 31.7895Z" fill="black"/>
                    <path d="M150.913 31.2596L144.202 22.6941C147.999 21.9877 150.206 19.4269 150.206 15.4974C150.206 10.9938 147.292 7.94736 142.082 7.94736H132.722C132.457 7.94736 132.236 8.16812 132.236 8.43303C132.236 10.1991 133.649 11.612 135.415 11.612H141.729C144.864 11.612 146.365 13.2015 146.365 15.5415C146.365 17.8816 144.908 19.471 141.729 19.471H132.81C132.545 19.471 132.325 19.6918 132.325 19.9567V31.4362C132.325 31.6129 132.457 31.7895 132.678 31.7895H135.857C136.033 31.7895 136.21 31.657 136.21 31.4362V22.9149H139.875L145.703 30.5091C146.321 31.3479 147.292 31.7895 148.352 31.7895H150.78C150.957 31.7895 151.089 31.4804 150.913 31.2596Z" fill="black"/>
                    <path d="M98.1055 7.94736H83.3146C83.0497 7.94736 82.873 8.12397 82.873 8.38888C82.873 10.155 84.3301 11.612 86.0961 11.612H98.1055C98.2821 11.612 98.4587 11.4795 98.4587 11.2588V8.25642C98.4146 8.07981 98.2821 7.94736 98.1055 7.94736ZM98.1055 28.1248H87.0675C86.8909 28.1248 86.7143 27.9924 86.7143 27.7716V21.8111C86.7143 21.6345 86.8467 21.4579 87.0675 21.4579H97.2666C97.4432 21.4579 97.6198 21.3254 97.6198 21.1047V18.1023C97.6198 17.9257 97.4874 17.7491 97.2666 17.7491H83.3587C83.0938 17.7491 82.873 17.9699 82.873 18.2348V31.2596C82.873 31.5246 83.0938 31.7453 83.3587 31.7453H98.1055C98.2821 31.7453 98.4587 31.6129 98.4587 31.3921V28.3898C98.4146 28.2573 98.2821 28.1248 98.1055 28.1248Z" fill="black"/>
                    <path d="M31.8778 2.03099L23.5772 14.3494C23.0032 15.1883 24.107 16.2038 24.9018 15.4974L33.0699 8.38889C33.2906 8.21228 33.5997 8.34474 33.5997 8.6538V30.8623C33.5997 31.1713 33.2023 31.3038 33.0257 31.083L8.30058 1.50117C7.50585 0.529825 6.35789 0 5.07749 0H4.19444C1.89854 0 0 1.89854 0 4.2386V35.4982C0 37.8383 1.89854 39.7368 4.2386 39.7368C5.69561 39.7368 7.06433 38.9863 7.85906 37.7058L16.1596 25.3874C16.7336 24.5485 15.6298 23.533 14.8351 24.2395L6.66696 31.3038C6.4462 31.4804 6.13713 31.348 6.13713 31.0389V8.87456C6.13713 8.5655 6.5345 8.43304 6.71111 8.6538L31.4363 38.2357C32.231 39.207 33.4231 39.7368 34.6594 39.7368H35.5424C37.8825 39.7368 39.781 37.8383 39.781 35.4982V4.2386C39.7368 1.89854 37.8383 0 35.4982 0C34.0412 0 32.6725 0.750585 31.8778 2.03099Z" fill="black"/>
                    </g>
                    <defs>
                    <clipPath id="clip0_209_7034">
                    <rect width="151" height="39.7368" fill="white"/>
                    </clipPath>
                    </defs>
                </svg>

                <!-- Title -->
                <p class="text-2xl font-bold text-center mt-5">Contract deploy</p>

                <!-- Description -->
                <p class="text-gray-400 text-center mt-2 text-sm font-semibold">
                    Please make sure that you put in input field correct contract id and your contract is deployed correctly. 
                    This is  <a href class="inline-block bg-gradient-to-r from-orange-400 to-orange-300 text-transparent bg-clip-text font-semibold">contract source code</a> with setup instructions. <br>
                    <span class="text-black font-semibold">
                        If your input is not valid, your will see error message with description of error
                    </span>
                </p>

                <!-- Current ID -->
                <div class="flex flex-col items-center mt-3">
                    <p class="inline-block bg-gradient-to-r from-orange-400 to-orange-300 text-transparent bg-clip-text text-sm font-semibold">Current ID</p>
                    <p class="text-center text-black text-sm font-semibold">“dev-1635829277525-2258924695353”</p>
                </div>

                <!-- Form -->
                <form action="" class="w-full">

                    <!-- Noraml input -->
                    <input type="text" placeholder="Set your contract ID" class="w-full h-14 mt-4 rounded-3xl outline-none border focus:border-blue-24 pl-7 pr-2 font-medium placeholder-gray-400">
                    
                    <!-- Error input -->
                    <div class="w-full mt-3 flex flex-col items-end">
                        <p class="mr-6 my-1 flex items-center text-sm text-red-24">
                            <svg xmlns="http://www.w3.org/2000/svg" class="mr-1" width="9" height="9" viewBox="0 0 9 9" fill="none">
                                <path d="M0.674265 2.32021C-0.957612 5.13891 1.07633 8.66667 4.33333 8.66667C7.59034 8.66667 9.62428 5.1389 7.9924 2.32021C6.3639 -0.492652 2.30276 -0.492651 0.674265 2.32021ZM5 6C5 6.36819 4.70152 6.66667 4.33333 6.66667C3.96514 6.66667 3.66667 6.36819 3.66667 6C3.66667 5.63181 3.96514 5.33333 4.33333 5.33333C4.70152 5.33333 5 5.63181 5 6ZM5 3.33333C5 3.70152 4.70152 4 4.33333 4C3.96514 4 3.66667 3.70152 3.66667 3.33333V2C3.66667 1.63181 3.96514 1.33333 4.33333 1.33333C4.70152 1.33333 5 1.63181 5 2V3.33333Z" fill="#F03738"/>
                            </svg>
                            An occured error
                        </p>
                        <input type="text" placeholder="Set your contract ID" class="w-full h-14 rounded-3xl outline-none border border-red-24 focus:border-red-24 pl-7 pr-2 font-medium placeholder-gray-400">
                    </div>

                    <!-- Normal deploy button -->
                    <button class="w-full h-16 mt-4 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5 transform active:scale-95 duration-100">
                        <div class="w-full h-full rounded-full bg-transparent hover:bg-white">
                            <p class="flex justify-center items-center h-full text-lg font-bold text-transparent bg-clip-text bg-gradient-to-r from-white to-white hover:from-orange-400 hover:text-orange-300">Deploy contract</p>
                        </div>
                    </button>

                    <!-- Blocked deploy button -->
                    <button class="opacity-50 cursor-not-allowed w-full h-16 mt-4 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5">
                        <div class="w-full h-full rounded-full bg-transparent">
                            <p class="flex justify-center items-center h-full text-lg font-bold text-transparent bg-clip-text bg-gradient-to-r from-white to-white ">Deploy contract</p>
                        </div>
                    </button>

                    <!-- Load deploy button -->
                    <button class="opacity-50 cursor-wait w-full h-16 mt-4 bg-gradient-to-r from-orange-400 to-orange-300 rounded-full p-0.5">
                        <div class="w-full h-full rounded-full bg-transparent">
                            <p class="flex justify-center items-center h-full text-lg font-bold text-transparent bg-clip-text bg-gradient-to-r from-white to-white ">
                                Deploy contract
                                <svg xmlns="http://www.w3.org/2000/svg" class="animate-spin" width="29" height="29" viewBox="0 0 29 29" fill="none">
                                    <g opacity="">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14.5004 9.51121C14.0163 9.51121 13.6201 9.11505 13.6201 8.63085V5.10942C13.6201 4.62523 14.0163 4.22906 14.5004 4.22906C14.9846 4.22906 15.3808 4.62523 15.3808 5.10942V8.63085C15.3808 9.11505 14.9846 9.51121 14.5004 9.51121Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M16.9948 10.1796C16.5755 9.93748 16.4305 9.39635 16.6726 8.97701L18.4333 5.92745C18.6754 5.50811 19.2165 5.36314 19.6359 5.60524C20.0552 5.84734 20.2002 6.38846 19.9581 6.80781L18.1974 9.85736C17.9553 10.2767 17.4141 10.4217 16.9948 10.1796Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M18.8208 12.0056C18.5787 11.5862 18.7236 11.0451 19.143 10.803L22.1925 9.04227C22.6119 8.80017 23.153 8.94514 23.3951 9.36448C23.6372 9.78383 23.4922 10.325 23.0729 10.567L20.0233 12.3278C19.604 12.5699 19.0629 12.4249 18.8208 12.0056Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M19.4891 14.4999C19.4891 14.0157 19.8853 13.6195 20.3695 13.6195H23.8909C24.3751 13.6195 24.7713 14.0157 24.7713 14.4999C24.7713 14.9841 24.3751 15.3803 23.8909 15.3803H20.3695C19.8853 15.3803 19.4891 14.9841 19.4891 14.4999Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M18.8208 16.9942C19.0629 16.5749 19.604 16.4299 20.0233 16.672L23.0729 18.4327C23.4922 18.6748 23.6372 19.216 23.3951 19.6353C23.153 20.0547 22.6119 20.1996 22.1925 19.9575L19.143 18.1968C18.7236 17.9547 18.5787 17.4136 18.8208 16.9942Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M16.9948 18.8202C17.4141 18.5781 17.9553 18.7231 18.1974 19.1424L19.9581 22.192C20.2002 22.6113 20.0552 23.1525 19.6359 23.3946C19.2165 23.6367 18.6754 23.4917 18.4333 23.0723L16.6726 20.0228C16.4305 19.6034 16.5755 19.0623 16.9948 18.8202Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M14.5004 19.4886C14.9846 19.4886 15.3808 19.8848 15.3808 20.3689V23.8904C15.3808 24.3746 14.9846 24.7707 14.5004 24.7707C14.0163 24.7707 13.6201 24.3746 13.6201 23.8904V20.3689C13.6201 19.8848 14.0163 19.4886 14.5004 19.4886Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12.0061 18.8202C12.4254 19.0623 12.5704 19.6034 12.3283 20.0228L10.5676 23.0723C10.3255 23.4917 9.78438 23.6367 9.36503 23.3946C8.94569 23.1525 8.80072 22.6113 9.04282 22.192L10.8035 19.1424C11.0456 18.7231 11.5868 18.5781 12.0061 18.8202Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M10.1801 16.9942C10.4222 17.4136 10.2773 17.9547 9.85791 18.1968L6.80836 19.9575C6.38901 20.1996 5.84789 20.0547 5.60579 19.6353C5.36369 19.216 5.50866 18.6748 5.928 18.4327L8.97756 16.672C9.3969 16.4299 9.93803 16.5749 10.1801 16.9942Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M9.51176 14.4999C9.51176 14.9841 9.1156 15.3803 8.6314 15.3803H5.10997C4.62578 15.3803 4.22961 14.9841 4.22961 14.4999C4.22961 14.0157 4.62578 13.6195 5.10997 13.6195H8.6314C9.1156 13.6195 9.51176 14.0157 9.51176 14.4999Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M10.1801 12.0056C9.93803 12.4249 9.3969 12.5699 8.97756 12.3278L5.928 10.567C5.50866 10.325 5.36369 9.78383 5.60579 9.36448C5.84789 8.94514 6.38901 8.80017 6.80836 9.04227L9.85791 10.803C10.2773 11.0451 10.4222 11.5862 10.1801 12.0056Z" fill="white"/>
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12.0061 10.1796C11.5868 10.4217 11.0456 10.2767 10.8035 9.85736L9.04282 6.80781C8.80072 6.38846 8.94569 5.84734 9.36503 5.60524C9.78438 5.36314 10.3255 5.50811 10.5676 5.92745L12.3283 8.97701C12.5704 9.39635 12.4254 9.93748 12.0061 10.1796Z" fill="white"/>
                                    </g>
                                </svg>
                                </p>
                        </div>
                    </button>

                    <!-- Normal cancele deployment button -->
                    <button class="w-full h-16 flex items-center justify-center mt-4 rounded-full border border-red-24 hover:bg-red-24 font-bold text-lg text-red-24 hover:text-white transform active:scale-95 duration-100">
                        Cancel deployment
                    </button>

                    <!-- Blocked cancele deployment button -->
                    <button class="opacity-50 cursor-not-allowed w-full h-16 flex items-center justify-center mt-4 rounded-full border border-red-24 bg-red-24 font-bold text-lg text-white transform active:scale-95 duration-100">
                        Cancel deployment
                    </button>

                    <!-- Blocked cancele deployment button -->
                    <button class="opacity-50 cursor-wait w-full h-16 flex items-center justify-center mt-4 rounded-full border border-red-24 bg-red-24 font-bold text-lg text-white transform active:scale-95 duration-100">
                        Cancel deployment
                        <svg xmlns="http://www.w3.org/2000/svg" class="animate-spin" width="29" height="29" viewBox="0 0 29 29" fill="none">
                            <g opacity="">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M14.5004 9.51121C14.0163 9.51121 13.6201 9.11505 13.6201 8.63085V5.10942C13.6201 4.62523 14.0163 4.22906 14.5004 4.22906C14.9846 4.22906 15.3808 4.62523 15.3808 5.10942V8.63085C15.3808 9.11505 14.9846 9.51121 14.5004 9.51121Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M16.9948 10.1796C16.5755 9.93748 16.4305 9.39635 16.6726 8.97701L18.4333 5.92745C18.6754 5.50811 19.2165 5.36314 19.6359 5.60524C20.0552 5.84734 20.2002 6.38846 19.9581 6.80781L18.1974 9.85736C17.9553 10.2767 17.4141 10.4217 16.9948 10.1796Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M18.8208 12.0056C18.5787 11.5862 18.7236 11.0451 19.143 10.803L22.1925 9.04227C22.6119 8.80017 23.153 8.94514 23.3951 9.36448C23.6372 9.78383 23.4922 10.325 23.0729 10.567L20.0233 12.3278C19.604 12.5699 19.0629 12.4249 18.8208 12.0056Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M19.4891 14.4999C19.4891 14.0157 19.8853 13.6195 20.3695 13.6195H23.8909C24.3751 13.6195 24.7713 14.0157 24.7713 14.4999C24.7713 14.9841 24.3751 15.3803 23.8909 15.3803H20.3695C19.8853 15.3803 19.4891 14.9841 19.4891 14.4999Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M18.8208 16.9942C19.0629 16.5749 19.604 16.4299 20.0233 16.672L23.0729 18.4327C23.4922 18.6748 23.6372 19.216 23.3951 19.6353C23.153 20.0547 22.6119 20.1996 22.1925 19.9575L19.143 18.1968C18.7236 17.9547 18.5787 17.4136 18.8208 16.9942Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M16.9948 18.8202C17.4141 18.5781 17.9553 18.7231 18.1974 19.1424L19.9581 22.192C20.2002 22.6113 20.0552 23.1525 19.6359 23.3946C19.2165 23.6367 18.6754 23.4917 18.4333 23.0723L16.6726 20.0228C16.4305 19.6034 16.5755 19.0623 16.9948 18.8202Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M14.5004 19.4886C14.9846 19.4886 15.3808 19.8848 15.3808 20.3689V23.8904C15.3808 24.3746 14.9846 24.7707 14.5004 24.7707C14.0163 24.7707 13.6201 24.3746 13.6201 23.8904V20.3689C13.6201 19.8848 14.0163 19.4886 14.5004 19.4886Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M12.0061 18.8202C12.4254 19.0623 12.5704 19.6034 12.3283 20.0228L10.5676 23.0723C10.3255 23.4917 9.78438 23.6367 9.36503 23.3946C8.94569 23.1525 8.80072 22.6113 9.04282 22.192L10.8035 19.1424C11.0456 18.7231 11.5868 18.5781 12.0061 18.8202Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M10.1801 16.9942C10.4222 17.4136 10.2773 17.9547 9.85791 18.1968L6.80836 19.9575C6.38901 20.1996 5.84789 20.0547 5.60579 19.6353C5.36369 19.216 5.50866 18.6748 5.928 18.4327L8.97756 16.672C9.3969 16.4299 9.93803 16.5749 10.1801 16.9942Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M9.51176 14.4999C9.51176 14.9841 9.1156 15.3803 8.6314 15.3803H5.10997C4.62578 15.3803 4.22961 14.9841 4.22961 14.4999C4.22961 14.0157 4.62578 13.6195 5.10997 13.6195H8.6314C9.1156 13.6195 9.51176 14.0157 9.51176 14.4999Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M10.1801 12.0056C9.93803 12.4249 9.3969 12.5699 8.97756 12.3278L5.928 10.567C5.50866 10.325 5.36369 9.78383 5.60579 9.36448C5.84789 8.94514 6.38901 8.80017 6.80836 9.04227L9.85791 10.803C10.2773 11.0451 10.4222 11.5862 10.1801 12.0056Z" fill="white"/>
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M12.0061 10.1796C11.5868 10.4217 11.0456 10.2767 10.8035 9.85736L9.04282 6.80781C8.80072 6.38846 8.94569 5.84734 9.36503 5.60524C9.78438 5.36314 10.3255 5.50811 10.5676 5.92745L12.3283 8.97701C12.5704 9.39635 12.4254 9.93748 12.0061 10.1796Z" fill="white"/>
                            </g>
                        </svg>
                    </button>

                </form>
        </div>
    </div>
</template>