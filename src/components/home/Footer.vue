<template>
  <section>
    <div class="bg-white">
      <div class="max-w-screen-xl mx-auto py-12 md:pt-24 px-4 overflow-hidden sm:px-6 lg:px-8">
        <nav class="-mx-5 -my-2 flex flex-wrap justify-center">
          <div class="px-5 py-2">
            <g-link to="/docs/introduction/" class="text-base leading-6 text-gray-500 hover:text-gray-900">
              Docs
            </g-link>
          </div>
          <div class="px-5 py-2">
            <g-link to="/guides/" class="text-base leading-6 text-gray-500 hover:text-gray-900">
              Guides
            </g-link>
          </div>
          <div class="px-5 py-2">
            <g-link to="/starters/" class="text-base leading-6 text-gray-500 hover:text-gray-900">
              Starters
            </g-link>
          </div>
          <div class="px-5 py-2">
            <g-link to="https://github.com/maizzle" class="text-base leading-6 text-gray-500 hover:text-gray-900">
              Contribute
            </g-link>
          </div>
        </nav>
        <div class="mt-8 flex justify-center -mx-6">
          <g-link to="https://twitter.com/maizzlejs/" class="mx-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">Twitter</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"/>
            </svg>
          </g-link>
          <g-link to="https://github.com/maizzle" class="mx-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">GitHub</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"/>
            </svg>
          </g-link>
          <g-link to="https://codepen.io/maizzle" class="mx-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">Codepen</span>
            <svg class="h-6 w-6" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 122 120">
              <path fill-rule="evenodd" d="M60 0C26.863 0 0 26.863 0 60c0 33.138 26.863 60 60 60s60-26.861 60-60c0-33.137-26.862-60-60-60zm0 110.146C32.35 110.146 9.854 87.65 9.854 60S32.35 9.854 60 9.854c27.65 0 50.145 22.496 50.145 50.146S87.65 110.146 60 110.146z"/><path class="inner-box" d="M97.071 48.281c-.007-.047-.019-.092-.026-.139-.016-.09-.032-.18-.056-.267-.014-.053-.033-.104-.05-.154a3.193 3.193 0 00-.082-.232c-.021-.053-.047-.105-.071-.156a2.31 2.31 0 00-.108-.21c-.029-.051-.061-.1-.091-.148a2.895 2.895 0 00-.244-.331 3.237 3.237 0 00-.159-.172c-.042-.043-.083-.086-.127-.125a3.621 3.621 0 00-.18-.152c-.048-.037-.095-.074-.145-.109-.019-.012-.035-.027-.053-.039l-33.91-22.609a3.188 3.188 0 00-3.537 0L24.321 46.045c-.018.012-.034.027-.053.039a3.825 3.825 0 00-.325.261c-.045.039-.086.082-.128.125a2.847 2.847 0 00-.402.503 4.547 4.547 0 00-.092.148 3.196 3.196 0 00-.108.21c-.024.051-.049.104-.071.156a3.193 3.193 0 00-.082.232c-.017.051-.035.102-.05.154-.023.087-.039.177-.056.267-.008.047-.02.092-.025.139a3.018 3.018 0 00-.029.416v22.607c0 .141.011.279.029.418.006.045.018.092.025.137.017.09.032.18.056.268.015.053.033.104.05.154.025.078.051.155.082.233.021.053.047.104.071.154.034.072.069.143.108.213.029.049.06.098.092.146a2.882 2.882 0 00.244.332c.05.059.103.117.158.172.042.043.083.086.128.124.058.053.118.104.181.152.047.037.094.074.144.109.019.012.035.027.053.039L58.232 96.56a3.185 3.185 0 003.537 0L95.68 73.956c.018-.012.034-.027.053-.039.05-.035.097-.072.145-.109.061-.049.121-.1.18-.152.044-.038.085-.081.127-.124a2.865 2.865 0 00.403-.504l.091-.146c.04-.07.075-.141.108-.213.024-.051.05-.102.071-.154.031-.078.057-.155.082-.233.017-.051.036-.102.05-.154.023-.088.04-.178.056-.268.008-.045.02-.092.026-.137.018-.139.028-.277.028-.418V48.697c0-.14-.011-.279-.029-.416zM63.188 32.048L88.17 48.701l-11.158 7.465-13.823-9.247V32.048zm-6.376 0v14.871L42.99 56.166l-11.159-7.465 24.981-16.653zM29.278 54.665L37.255 60l-7.977 5.335v-10.67zm27.534 33.288L31.831 71.3l11.159-7.463 13.822 9.245v14.871zM60 67.543L48.723 60 60 52.458 71.276 60 60 67.543zm3.188 20.41V73.082l13.823-9.245L88.17 71.3 63.188 87.953zm27.535-22.617L82.746 60l7.977-5.335v10.671z"/>
            </svg>
          </g-link>
        </div>
        <div class="flex justify-center mt-8">
          <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
            <input type="hidden" name="cmd" value="_s-xclick" />
            <input type="hidden" name="hosted_button_id" value="RF4DDZAUSH6NE" />
            <input type="image" class="focus:outline-none" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
            <img alt="" border="0" src="https://www.paypal.com/en_RO/i/scr/pixel.gif" width="1" height="1">
          </form>
        </div>
        <div class="mt-8">
          <p class="text-center text-sm leading-6 text-gray-400">
            &copy; {{ new Date().getFullYear() }} Maizzle - Made with <span class="text-red-500">❤</span> for email,
            <g-link to="https://github.com/maizzle/maizzle" class="text-ocean lg:text-gradient lg:bg-gradient-l-ocean-dark lg:hover:bg-gradient-r-ocean-dark">open sourced</g-link> under the MIT license.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Footer'
}
</script>
