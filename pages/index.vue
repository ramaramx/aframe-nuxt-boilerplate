<template>
    <div>
        <SceneAframe />
    </div>
</template>

<script>
import SceneAframe from '~/components/aframe/SceneAframe.vue';

export default{
    name: "index",
    layout: "default",
    components: { SceneAframe }
}
</script>