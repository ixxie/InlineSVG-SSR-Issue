<script>
  import InlineSVG from 'svelte-inline-svg'

  const openmoji = require('openmoji')
  const om = openmoji.openmojis
    
  let src = om[5].openmoji_images.color.svg
</script>

<p>{src}</p>

<InlineSVG src={src}/>