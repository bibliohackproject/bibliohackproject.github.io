<script lang="ts">
  import BrandIcon from "$lib/components/BrandIcon.svelte";
  import Logo from "$lib/components/Logo.svelte";
  import ProjectLink from "$lib/components/ProjectLink.svelte";
  import { siGithub, siBluesky, siNote } from "simple-icons";
</script>

<h1
  class="flex items-center gap-3 text-4xl px-4 py-12 bg-slate-600 text-slate-100"
>
  <Logo class="h-10 w-10" />
  <span class="font-extralight">biblio<span class="font-semibold">hack</span> project</span>
</h1>

<div class="p-4">
  <div class="text-lg">
    <span class="font-zalando-sans-expanded">bibliohack project</span>［ビブリオハック・プロジェクト］は、
    テクノロジーを活用し、本の情報を共有し、発見するさまざまなサービスを開発・提供することを目指すプロジェクトです。
    読者、著者、出版社を結びつけ、本と読書を中心とした新しいコミュニティを創り出します。
  </div>
  <div class="text-lg">
    <span class="font-zalando-sans-expanded">bibliohack project</span>
    ｓis a project that aims to develop and provide various services that leverage technology to share and discover book information. 
    It brings together readers, authors, and publishers to create a new community centered around books and reading.
  </div>

  <h2 class="text-2xl mt-6">Projects</h2>
  <ul class="mt-4 flex gap-4">
    <li>
      <ProjectLink name="opencover" url="//opencover.jp/" />
    </li>
    <li>
      <ProjectLink name="honbaco" url="//honbaco.com/" />
    </li>
  </ul>

  <h2 class="text-xl mt-6">Contact</h2>

  <p>
    SUGIMOTO Tatsuo<br />
    <a
      href="//bsky.app/profile/sugimototatsuo.com"
      target="_blank"
      rel="noopener noreferrer"
      class="inline-flex items-center gap-1"
      ><BrandIcon icon={siBluesky} class="size-4" />Bluesky</a
    >
    |
    <a
      href="//github.com/sugi2000"
      target="_blank"
      rel="noopener noreferrer"
      class="inline-flex items-center gap-1"
      ><BrandIcon icon={siGithub} class="size-4" />GitHub</a
    >
    |
    <a
      href="//note.com/bibliohack"
      target="_blank"
      rel="noopener noreferrer"
      class="inline-flex items-center gap-1"
      ><BrandIcon icon={siNote} class="size-4" />Note</a
    >
  </p>
</div>
