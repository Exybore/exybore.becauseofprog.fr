<script>
  export let name
  export let id
  export let href
</script>

<a class="props" id={id} href={phref}>
  <img src="img/{id}.png" />
  <span class="tooltip">{social.name}</span>
</a>