<script lang="ts">
  import myface from '/me.jpg';
  import CV from '/PirsonBethancourt.pdf'
</script>

<main>
  <div>
    <a href="https://github.com/pirsonxyz" target="_blank" rel="noreferrer">
      <img src={myface} class="img" alt="Pfp" />
    </a>
    
  </div>
  <h1>Pirson Bethancourt</h1>
  <p>
   Software Developer from the Dominican Republic
  </p>

  <p class="presentation">Links</p>

  <a href="https://github.com/pirsonxyz"><button>Github</button></a>
  <a href="https://x.com/pirsonxyz"><button>X</button></a>
  <a href="mailto:pirson@pirson.xyz"><button>Mail</button></a>
  <a href={CV}><button>CV</button></a>

</main>

<style>
    .img {
        border-radius: 50%;
    }
  .presentation{
    color: #888;
  }
</style>
