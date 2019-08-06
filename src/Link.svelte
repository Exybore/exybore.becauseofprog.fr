<script>
  export let name
  export let id
  export let href
</script>

<a class="link" id={id} href={href}>
  <img src="img/{id}.png" />
  <span class="tooltip">{name}</span>
</a>