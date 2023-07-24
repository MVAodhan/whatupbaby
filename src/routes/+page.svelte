<script lang="ts">
	import { Howl } from 'howler';

	let sound = new Howl({
		src: ['whatupbaby.mp3']
	});
</script>

<button class="btn" on:click={() => sound.play()}>What up</button>
