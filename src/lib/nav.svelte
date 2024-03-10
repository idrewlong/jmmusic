<script>
        let showMenu = false;
      
        function toggleNavbar() {
          showMenu = !showMenu;
        }
      
        function closeNavbar() {
          showMenu = false;
        }
      </script>
      
      <div class="">
       <div>
          <nav
            class=" p-4 px-6 mx-auto shadow-lg  md:flex md:justify-between md:items-center"
          >
            <div class="flex items-center justify-between">
              <a href="/" class="flex items-center">
                <!-- <img src="/favicon.png" class="h-14 w-14 hover:scale-105 duration-500" alt="iDrew Logo" /> -->
                <span class="text-2xl font-semibold whitespace-nowrap text-white ">JM</span>
              </a>
      
              <!-- Mobile menu button -->
              <div class="flex md:hidden">
                <button
                  type="button"
                  class="text-white hover:text-gray focus:outline-none focus:text-gray-400"
                  aria-label="Toggle Navigation"
                  on:click={toggleNavbar}
                >
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" class="w-6 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
                  </svg>
                </button>
              </div>
            </div>
      
            <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
            <div
              class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-6 md:mt-0 {showMenu
                    ? 'flex'
                    : 'hidden'}"
            >
              <a class="text-gray-50 duration-500 hover:text-opacity-70  hover:underline ease-in-out" href="/about" on:click={closeNavbar}>About</a>
              <!-- <a class="text-grey-800 duration-500 hover:text-orange-400 hover:underline ease-in-out" href="/blog" on:click={closeNavbar}>Blog</a> -->
              <a class="text-gray-50 duration-500 hover:text-opacity-70  hover:underline ease-in-out" href="/credits" on:click={closeNavbar}>Credits</a>
              <a class="text-gray-50 duration-500 hover:text-opacity-70  hover:underline ease-in-out" href="/faq" on:click={closeNavbar}>FAQ</a>
              <!-- <a class="text-gray-500 duration-500 hover:text-orange-400 hover:underline ease-in-out" href="/blog" on:click={closeNavbar}>Portfolio</a> -->
              <a class="text-gray-50 duration-500 hover:text-opacity-70  hover:underline ease-in-out" href="/contact" on:click={closeNavbar}>Contact</a>

              <a href="https://www.instagram.com/jacksonmaddoxmusic/" class="text-gray-50 hover:text-opacity-70 duration-200">
                <span class="sr-only">Instagram</span>
                <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M15.233 5.488c-.843-.038-1.097-.046-3.233-.046s-2.389.008-3.232.046c-2.17.099-3.181 1.127-3.279 3.279-.039.844-.048 1.097-.048 3.233s.009 2.389.047 3.233c.099 2.148 1.106 3.18 3.279 3.279.843.038 1.097.047 3.233.047 2.137 0 2.39-.008 3.233-.046 2.17-.099 3.18-1.129 3.279-3.279.038-.844.046-1.097.046-3.233s-.008-2.389-.046-3.232c-.099-2.153-1.111-3.182-3.279-3.281zm-3.233 10.62c-2.269 0-4.108-1.839-4.108-4.108 0-2.269 1.84-4.108 4.108-4.108s4.108 1.839 4.108 4.108c0 2.269-1.839 4.108-4.108 4.108zm4.271-7.418c-.53 0-.96-.43-.96-.96s.43-.96.96-.96.96.43.96.96-.43.96-.96.96zm-1.604 3.31c0 1.473-1.194 2.667-2.667 2.667s-2.667-1.194-2.667-2.667c0-1.473 1.194-2.667 2.667-2.667s2.667 1.194 2.667 2.667zm4.333-12h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm.952 15.298c-.132 2.909-1.751 4.521-4.653 4.654-.854.039-1.126.048-3.299.048s-2.444-.009-3.298-.048c-2.908-.133-4.52-1.748-4.654-4.654-.039-.853-.048-1.125-.048-3.298 0-2.172.009-2.445.048-3.298.134-2.908 1.748-4.521 4.654-4.653.854-.04 1.125-.049 3.298-.049s2.445.009 3.299.048c2.908.133 4.523 1.751 4.653 4.653.039.854.048 1.127.048 3.299 0 2.173-.009 2.445-.048 3.298z"/></svg>
            </a>
            </div>
          </nav>
        </div>
      </div>