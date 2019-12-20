<template>
  <div id="conteneur" itemscope itemtype="http://schema.org/Movie">
    <header id="div_titre">
      <h1><nuxt-link to="/" title="Accueil">Innsbay</nuxt-link></h1>
      <div id="imdb">
        <a href="http://www.imdb.com/title/tt1986870/" itemprop="sameAs" title="Lien vers la fiche IMDb de Innsbay" target="_blank"><img src="imdb_h30.png" alt="Lien vers la fiche IMDb de Innsbay" /></a>
      </div>
    </header>
    <div><img src="image2r_bg.jpg" alt="" style="display:none;" /></div><!-- Préchargement de l’image -->
    <nav id="div_menu">
      <ul id="menu">
        <li><nuxt-link to="/" title="Accueil">Présentation</nuxt-link></li>
        <li><nuxt-link to="/infos">Informations diverses</nuxt-link></li>
        <li><nuxt-link to="/voir">Comment le voir</nuxt-link></li>
        <li><nuxt-link to="/ressources">Ressources et liens</nuxt-link></li>
        <li><nuxt-link to="/contact">Contact</nuxt-link></li>
      </ul>
    </nav>
    <section id="div_contenu" role="main">
      <nuxt />
    </section>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
