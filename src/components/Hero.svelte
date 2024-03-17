<script>
  import CTAs from "./CTAs.svelte";
  import Header from "./Header.svelte";
  import SectionWrapper from "./SectionWrapper.svelte";
  import Stars from "./Stars.svelte";
</script>

<SectionWrapper id="hero">
  <Header />
  <div
    class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14"
  >
    <h2
      class="font-semibold text-4xl sm:text-5xl md:text-6xl lg:text-7xl text-center max-w-[1200px] mx-auto w-full"
    >
      <span class="text-indigo-800">Gym</span>
      Training <span class="text-slate-600 line-through">Is Hard</span><br />
      Just Got <span class="text-indigo-400">Easier</span>
    </h2>
    <p
      class="text-xl sm:text-xl md:text-2xl text-center max-w-[1000px] px-4 mx-auto w-full"
    >
      Less thinking & more doing. We've the trainer in your pocket full of <span
        class="italic"
        >personalized workouts, exercise explainations, analytics</span
      > and much much more.
    </p>
    <CTAs />
    <Stars />
  </div>
</SectionWrapper>
