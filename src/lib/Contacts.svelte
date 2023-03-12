<script lang="ts">
  import ContactItem from "./ContactItem.svelte";
</script>

<section id="contacts">
  <hr class="divideLine" />
  <h2 class="contactsTitle">My contacts</h2>
  <ul class="contacts">
    <ContactItem
      link={{
        id: "email",
        href: "mailto:relisqu@gmail.com",
      }}
      img={{
        alt: "mail",
        src: "src/content/contactIcons/mail.svg",
      }}
    />

    <ContactItem
      link={{
        id: "",
        href: "https://relisqu.itch.io/",
      }}
      img={{
        alt: "itch-io",
        src: "src/content/contactIcons/itchIo.svg",
      }}
    />
    <ContactItem
      link={{
        id: "tg-link",
        href: "https://t.me/relisqu_dev",
      }}
      img={{
        alt: "telegram",
        src: "src/content/contactIcons/telegram.svg",
      }}
    />

    <ContactItem
      link={{
        id: "gh-link",
        href: "https://github.com/relisqu",
      }}
      img={{
        alt: "github",
        src: "src/content/contactIcons/github.svg",
      }}
    />
    <ContactItem
      link={{
        id: "",
        href: "https://twitter.com/relisqu",
      }}
      img={{
        alt: "twitter",
        src: "src/content/contactIcons/twitter.svg",
      }}
    />
  </ul>
</section>
