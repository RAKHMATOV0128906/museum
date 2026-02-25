<template>
  <div class="news-layout">
    <div class="big-card">
      <img class="bg-image" src="../assets/image/image%209.svg"/>
      <div class="overlay-card">
        <div class="overlay-top">
          <span class="date">Apr 24, 2025</span>
          <div class="tags">
            <span class="tag green">Toshkent</span>
            <span class="tag pink">loyihalar</span>
          </div>
        </div>

        <h2>
          Muzeylarning yangi davri:<br>
          raqamli texnologiyalar<br> tarixni jonlantiradi
        </h2>

        <p class="author">
          e’lon qilindi: Dilshod Ruziev / Muallif
        </p>
      </div>
    </div>
    <div class="right-list">
      <div class="mini-card" v-for="i in 3" :key="i">
        <img
          class="mini-img"
          src="../assets/image/image%204.svg"
          alt="museum"
        />

        <div class="mini-content">
          <div class="mini-tags">
            <span class="tag green">Toshkent</span>
            <span class="tag pink"> loyihalar</span>
          </div>

          <span class="mini-date">Apr 20, 2025</span>

          <h4>
            Kirish ochiq: Toshkentda noyob ochiq osmon osti muzeyi ochildi
          </h4>
        </div>
      </div>
    </div>
  </div>
</template>
