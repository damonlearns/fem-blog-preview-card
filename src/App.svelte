<script>
  import illustImg from '/illustration-article.svg'
  import avatarImg from '/image-avatar.webp'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main class="min-h-screen flex items-center justify-center bg-(--bg-yellow)">
  <div class="font-figtree h-100 w-75 p-4 bg-white text-(--card-light-gray) outline-1 outline-(--card-dark-gray) rounded-2xl flex flex-col items-start text-left relative justify-evenly shadow-[7px_7px_0] shadow-gray-950">
    <img class="class rounded-2xl mb-4" src="{illustImg}" alt="illustration">
    <h4 class="mb-1 p-1 font-bold text-xs self-start bg-(--card-yellow) text-(--card-dark-gray) rounded-sm">Learning</h4>
    <i class="mb-1 text-xs text-(--card-dark-gray)">Published 21 Dec 2023</i>
    <h2 class="mb-1 pt-2 pb-1 font-bold text-lg text-(--card-dark-gray) self-start">HTML & CSS foundations</h2>
    <p class="text-xs mb-2 ">These languages are the backbone of every website, defining structure, content and presentation.</p>
    <div class="flex items-center gap-2">
      <img class="class rounded-full h-8 w-8" src="{avatarImg}" alt="avatar">
      <h4 class="text-xs font-bold text-(--card-dark-gray)">Greg Hooper</h4>
    </div>
  </div>

</main>

<style>
:root {
  --shadow-lg: 0 35px 20px;
  --card-yellow: hsl(47, 88%, 63%);
  --card-white: hsl(0, 0%, 100%);
  --card-light-gray: hsl(0, 0%, 42%);
  --card-dark-gray: hsl(0, 0%, 7%);
  --bg-yellow: hsl(47, 88%, 63%);

}
</style>
