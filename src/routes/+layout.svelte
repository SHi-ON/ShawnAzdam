<script lang="ts">
  import '../app.postcss';
  import { AppShell, AppBar } from '@skeletonlabs/skeleton';
  import Icon from '@iconify/svelte';
</script>

<!-- App Shell -->
<AppShell>
  <svelte:fragment slot="header">
    <!-- App Bar -->
    <AppBar>
      <svelte:fragment slot="lead">
        <strong class="text-xl">Infinite Eternity</strong>
      </svelte:fragment>
      <svelte:fragment slot="trail">
        <a
          class="variant-glass-primary btn"
          href="https://s.azdam.com/github"
          target="_blank"
          rel="noreferrer">
          <Icon icon="mdi:github" height="28" width="28" color="white" />
        </a>
        <a
          class="variant-glass-primary btn"
          href="https://s.azdam.com/google-scholar"
          target="_blank"
          rel="noreferrer">
          <Icon icon="simple-icons:googlescholar" height="28" width="28" color="white" />
        </a>
        <a
          class="variant-glass-primary btn"
          href="https://s.azdam.com/linkedin"
          target="_blank"
          rel="noreferrer">
          <Icon icon="mdi:linkedin" height="28" width="28" color="white" />
        </a>
        <a
          class="variant-glass-primary btn"
          href="https://s.azdam.com/x"
          target="_blank"
          rel="noreferrer">
          <Icon icon="simple-icons:x" height="28" width="28" color="white" />
        </a>
        <a
          class="variant-glass-primary btn"
          href="https://s.azdam.com/stack-overflow"
          target="_blank"
          rel="noreferrer">
          <Icon icon="mdi:stack-overflow" height="28" width="28" color="white" />
        </a>
      </svelte:fragment>
    </AppBar>
  </svelte:fragment>
  <!-- Page Route Content -->
  <slot />
</AppShell>
