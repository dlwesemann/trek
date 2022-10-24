<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://sdianalytics.netlify.app">
        <svg
          baseProfile="tiny"
          height="32px"
          fill="white"
          version="1.1"
          viewBox="0 0 0 0"
          width="24px"
          xml:space="preserve"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
        >
          <g>
            <g>
              <g>
                <path
                  d=""
                />
              </g>
            </g>
          </g>
        </svg>
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: #C6AD0C;
}
</style>
