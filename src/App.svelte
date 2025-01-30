<script lang="ts">
  import snorlax from "/snorlax.webp";
  import me from "/me.jpg"
  import CV from "/PirsonBethancourt.pdf";
</script>

<main>
  <div>
    <a href="https://github.com/pirsonxyz" target="_blank" rel="noreferrer">
      <img src={me} class="img" alt="Pfp" />
    </a>
  </div>
  <h1>Pirson Bethancourt</h1>
  <p>Software Developer from the Dominican Republic</p>

  <p class="presentation">Links</p>

  <a href="https://github.com/pirsonxyz"><button>Github</button></a>
  <a href="https://x.com/pirsonxyz"><button>X</button></a>
  <a href="mailto:pirson@pirson.xyz"><button>Mail</button></a>
  <a href={CV}><button>CV</button></a>
  <a href="https://pirson.bearblog.dev"><button>Blog</button></a>
</main>

<style>
  .img {
    border-radius: 50%;
    width: 769px;
    height: auto;
  }
  .presentation {
    color: #888;
  }
</style>
