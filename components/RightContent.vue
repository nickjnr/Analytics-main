<template>
    <div class="sticky w-[24rem] h-screen bg-[#F1EEF6] rounded-2xl p-5 space-y-3 mb-12 sm:mb-0">
        <div class="bg-white flex items-center space-x-2 p-3 rounded-2xl">
            <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M18.5 15.7076L20.4217 17.6292C21.1928 18.4004 21.1928 19.6506 20.4217 20.4217C19.6506 21.1928 18.4004 21.1928 17.6293 20.4217L15.7076 18.5M1 9.5C1 4.80558 4.80558 1 9.5 1C14.1944 1 18 4.80558 18 9.5C18 14.1944 14.1944 18 9.5 18C4.80558 18 1 14.1944 1 9.5Z"
                    stroke="#757575" stroke-width="2" stroke-linecap="round" />
            </svg>
            <input type="text" placeholder="Search here..." class="w-full bg-transparent outline-none border-0">
        </div>
        <div class="bg-white p-1 rounded-lg space-y-3">
            <div class="bg-[#F1EEF6] p-3 text-sm rounded-lg space-y-3">
                <div class="flex items-center justify-between ">
                    <p class="text-md font-semibold">September</p>
                    <button class="block bg-white px-2 py-1 text-[#5534A5] font-semibold rounded-xl">
                        + Add Task
                    </button>
                </div>
                <div class="flex items-center space-x-2 text-xs justify-between">
                    <div class="flex flex-col items-center">
                        <p class="font-bold">3</p>
                        <p class="text-[#757575]">mon</p>
                    </div>
                    <div class="flex flex-col items-center bg-[#5534A5] text-white p-1 rounded-md">
                        <p class="font-bold">4</p>
                        <p class="">tue</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <p class="font-bold">5</p>
                        <p class="text-[#757575]">wed</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <p class="font-bold">6</p>
                        <p class="text-[#757575]">thu</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <p class="font-bold">7</p>
                        <p class="text-[#757575]">fri</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <p class="font-bold">8</p>
                        <p class="text-[#757575]">sat</p>
                    </div>
                </div>
            </div>
            <div class="text-xs p-2">
                <div class="space-y-4">
                    <div class="flex items-center space-x-3">
                        <p>09:00</p>
                        <div class="h-[0.1rem] w-full bg-[#EAEAEA]"></div>
                    </div>
                    <div class="flex items-center space-x-3">
                        <p>10:00</p>
                        <div class="flex items-center w-full">
                            <div class="h-[0.1rem] w-3 bg-[#EAEAEA]"></div>
                            <div class="w-full border-l-4 border-l-[#5534A5] border rounded-r-xl p-3 space-y-2">
                                <div class="flex items-center justify-between">
                                    <p class="text-md font-bold">UI Motion</p>
                                    <svg width="16" height="4" viewBox="0 0 16 4" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <circle cx="2" cy="2" r="2" fill="black" />
                                        <circle cx="8" cy="2" r="2" fill="black" />
                                        <circle cx="14" cy="2" r="2" fill="black" />
                                    </svg>
                                </div>
                                <p class="text-[#757575] text-[0.7rem]">10:00am - 12:00pm</p>
                            </div>
                        </div>
                    </div>
                    <div class="flex items-center space-x-3">
                        <p>11:00</p>
                        <div class="h-[0.1rem] w-full bg-[#EAEAEA]"></div>
                    </div>
                    <div class="flex items-center space-x-3">
                        <p>12:00</p>
                        <div class="flex items-center w-full">
                            <div class="h-[0.1rem] w-3 bg-[#EAEAEA]"></div>
                            <div class="w-full border-l-4 border-l-[#5534A5] border rounded-r-xl p-3 space-y-2">
                                <div class="flex items-center justify-between">
                                    <p class="text-md font-bold">UI Design</p>
                                    <svg width="16" height="4" viewBox="0 0 16 4" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <circle cx="2" cy="2" r="2" fill="black" />
                                        <circle cx="8" cy="2" r="2" fill="black" />
                                        <circle cx="14" cy="2" r="2" fill="black" />
                                    </svg>
                                </div>
                                <p class="text-[#757575] text-[0.7rem]">12:00pm - 01:00pm</p>
                            </div>
                        </div>
                    </div>
                    <div class="flex items-center space-x-3">
                        <p>01:00</p>
                        <div class="h-[0.1rem] w-full bg-[#EAEAEA]"></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-white p-3 text-sm rounded-lg space-y-3 mb-4">
            <p class="font-bold text-md">Assignments <span class="text-[#757575] text-xs">(12)</span></p>
            <div class="flex items-center space-x-2">
                <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                        d="M10.038 0C12.411 0 14 1.666 14 4.144V9.8637C14 12.334 12.411 14 10.038 14H3.969C1.596 14 0 12.334 0 9.8637V4.144C0 1.666 1.596 0 3.969 0H10.038ZM9.926 4.9C9.688 4.662 9.296 4.662 9.058 4.9L6.167 7.791L4.942 6.566C4.704 6.328 4.312 6.328 4.074 6.566C3.836 6.804 3.836 7.189 4.074 7.434L5.74 9.093C5.859 9.212 6.013 9.268 6.167 9.268C6.328 9.268 6.482 9.212 6.601 9.093L9.926 5.768C10.164 5.53 10.164 5.145 9.926 4.9Z"
                        fill="#6FDFDF" />
                </svg>
                <p class="text-[0.7rem]">2/5 completed</p>
            </div>
            <div class="space-y-4">
                <div class="flex items-center space-x-2">
                    <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M15.7674 0C19.4953 0 22 2.6158 22 6.5076V15.4924C22 19.3842 19.4953 22 15.7663 22H6.2315C2.5036 22 0 19.3842 0 15.4924V6.5076C0 2.6158 2.5036 0 6.2315 0H15.7674ZM15.7674 1.65H6.2315C3.4485 1.65 1.65 3.5563 1.65 6.5076V15.4924C1.65 18.4437 3.4485 20.35 6.2315 20.35H15.7663C18.5504 20.35 20.35 18.4437 20.35 15.4924V6.5076C20.35 3.5563 18.5504 1.65 15.7674 1.65ZM15.4985 7.8067C15.8208 8.129 15.8208 8.6504 15.4985 8.9727L10.2779 14.1933C10.1173 14.355 9.90605 14.4353 9.69485 14.4353C9.48475 14.4353 9.27245 14.355 9.11185 14.1933L6.50045 11.583C6.17815 11.2607 6.17815 10.7393 6.50045 10.417C6.82275 10.0947 7.34415 10.0947 7.66645 10.417L9.69485 12.4432L14.3324 7.8067C14.6547 7.4844 15.1762 7.4844 15.4985 7.8067Z"
                            fill="#5534A5" />
                    </svg>
                    <div class="w-full space-y-1">
                        <div class="flex items-center justify-between">
                            <p class="font-bold">Colour Theory</p>
                            <p class="font-bold">86/100</p>
                        </div>
                        <div class="flex items-center justify-between">
                            <p class="text-[#757575] text-[0.7rem]">01 Sep 2022</p>
                            <p class="text-[#757575] text-[0.7rem]">Grade</p>
                        </div>
                    </div>
                </div>
                <div class="flex items-center space-x-2">
                    <svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M15.7674 0C19.4953 0 22 2.6158 22 6.5076V15.4924C22 19.3842 19.4953 22 15.7663 22H6.2315C2.5036 22 0 19.3842 0 15.4924V6.5076C0 2.6158 2.5036 0 6.2315 0H15.7674ZM15.7674 1.65H6.2315C3.4485 1.65 1.65 3.5563 1.65 6.5076V15.4924C1.65 18.4437 3.4485 20.35 6.2315 20.35H15.7663C18.5504 20.35 20.35 18.4437 20.35 15.4924V6.5076C20.35 3.5563 18.5504 1.65 15.7674 1.65ZM15.4985 7.8067C15.8208 8.129 15.8208 8.6504 15.4985 8.9727L10.2779 14.1933C10.1173 14.355 9.90605 14.4353 9.69485 14.4353C9.48475 14.4353 9.27245 14.355 9.11185 14.1933L6.50045 11.583C6.17815 11.2607 6.17815 10.7393 6.50045 10.417C6.82275 10.0947 7.34415 10.0947 7.66645 10.417L9.69485 12.4432L14.3324 7.8067C14.6547 7.4844 15.1762 7.4844 15.4985 7.8067Z"
                            fill="#5534A5" />
                    </svg>
                    <div class="w-full space-y-1">
                        <div class="flex items-center justify-between">
                            <p class="font-bold">Design system</p>
                            <p class="font-bold">90/100</p>
                        </div>
                        <div class="flex items-center justify-between">
                            <p class="text-[#757575] text-[0.7rem]">01 Sep 2022</p>
                            <p class="text-[#757575] text-[0.7rem]">Grade</p>
                        </div>
                    </div>
                </div>
                <div class="flex items-center space-x-2">
                    <svg width="23" height="22" viewBox="0 0 23 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M16.2589 0C20.103 0 22.6857 2.6158 22.6857 6.5076V15.4924C22.6857 19.3842 20.103 22 16.2577 22H6.42573C2.58164 22 0 19.3842 0 15.4924V6.5076C0 2.6158 2.58164 0 6.42573 0H16.2589ZM16.2589 1.65H6.42573C3.55599 1.65 1.70143 3.5563 1.70143 6.5076V15.4924C1.70143 18.4437 3.55599 20.35 6.42573 20.35H16.2577C19.1286 20.35 20.9843 18.4437 20.9843 15.4924V6.5076C20.9843 3.5563 19.1286 1.65 16.2589 1.65Z"
                            fill="#EAEAEA" />
                    </svg>
                    <div class="w-full space-y-1">
                        <div class="flex items-center justify-between">
                            <p class="font-bold">User persona</p>
                            <p class="font-bold">0 /100</p>
                        </div>
                        <div class="flex items-center justify-between">
                            <p class="text-[#757575] text-[0.7rem]">03 Sep 2022</p>
                            <p class="text-[#757575] text-[0.7rem]">To Do</p>
                        </div>
                    </div>
                </div>
                <div class="flex items-center space-x-2">
                    <svg width="23" height="22" viewBox="0 0 23 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd"
                            d="M16.2589 0C20.103 0 22.6857 2.6158 22.6857 6.5076V15.4924C22.6857 19.3842 20.103 22 16.2577 22H6.42573C2.58164 22 0 19.3842 0 15.4924V6.5076C0 2.6158 2.58164 0 6.42573 0H16.2589ZM16.2589 1.65H6.42573C3.55599 1.65 1.70143 3.5563 1.70143 6.5076V15.4924C1.70143 18.4437 3.55599 20.35 6.42573 20.35H16.2577C19.1286 20.35 20.9843 18.4437 20.9843 15.4924V6.5076C20.9843 3.5563 19.1286 1.65 16.2589 1.65Z"
                            fill="#EAEAEA" />
                    </svg>
                    <div class="w-full space-y-1">
                        <div class="flex items-center justify-between">
                            <p class="font-bold">Prototyping</p>
                            <p class="font-bold">0 /100</p>
                        </div>
                        <div class="flex items-center justify-between">
                            <p class="text-[#757575] text-[0.7rem]">06 Sep 2022</p>
                            <p class="text-[#757575] text-[0.7rem]">To Do</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</div></template>
