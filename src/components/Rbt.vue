<template>
  <div class="container card">
    <div class="row rbt">
      <div class="col">
        <a
          href="sms:1212;?&body=YRLAP   "
          class="link-img"
          title="Aktifkan NPS Woro Widowati - Ya Rasulullah telkomsel"
        >
          <img src="../assets/telkomsel-min.png" alt="telkomsel" />
          <span class="mt-2">TELKOMSEL</span>
        </a>
        <a
          href="sms:1212;?&body=YRLAP  "
          class="button link-aktif"
          title="Aktifkan NPS Woro Widowati - Ya Rasulullah telkomsel"
        >
          <i class="icon fas fa-play mr-1" style='font-size:14px;color:#171257'></i>
          AKTIFKAN
        </a>
      </div>
      <div class="col">
        <a href="sms:1818;?&body=34151263   " class="link-img" title="Aktifkan NPS Woro Widowati - Ya Rasulullah Xl">
          <img src="../assets/xl.png" alt="Xl" />
          <span class="mt-2">XL</span>
        </a>
        <a
          href="sms:1818;?&body=34151263   "
          class="button link-aktif"
          title="Aktifkan NPS Woro Widowati - Ya Rasulullah Xl"
        >
          <i class="icon fas fa-play mr-1" style='font-size:14px;color:#171257'></i>
          AKTIFKAN
        </a>
      </div>
      <div class="col">
        <a href="sms:1212;?&body=590711   " class="link-img" title="Aktifkan NPS Woro Widowati - Ya Rasulullah 3">
          <img src="../assets/3.png" alt="3" />
          <span class="mt-2">Tri</span>
        </a>
        <a
          href="sms:1212;?&body=590711  "
          class="button link-aktif"
          title="Aktifkan NPS Woro Widowati - Ya Rasulullah 3"
        >
          <i class="icon fas fa-play mr-1" style='font-size:14px;color:#171257'></i>
          AKTIFKAN
        </a>
      </div>
      <div class="col">
        <a href="sms:808;?&body=#  " class="link-img" title="Aktifkan NPS Woro Widowati - Ya Rasulullah indosat">
          <img src="../assets/Indosat.png" alt="indosat" />
          <span class="mt-2">INDOSAT</span>
        </a>
        <a
          href="sms:808;?&body=#  "
          class="button link-aktif"
          title="Aktifkan NPS Woro Widowati - Ya Rasulullah indosat"
        >
          <i class="icon fas fa-play mr-1" style='font-size:14px;color:#171257'></i>
          AKTIFKAN
        </a>
      </div>
    </div>
    <hr />

    <div class="text-center">
      <ul class="list-unstyled list-inline">
        <li class="list-inline-item">
          <a href="https://www.facebook.com/musikproaktif/" class="btn-floating btn-sm btn-fb mx-1" target="_blank">
            <i class="fab fa-facebook" style="font-size:14px;color:white"></i>
          </a>
        </li>
        <li class="list-inline-item">
          <a href="https://twitter.com/musikproaktif" class="btn-floating btn-sm btn-tw mx-1" target="_blank">
            <i class="fab fa-twitter" style="font-size:14px;color:white"></i>
          </a>
        </li>
        
        <li class="list-inline-item">
          <a href="https://www.youtube.com/musikproaktif" class="btn-floating btn-sm btn-li mx-1" target="_blank">
            <i class="fab fa-youtube" style="font-size:14px;color:white"></i>
          </a>
        </li>

        <li class="list-inline-item">
          <a href="https://www.instagram.com/musikproaktif/" class="btn-floating btn-sm btn-li mx-1" target="_blank">
            <i class="fab fa-instagram" style="font-size:14px;color:white"></i>
          </a>
        </li>
        
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Rbt"
};
</script>

<style scoped>

.rbt {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

@media screen and (min-width: 992px) {
    .rbt {
        flex-wrap: nowrap;
    }
}

@media (max-width: 480px) {
  .card {
    max-width: 300px;
    min-width: 280px;
    width: 90%;
    padding: 0 1rem;
  }

  .col {
    width: 100%;
  }

  .rbt {
      display: block;
  }

  .rbt .col {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-bottom: 0;
  }

  .rbt a {
    margin-bottom: auto;
    margin-right: 1rem;
  }
}


.card {
  background-color: #272267;
    border: 0;
}

.col {
    display: block;
    float: left;
    padding: 1rem;

}


.rbt a {
  text-decoration: none;
  margin-bottom: 2rem;
}

.rbt a {
  display: block;
  border: none;
  outline: none;
  margin: auto;
}

a.link-img {
  padding: 1rem;
  border-radius: 1rem;
  
}

a.link-img:hover {
  background: rgba(0, 0, 0, 0.144);
  
}

a {
  color: white;
  text-decoration: none;
}

a {
  background-color: transparent;
}

a:-webkit-any-link {
  color: -webkit-link;
  cursor: pointer;
  text-decoration: none;
}

.rbt a img {
  max-width: 300px;
  width: 50%;
}

img {
  border-style: none;
}

.rbt a span {
  display: block;
  color: white; 
}

.button .icon {
  font-size: initial;
  margin-left: 0.1em;
  line-height: 38px;
}



.link-aktif {
    background: -webkit-linear-gradient(left, rgba(254,180,178,1) 0%, rgba(250,109,149,1) 80%, rgba(250,109,149,1) 100%);
    
}



.button {
    display: inline-block;
    height: 38px;
    padding: 0 30px;
    background-color: #9095a2;
    border-color: #9095a2;
    box-shadow: 0 2px 2px 0 hsla(223,9%,60%,.14), 0 3px 1px -2px hsla(223,9%,60%,.2), 0 1px 5px 0 hsla(223,9%,60%,.12);
    color: #171257 !important;
    text-align: center;
    font-size: 11px;
    font-weight: 600;
    line-height: 38px;
    text-transform: uppercase;
    text-decoration: none;
    white-space: nowrap;
    border-radius: 4px;
    cursor: pointer;
    box-sizing: border-box;
}


</style>