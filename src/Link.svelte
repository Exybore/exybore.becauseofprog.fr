<script>
  export let name
  export let id
  export let href
</script>

<a class="link" id={id} href={href}>
  <img src="img/{id}.png" alt={id} />
  <span class="tooltip">{@html name.replace(' ','<br>')}</span>
</a>