<script>
  import Link from './components/Link.svelte'

  let links = [
    {
      name: 'BecauseOfProg team',
      id: 'bop',
      href: 'https://becauseofprog.fr'
    },
    {
      name: 'Keybase',
      id: 'keybase',
      href: 'https://keybase.io/exybore'
    },
    {
      name: 'Email address',
      id: 'email',
      href: 'mailto:exybore@becauseofprog.fr'
    },
    {
      name: 'Github',
      id: 'github',
      href: 'https://github.com/exybore'
    },
    {
      name: 'Mastodon',
      id: 'mastodon',
      href: 'https://mstdn.io/@Exybore'
    },
    {
      name: 'Twitter',
      id: 'twitter',
      href: 'https://twitter.com/exybore'
    },
    {
      name: 'Youtube channel',
      id: 'youtube',
      href: 'https://www.youtube.com/channel/UC9Q3XhnYp-bZUgE995Csxww'
    }
  ];
</script>

<div id="container">
  {#each links as link}
    <Link {...link} />
  {/each}

  <img
    id="avatar"
    src="img/avatar.png"
    alt="Profile picture" />
</div>
