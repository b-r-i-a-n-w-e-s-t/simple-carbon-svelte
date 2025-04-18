<script lang="ts">
  import { UIShell } from '@txstate-mws/carbon-svelte'
  import '../app.css'

</script>

<UIShell appName="Simple Carbon Svelte Project" navRoot={{
  title: 'Simple Carbon Svelte Project',
  routeId: '/',
  children: [
    { title: 'Form', routeId: '/form' }
  ]

}}>
    <slot />
</UIShell>
