<template>
    <div class="text-gray-900 text-sm">
        <nav class="bg-gray-900 text-white px-4 py-3 flex items-center justify-between">
            <div class="flex items-center space-x-4">
                <a href="#" class="text-white hover:text-gray-400">
                    <svg class=" w-8 fill-current" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
                </a>
                <div class="relative hidden lg:block">
                    <input type="text" class="rounded bg-gray-700 placeholder-white w-72 px-3 py-1" placeholder="Search or jump to...">
                    <div class="absolute flex h-full items-center right-0 top-0 ">
                        <div class="border border-gray-600 mr-2 px-2 rounded text-gray-400 text-xs">/</div>
                    </div>
                </div>
                <ul class="hidden lg:flex items-center font-semibold space-x-4">
                    <li class="hover:text-gray-400 cursor-pointer">Pull Requests</li>
                    <li class="hover:text-gray-400 cursor-pointer">Issues</li>
                    <li class="hover:text-gray-400 cursor-pointer">Marketplace</li>
                    <li class="hover:text-gray-400 cursor-pointer">Explore</li>
                </ul>
            </div>
            <div class="flex items-center space-x-4 text-white">
                <a href="#" class="relative hover:text-gray-400">
                    <svg class="w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path></svg>
                    <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
                </a>
                <a href="#" class="flex items-center hover:text-gray-400">
                    <svg class="w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path></svg>
                    <svg class="w-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </a>
                <a href="#" class="flex items-center hover:text-gray-400">
                    <img class="rounded-full w-5 h-5" src="https://avatars.githubusercontent.com/u/59318027?s=60&v=4" alt="">
                    <svg class="w-3 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </a>
            </div>
        </nav> <!-- end main nav -->

        <div class="repo-stats flex flex-col lg:flex-row items-center justify-between px-8 py-4">
            <div class="flex items-center">
                <svg class="w-4 mt-1 fill-current text-gray-600" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"></path></svg>
                <div class="flex items-center text-xl ml-2">
                    <a href="#" class="text-blue-600 hover:underline">tailwindcss</a>
                    <span class="ml-1">/</span>
                    <a href="#" class="text-blue-600 hover:underline font-semibold ml-1">tailwindcss</a>
                </div>
            </div>
            <div class="flex space-x-2 mt-4 lg:mt-0">
                <div class="flex text-xs">
                    <button class="border border-gray-400 px-3 py-1 rounded rounded-r-none flex items-center space-x-1">
                        <svg class="" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path></svg>
                        <div>Watch</div>
                        <svg class="" height="10" width="14" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </button>
                    <a href="#" class="border border-gray-400 border-l-0 font-semibold hover:text-blue-600 px-3 py-1 rounded rounded-l-none">430</a>
                </div>
                <div class="flex text-xs">
                    <button class="border border-gray-400 px-3 py-1 rounded rounded-r-none flex items-center space-x-1">
                        <svg class="" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25z"></path></svg>
                        <div>Unstar</div>
                    </button>
                    <a href="#" class="border border-gray-400 border-l-0 font-semibold hover:text-blue-600 px-3 py-1 rounded rounded-l-none">25.7k</a>
                </div>
                <div class="flex text-xs">
                    <button class="border border-gray-400 px-3 py-1 rounded rounded-r-none flex items-center space-x-1">
                        <svg class="" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path></svg>
                        <div>Fork</div>
                    </button>
                    <a href="#" class="border border-gray-400 border-l-0 font-semibold hover:text-blue-600 px-3 py-1 rounded rounded-l-none">430</a>
                </div>
            </div>
        </div> <!-- end repo-stats -->

        <ul class="repo-nav border-b border-gray-400 flex items-center px-8 mt-4">
            <li class="font-semibold"> 
                <a href="#" class="flex items-center border-b-2 border-red-500 px-3 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"></path></svg>
                    <span class="ml-2">Code</span>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm9 3a1 1 0 11-2 0 1 1 0 012 0zm-.25-6.25a.75.75 0 00-1.5 0v3.5a.75.75 0 001.5 0v-3.5z"></path></svg>
                    <span class="ml-2">Issues</span>
                    <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">106</div>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path></svg>
                    <span class="ml-2">Pull requests</span>
                    <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1">16</div>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="hidden lg:flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"></path></svg>
                    <span class="ml-2">Actions</span>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="hidden lg:flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M1.75 0A1.75 1.75 0 000 1.75v12.5C0 15.216.784 16 1.75 16h12.5A1.75 1.75 0 0016 14.25V1.75A1.75 1.75 0 0014.25 0H1.75zM1.5 1.75a.25.25 0 01.25-.25h12.5a.25.25 0 01.25.25v12.5a.25.25 0 01-.25.25H1.75a.25.25 0 01-.25-.25V1.75zM11.75 3a.75.75 0 00-.75.75v7.5a.75.75 0 001.5 0v-7.5a.75.75 0 00-.75-.75zm-8.25.75a.75.75 0 011.5 0v5.5a.75.75 0 01-1.5 0v-5.5zM8 3a.75.75 0 00-.75.75v3.5a.75.75 0 001.5 0v-3.5A.75.75 0 008 3z"></path></svg>
                    <span class="ml-2">Projects</span>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="hidden lg:flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path></svg>
                    <span class="ml-2">Wiki</span>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="hidden lg:flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"></path></svg>
                    <span class="ml-2">Security</span>
                </a>
            </li>
            <li class=""> 
                <a href="#" class="hidden lg:flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-in-out duration-150 px-4 pb-3">
                    <svg class="w-4" viewBox="0 0 16 16" aria-hidden="true"><path fill-rule="evenodd" d="M7.429 1.525a6.593 6.593 0 011.142 0c.036.003.108.036.137.146l.289 1.105c.147.56.55.967.997 1.189.174.086.341.183.501.29.417.278.97.423 1.53.27l1.102-.303c.11-.03.175.016.195.046.219.31.41.641.573.989.014.031.022.11-.059.19l-.815.806c-.411.406-.562.957-.53 1.456a4.588 4.588 0 010 .582c-.032.499.119 1.05.53 1.456l.815.806c.08.08.073.159.059.19a6.494 6.494 0 01-.573.99c-.02.029-.086.074-.195.045l-1.103-.303c-.559-.153-1.112-.008-1.529.27-.16.107-.327.204-.5.29-.449.222-.851.628-.998 1.189l-.289 1.105c-.029.11-.101.143-.137.146a6.613 6.613 0 01-1.142 0c-.036-.003-.108-.037-.137-.146l-.289-1.105c-.147-.56-.55-.967-.997-1.189a4.502 4.502 0 01-.501-.29c-.417-.278-.97-.423-1.53-.27l-1.102.303c-.11.03-.175-.016-.195-.046a6.492 6.492 0 01-.573-.989c-.014-.031-.022-.11.059-.19l.815-.806c.411-.406.562-.957.53-1.456a4.587 4.587 0 010-.582c.032-.499-.119-1.05-.53-1.456l-.815-.806c-.08-.08-.073-.159-.059-.19a6.44 6.44 0 01.573-.99c.02-.029.086-.075.195-.045l1.103.303c.559.153 1.112.008 1.529-.27.16-.107.327-.204.5-.29.449-.222.851-.628.998-1.189l.289-1.105c.029-.11.101-.143.137-.146zM8 0c-.236 0-.47.01-.701.03-.743.065-1.29.615-1.458 1.261l-.29 1.106c-.017.066-.078.158-.211.224a5.994 5.994 0 00-.668.386c-.123.082-.233.09-.3.071L3.27 2.776c-.644-.177-1.392.02-1.82.63a7.977 7.977 0 00-.704 1.217c-.315.675-.111 1.422.363 1.891l.815.806c.05.048.098.147.088.294a6.084 6.084 0 000 .772c.01.147-.038.246-.088.294l-.815.806c-.474.469-.678 1.216-.363 1.891.2.428.436.835.704 1.218.428.609 1.176.806 1.82.63l1.103-.303c.066-.019.176-.011.299.071.213.143.436.272.668.386.133.066.194.158.212.224l.289 1.106c.169.646.715 1.196 1.458 1.26a8.094 8.094 0 001.402 0c.743-.064 1.29-.614 1.458-1.26l.29-1.106c.017-.066.078-.158.211-.224a5.98 5.98 0 00.668-.386c.123-.082.233-.09.3-.071l1.102.302c.644.177 1.392-.02 1.82-.63.268-.382.505-.789.704-1.217.315-.675.111-1.422-.364-1.891l-.814-.806c-.05-.048-.098-.147-.088-.294a6.1 6.1 0 000-.772c-.01-.147.039-.246.088-.294l.814-.806c.475-.469.679-1.216.364-1.891a7.992 7.992 0 00-.704-1.218c-.428-.609-1.176-.806-1.82-.63l-1.103.303c-.066.019-.176.011-.299-.071a5.991 5.991 0 00-.668-.386c-.133-.066-.194-.158-.212-.224L10.16 1.29C9.99.645 9.444.095 8.701.031A8.094 8.094 0 008 0zm1.5 8a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM11 8a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                    <span class="ml-2">Settings</span>
                </a>
            </li>
        </ul> <!-- end repo nav -->

        <div class="container mx-auto my-8 px-4 lg:px-32 flex flex-col lg:flex-row">
            <div class="file-explorer-container w-full lg:w-3/4 lg:mr-8">
                <div class="branch-navigation flex items-center justify-between">
                    <div class="flex items-center space-x-3">
                        <button class="border border-gray-400 rounded-md px-4 py-1 hover:bg-gray-200 flex items-center space-x-2">
                            <svg class="" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
                            <div class="font-semibold">master</div>
                            <svg class="w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </button>
                        <a href="#" class="hidden lg:flex items-center space-x-2 px-3 py-1 group">
                            <svg class="fill-current text-gray-600 group-hover:text-blue-500" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path></svg>
                            <span class="group-hover:text-blue-500">
                                <span class="font-semibold">25</span>
                                <span class="text-gray-600">branches</span>
                            </span>
                        </a>
                        <a href="#" class="hidden lg:flex items-center space-x-2 px-3 py-1 group">
                            <svg class="fill-current text-gray-600 group-hover:text-blue-500" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path></svg>
                            <span class="group-hover:text-blue-500">
                                <span class="font-semibold">79</span>
                                <span class="text-gray-600">tags</span>
                            </span>
                        </a>
                    </div>
                    <div class="hidden lg:flex items-center space-x-2">
                        <button class="border border-gray-400 text-gray-900 px-3 py-1 rounded-md flex items-center space-x-2">
                            <div class="font-bold">Go to file</div>
                        </button>
                        <button class="border border-gray-400 text-gray-900 px-3 py-1 rounded-md flex items-center space-x-2">
                            <div class="font-bold">Add file</div>
                            <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </button>
                        <button class="border border-green-600 text-white px-3 py-1 rounded-md bg-green-600 hover:bg-green-700 flex items-center space-x-2">
                            <svg class="fill-current text-gray-200" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.47 10.78a.75.75 0 001.06 0l3.75-3.75a.75.75 0 00-1.06-1.06L8.75 8.44V1.75a.75.75 0 00-1.5 0v6.69L4.78 5.97a.75.75 0 00-1.06 1.06l3.75 3.75zM3.75 13a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5z"></path></svg>
                            <div class="font-semibold">Code</div>
                            <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                        </button>
                    </div>
                </div> <!-- end branch-navigation -->
                <div class="commits-container bg-blue-100 rounded-md rounded-b-none border border-blue-200 border-b-0 flex items-center justify-between px-4 py-4 mt-5">
                    <div class="flex items-center space-x-2">
                        <a href=""><img height="24" width="24" alt="@SukhrobNuraliev" src="https://avatars.githubusercontent.com/u/59318027?s=60&amp;u=cd4bb5b7dabf41c1566a7334ecc3ea43f8180116&amp;v=4" class="avatar-user rounded-full"></a>
                        <a href="#" class="font-semibold hover:underline">SukhrobNuraliev</a>
                        <a href="#" class="hover:text-blue-600 hover:underline">2.0.1</a>
                    </div>
                    <div class="flex items-end">
                        <a href="#">
                            <svg aria-label="2 / 2 checks OK" class="octicon octicon-check" viewBox="0 0 16 16" version="1.1" width="16" height="16" role="img"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                        </a>
                        <a href="#" class="font-mono hover:text-blue-500 hover:underline ml-1 text-gray-600 text-xs hidden lg:block">da080bd</a>
                        <a href="#" class="hover:text-blue-500 hover:underline ml-2 text-gray-600">4 days ago</a>
                        <a href="#" class="flex items-center ml-3">
                            <svg class="fill-current text-gray-600 " height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"></path></svg>
                            <span class="">
                                <span class="font-semibold ml-1">12</span>
                                <span class="hidden lg:inline">commits</span>
                            </span>
                        </a>
                    </div>
                </div> <!-- end commits-container -->
                <div class="file-explorer rounded-md rounded-t-none border border-gray-300 text-gray-700 divide-y divide-gray-300">
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="Directory" class="fill-current octicon octicon-file-directory text-blue-400 text-color-icon-directory" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">.github</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem, ipsum dolor.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">4 days ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="Directory" class="fill-current octicon octicon-file-directory text-blue-400 text-color-icon-directory" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">__tests__</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem, ipsum.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">2 weeks ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="Directory" class="fill-current octicon octicon-file-directory text-blue-400 text-color-icon-directory" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">dist</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">16 days ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="Directory" class="fill-current octicon octicon-file-directory text-blue-400 text-color-icon-directory" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">jest</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem, ipsum dolor. Lorem, ipsum.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">4 months ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="Directory" class="fill-current octicon octicon-file-directory text-blue-400 text-color-icon-directory" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M1.75 1A1.75 1.75 0 000 2.75v10.5C0 14.216.784 15 1.75 15h12.5A1.75 1.75 0 0016 13.25v-8.5A1.75 1.75 0 0014.25 3h-6.5a.25.25 0 01-.2-.1l-.9-1.2c-.33-.44-.85-.7-1.4-.7h-3.5z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">scripts</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem, ipsum dolor Lorem, ipsum dolor.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">5 months ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">.editconfig</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">6 months ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">.eslintignore</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit amet.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">14 days ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">plugin.js</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum, dolor sit amet consectetur adipisicing.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">2 weeks ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">README.md</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit amet.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">4 months ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">tailwind.css</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic, minima! Provident.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">5 months ago</div>
                    </div>
                    <div class="flex justify-between px-4 py-2 hover:bg-gray-100">
                        <div class="w-4/12 flex items-center">
                            <svg aria-label="File" class="fill-current octicon octicon-file text-gray-600 text-gray-light" height="16" viewBox="0 0 16 16" version="1.1" width="16" role="img"><path fill-rule="evenodd" d="M3.75 1.5a.25.25 0 00-.25.25v11.5c0 .138.112.25.25.25h8.5a.25.25 0 00.25-.25V6H9.75A1.75 1.75 0 018 4.25V1.5H3.75zm5.75.56v2.19c0 .138.112.25.25.25h2.19L9.5 2.06zM2 1.75C2 .784 2.784 0 3.75 0h5.086c.464 0 .909.184 1.237.513l3.414 3.414c.329.328.513.773.513 1.237v8.086A1.75 1.75 0 0112.25 15h-8.5A1.75 1.75 0 012 13.25V1.75z"></path></svg>
                            <a href="#" class="ml-2 hover:underline hover:text-blue-600">package.json</a>
                        </div>
                        <div class="w-6/12"><a href="#" class="truncate hidden lg:block hover:underline hover:text-blue-600">Lorem ipsum dolor sit amet.</a></div>
                        <div class="w-4/12 lg:w-2/12 text-right">6 months ago</div>
                    </div>
                </div> <!-- end file-explorer -->
                <div class="readme-container rounded-md border border-gray-300 px-4 py-4 mt-4">
                    <h4 class="font-semibold">README.md</h4>
                    <div v-html="readme" class="prose max-w-none"></div>
                </div>
            </div>
            <div class="sidebar w-full lg:w-1/4 pr-4">
                <div class="about mt-4 lg:mt-0">
                    <h4 class="text-base font-semibold">About</h4>
                    <p>A utility-first CSS framework for rapid UI development.</p>

                    <div class="flex items-center space-x-1 mt-4">
                        <svg class="octicon octicon-link flex-shrink-0 mr-2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>
                        <a class="text-blue-600 hover:underline font-semibold" href="#">tailwindcss.com</a>
                    </div>

                    <div class="flex flex-wrap font-semibold items-center mt-2 tags text-xs">
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">tailwindcss</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">css</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">css-framework</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">postcss</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">functional-css</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">utility-classes</a>
                        <a href="#" class="bg-blue-100 hover:bg-blue-200 mr-2 mt-2 px-2 py-1 rounded-full text-blue-600">responsive</a>
                    </div>

                    <div class="flex items-center space-x-1 mt-4 group">
                        <svg class="group-hover:text-blue-400 fill-current octicon octicon-book mr-2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"></path></svg>
                        <a class="group-hover:text-blue-400 font-medium text-gray-500" href="#">Readme</a>
                    </div>
                    <div class="flex items-center space-x-1 mt-4 group">
                        <svg class="group-hover:text-blue-400 fill-current octicon octicon-law mr-2" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"></path></svg>
                        <a class="group-hover:text-blue-400 font-medium text-gray-500" href="#">MIT License</a>
                    </div>
                </div> <!-- /about -->
                <div class="releases border-t border-gray-400 mt-6 pt-6">
                    <h4 class="text-base font-semibold flex items-center">
                        <span>Releases</span>
                        <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1 mt-1">79</div>
                    </h4>

                    <a href="#" class="flex items-start mt-4 group">
                        <svg class="octicon octicon-tag flex-shrink-0 mt-1 text-green" height="16" viewBox="0 0 16 16" version="1.1" width="16" aria-hidden="true"><path fill-rule="evenodd" d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"></path></svg>
                        <span class="ml-2">
                            <span class="font-semibold group-hover:text-blue-600">v1.5.1</span>
                            <span class="border border-green-500 font-semibold ml-1 px-2 rounded-full text-green-600 text-xs">Latest</span>
                            <span class="block text-xs group-hover:text-blue-600">6 days ago</span>
                        </span>
                    </a>

                    <div class="mt-4">
                        <a href="#" class="text-blue-600 hover:underline text-xs">+ 78 releases</a>
                    </div>

                </div> <!-- /releases -->
                <div class="used-by border-t border-gray-400 mt-6 pt-6">
                    <h4 class="text-base font-semibold flex items-center">
                        <span>Used by</span>
                        <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1 mt-1">5,000+</div>
                    </h4>

                    <div class="mt-4">
                        <a href="#" class="flex items-center -space-x-3">
                            <img src="https://randomuser.me/api/portraits/men/97.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://randomuser.me/api/portraits/men/86.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://uifaces.co/our-content/donated/rSuiu_Hr.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://randomuser.me/api/portraits/men/86.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://randomuser.me/api/portraits/men/97.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://uifaces.co/our-content/donated/1H_7AxP0.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg?crop=faces&fit=crop&h=200&w=200&auto=compress&cs=tinysrgb" class="w-8 border-2 border-white rounded-full" alt="">
                            <img src="https://uifaces.co/our-content/donated/rSuiu_Hr.jpg" class="w-8 border-2 border-white rounded-full" alt="">
                            <span class="text-xs text-blue-600 font-semibold hover:underline" style="margin-left:0.5rem">+ 58,357</span>
                        </a>
                    </div>

                </div> <!-- /used-by -->
                <div class="contributors border-t border-gray-400 mt-6 pt-6">
                    <h4 class="text-base font-semibold flex items-center">
                        <span>Contributors</span>
                        <div class="text-xs rounded-lg bg-gray-300 px-2 ml-1 mt-1">115</div>
                    </h4>

                    <div class="flex items-center flex-wrap mt-2">
                        <a href="#"><img src="https://randomuser.me/api/portraits/men/97.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://randomuser.me/api/portraits/men/86.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://randomuser.me/api/portraits/men/97.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://uifaces.co/our-content/donated/rSuiu_Hr.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://uifaces.co/our-content/donated/1H_7AxP0.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://randomuser.me/api/portraits/men/97.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://uifaces.co/our-content/donated/1H_7AxP0.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://uifaces.co/our-content/donated/1H_7AxP0.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                        <a href="#"><img src="https://uifaces.co/our-content/donated/rSuiu_Hr.jpg" class="w-8 rounded-full mr-2 mt-2" alt=""></a>
                    </div>

                    <div class="mt-4">
                        <a href="#" class="text-blue-600 hover:underline text-xs">+ 104 contributors</a>
                    </div>
                </div> <!-- /contributors -->
                <div class="languages border-t border-gray-400 mt-6 pt-6">
                    <h4 class="text-base font-semibold flex items-center">
                        <span>Languages</span>
                    </h4>

                    <div class="mt-4 flex">
                        <div class="w-11/12 h-2 rounded-md rounded-r-none bg-purple-700"></div>
                        <div class="w-1/12 h-2 rounded-md rounded-l-none bg-yellow-400"></div>
                    </div>
                    <ul class="mt-2 flex space-x-8 items-center text-xs">
                        <li class="flex items-center">
                            <span class="w-2 h-2 rounded-full bg-purple-700"></span>
                            <span class="ml-4">
                                <span class="font-semibold">CSS</span>
                                <span>93.9%</span>
                            </span>
                        </li>
                        <li class="flex items-center">
                            <span class="w-2 h-2 rounded-full bg-yellow-400"></span>
                            <span class="ml-4">
                                <span class="font-semibold">JS</span>
                                <span>6.1%</span>
                            </span>
                        </li>
                    </ul>
                </div> <!-- /languages -->

            </div> <!-- end sidebar -->
        </div>

        <footer class="container mx-auto text-xs border-t border-gray-400 py-10 flex flex-col lg:flex-row items-center justify-between">
            <ul class="flex items-center space-x-6 lg:space-x-12">
                <li>&copy; 2021 GitHub, Inc,</li>
                <li><a class="text-blue-600 hover:underline" href="#">Terms</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Privacy</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Security</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Status</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Docs</a></li>
            </ul>
            <div class="mx-16 hidden lg:block">
                <a href="#">
                    <svg height="24" class="fill-current hover:text-gray-500 octicon octicon-mark-github text-gray-400" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
                </a>
            </div>
            <ul class="flex items-center space-x-6 lg:space-x-12 mt-4 lg:mt-0">
                <li><a class="text-blue-600 hover:underline" href="#">Contact GitHub</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Pricing</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">API</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Training</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">Blog</a></li>
                <li><a class="text-blue-600 hover:underline" href="#">About</a></li>
            </ul>
        </footer>
    </div>
</template>

<script>
import readme from './readme-tailwind.md'

export default {
    layout: 'github',
    computed: {
        readme() {
            return readme
        }
    }
}
</script>

<style scoped>

</style>