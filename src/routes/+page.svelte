<script lang="ts">
  import * as Menubar from "$lib/components/ui/menubar";
</script>

<body class="flex flex-col justify-center items-center text-center pt-5 bg-slate-900 font-mono text-slate-200">
  <div class="flex items-center justify-center bg-slate-700">
    <img src="/favicon.png" alt="1x Developer Podcast Logo" width="100px" class="p-4 absolute left-0"/>
    <Menubar.Root class="flex-1 bg-slate-700">
      <Menubar.Menu>
        <Menubar.Trigger>Listen Now</Menubar.Trigger>
        <Menubar.Content class="bg-slate-700 text-slate-200">
          <a href="https://open.spotify.com/show/1eXZqdw1wIgEmkpmi24ppX?si=e1d4c1866e2b4e67" target="_blank">
            <Menubar.Item>Spotify</Menubar.Item>
          </a>
          <a href="https://www.youtube.com/@1xDeveloperPodcast" target="_blank">
            <Menubar.Item>YouTube</Menubar.Item>
          </a>
        </Menubar.Content>
      </Menubar.Menu>
      <Menubar.Menu>
        <Menubar.Trigger>Socials</Menubar.Trigger>
        <Menubar.Content class="bg-slate-700 text-slate-200">
            <a href="https://x.com/1xDevPodcast" target="_blank">
              <Menubar.Item>X/Twitter</Menubar.Item>
            </a>
            <a href="mailto:1xdeveloperpodcast@protonmail.com">
                <Menubar.Item>Email</Menubar.Item>
            </a>  
        </Menubar.Content>
      </Menubar.Menu>
    </Menubar.Root>
  </div>
  <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
    <h1 class="text-6xl">
        1x Developer Podcast
    </h1>
    <div class="pt-5">
      <iframe  title="embedded-player" style="border-radius:12px" src="https://open.spotify.com/embed/episode/6c3YkK9oiOi7YJmZ9QO1jF?utm_source=generator" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
    </div>
  </div>
</body>
