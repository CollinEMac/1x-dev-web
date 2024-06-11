<script lang="ts">
  import * as Menubar from "$lib/components/ui/menubar";
</script>

<body class="flex flex-col justify-center items-center text-center pt-5 bg-slate-900 font-mono text-slate-200">

  <Menubar.Root class="bg-slate-700">
    <Menubar.Menu>
      <Menubar.Trigger>Listen Now</Menubar.Trigger>
      <Menubar.Content class="bg-slate-700 text-slate-200">
      <Menubar.Item>
        link to spotify
      </Menubar.Item>
      <Menubar.Item>
        link to youtube
      </Menubar.Item>
      </Menubar.Content>
    </Menubar.Menu>
    <Menubar.Menu>
      <Menubar.Trigger>Socials</Menubar.Trigger>
      <Menubar.Content class="bg-slate-700 text-slate-200">
      <Menubar.Item>
        link to twitter?
      </Menubar.Item>
      <Menubar.Item>
        email?
      </Menubar.Item>
      </Menubar.Content>
    </Menubar.Menu>
    <Menubar.Menu>
      <Menubar.Trigger>About</Menubar.Trigger>
      <Menubar.Content class="bg-slate-700 text-slate-200">
      <Menubar.Item>
        About
      </Menubar.Item>
      </Menubar.Content>
    </Menubar.Menu>
  </Menubar.Root>
  <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
    <h1 class="text-6xl">
        1x Developer Podcast
    </h1>
    <p class="text-2xl pt-3">
        coming soon...
    </p>
  </div>
</body>