<script>
    import RoutifyIntro from './example/_components/RoutifyIntro.svelte'
    import { metatags } from '@roxi/routify'
    metatags.title = 'My Routify app'
    metatags.description = 'Description coming soon...'

    export let scoped;

    const { abc } = scoped;

    console.log(abc);
</script>

<RoutifyIntro />