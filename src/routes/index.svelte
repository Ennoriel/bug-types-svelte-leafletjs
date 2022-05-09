<script lang="ts">
    import { LeafletMap } from 'svelte-leafletjs';
    import type { Map } from 'leaflet';

    let getMap: () => Map;
</script>

<LeafletMap bind:getMap />