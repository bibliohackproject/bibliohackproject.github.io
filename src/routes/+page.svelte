<script lang="ts">
  import BrandIcon from "$lib/components/BrandIcon.svelte";
  import Logo from "$lib/components/Logo.svelte";
  import ProjectLink from "$lib/components/ProjectLink.svelte";
  import { siGithub, siBluesky, siNote } from "simple-icons";
</script>

<h1
  class="hero-gradient flex items-center gap-3 text-4xl px-4 py-12 text-slate-100"
>
  <Logo class="h-10 w-10 drop-shadow-lg" />
  <span class="font-extralight drop-shadow-lg"
    >biblio<span class="font-semibold">hack</span> project</span
  >
</h1>

<div class="p-4">
  <section class="my-8 md:flex md:gap-8">
    <h2 class="text-2xl md:w-40 md:shrink-0">/about</h2>

    <div class="max-w-3xl">
      <div class="text-lg leading-8" style="font-feature-settings: 'palt' 1;">
        <span class="font-zalando-sans-expanded">bibliohack project</span
        >［ビブリオハック・プロジェクト］は、
        テクノロジーを活用し、本の情報を共有し、発見するさまざまなサービスを開発・提供することを目指すプロジェクトです。
        読者、著者、出版社を結びつけ、本と読書を中心とした新しいコミュニティを創り出します。
      </div>
      <div class="text-lg">
        <span class="font-zalando-sans-expanded">bibliohack project</span>
        is a project that aims to develop and provide various services that leverage
        technology to share and discover book information. It brings together readers,
        authors, and publishers to create a new community centered around books and
        reading.
      </div>
    </div>
  </section>

  <section class="my-8 md:flex md:gap-8">
    <h2 class="text-2xl md:w-40 md:shrink-0">/projects</h2>
    <div>
      <div>
        <span class="font-zalando-sans-expanded">bibliohack project</span
        >参加のプロジェクト一覧です。
      </div>
      <ul class="mt-4 flex gap-4">
        <li>
          <ProjectLink
            name="opencover"
            icon="https://opencover.jp/favicon.png"
            url="//opencover.jp/"
            developer="SUGIMOTO Tatsuo"
          />
        </li>
        <li>
          <ProjectLink
            name="honbaco"
            icon="data:image/svg+xml,%3csvg%20width='640'%20height='640'%20viewBox='0%200%20640%20640'%20fill='none'%20xmlns='http://www.w3.org/2000/svg'%3e%3cg%20clip-path='url(%23clip0_26_16)'%3e%3cpath%20d='M471.715%2020L620%20168.285V620H20V20H471.715Z'%20fill='white'%20stroke='black'%20stroke-width='40'/%3e%3cpath%20d='M354.64%20480V366.6C354.64%20360.72%20354.22%20355.12%20353.38%20349.8C352.54%20344.48%20350.86%20339.86%20348.34%20335.94C346.1%20331.74%20343.02%20328.52%20339.1%20326.28C335.18%20323.76%20330.14%20322.5%20323.98%20322.5C311.94%20322.5%20302.7%20326.84%20296.26%20335.52C289.82%20343.92%20286.6%20354.42%20286.6%20367.02V480H217.72V162.48H286.6V297.3H287.44C292.2%20288.9%20299.76%20281.48%20310.12%20275.04C320.48%20268.32%20332.94%20264.96%20347.5%20264.96C361.78%20264.96%20373.68%20267.48%20383.2%20272.52C393%20277.56%20400.84%20284.14%20406.72%20292.26C412.88%20300.1%20417.22%20309.2%20419.74%20319.56C422.54%20329.92%20423.94%20340.28%20423.94%20350.64V480H354.64Z'%20fill='black'/%3e%3c/g%3e%3cdefs%3e%3cclipPath%20id='clip0_26_16'%3e%3crect%20width='640'%20height='640'%20fill='white'/%3e%3c/clipPath%3e%3c/defs%3e%3c/svg%3e"
            url="//honbaco.com/"
            developer="SUGIMOTO Tatsuo"
          />
        </li>
      </ul>
    </div>
  </section>

  <section class="my-8 md:flex md:gap-8">
    <h2 class="text-2xl md:w-40 md:shrink-0">/members</h2>

    <div>
      <div>
        <span class="font-zalando-sans-expanded">bibliohack project</span
        >参加メンバー一覧です。
      </div>

      <div class="mt-4 font-semibold">Founder</div>
      <div class="mt-2 flex items-center gap-2">
        <img
          src="https://avatars.githubusercontent.com/u/118193"
          alt="SUGIMOTO Tatsuo"
          class="size-12 rounded-full inline grayscale"
        />
        <div>
          SUGIMOTO Tatsuo<br />
          <div class="flex gap-4 mt-1">
            <a
              href="//bsky.app/profile/sugimototatsuo.com"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center gap-1"
              ><BrandIcon icon={siBluesky} class="size-4" />Bluesky</a
            >

            <a
              href="//github.com/sugi2000"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center gap-1"
              ><BrandIcon icon={siGithub} class="size-4" />GitHub</a
            >

            <!-- <a
              href="//note.com/bibliohack"
              target="_blank"
              rel="noopener noreferrer"
              class="inline-flex items-center gap-1"
              ><BrandIcon icon={siNote} class="size-4" />Note</a
            > -->
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="my-8 md:flex md:gap-8">
    <h2 class="text-2xl md:w-40 md:shrink-0">/funds</h2>
    <div>
      <span class="font-zalando-sans-expanded">bibliohack project</span>は以下の支援を受けています。
      <ul class="mt-4 list-disc list-inside">
        <li>TMU GAPファンド 2025 / 2026</li>
        <li>科研費 26K03601 /  20K12535</li>
      </ul>
    </div>
  </section>
</div>

<style>
  .hero-gradient {
    margin-inline: -1px;
    background-color: var(--color-slate-800);
    background-image: linear-gradient(
      to right,
      var(--color-slate-800),
      var(--color-slate-500),
      var(--color-slate-800),
      var(--color-slate-500),
      var(--color-slate-800)
    );
    background-size: 300% 100%;
    background-position: 0% 50%;
    animation: hero-gradient 15s ease-in-out infinite;
  }

  @keyframes hero-gradient {
    0%,
    100% {
      background-position: 0% 50%;
    }
    50% {
      background-position: 100% 50%;
    }
  }

  @media (prefers-reduced-motion: reduce) {
    .hero-gradient {
      animation: none;
    }
  }
</style>
