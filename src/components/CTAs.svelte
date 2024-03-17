<script>
  export let dark;
</script>

<div class="flex items-center gap-4">
  <button
    class={"specialBtn" + (dark ? " bg-[#181b34]" : " ")}
    id="cta-contact"
    aria-label="Contact Us"
  >
    <p class="text-base sm:text-lg md:text-xl">Contact Us</p>
  </button>
  <button
    class={"specialBtnDark" + (dark ? " bg-[#818cf8]" : " ")}
    id="cta-get-started"
    aria-label="Get Started"
  >
    <p class="text-base sm:text-lg md:text-xl">Get Started &rarr;</p>
  </button>
</div>
