<template>
  <div class="tr d-flex ">
    <div>
      <img src="./assets/epr.png" alt="">
    </div>
    <div class="bird">
      <img src="./assets/epr.png" alt="">
    </div>
  </div>

  <div class="gt">
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/gallery">GalleryNav</router-link>
      <router-link to="/news">NewsNav</router-link>
      <router-link to="/blog">BlogNav</router-link>
      <router-link to="/contact">ContactNav</router-link>
    </nav>
    <div class="ft">
      <div>
        <h1>BFCS:BEST FITURE COMMINICATIN SYSTEM</h1>
      </div>
      <div>
        <a href="">BFT/BFCS</a>
      </div>
      <div>
        <a href="">BFT/BSAF</a>
      </div>
    </div>
    <div class="last d-flex">
      <div class="fom">
        <div>
          <h2>EPR INFORMATION SYSTEM</h2>
        </div>
        <form>
          <div>
            L1: <label> Names</label>
            <input type="text" id="name" placeholder="Enter your Names here">
          </div>
          <div>
            L2:<label> Email</label>
            <input type="text" id="Email" placeholder="Enter your Email here">
          </div>
          <div>
            L3:<label> Phone</label>
            <input type="text" id="name" placeholder="Enter your Phone number here">
          </div>
          <div class="a d-flex">
            <label for="select" class="y-1">L5:Services</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a d-flex">
            <label for="select" class="y-2">L6:Presbytary</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a d-flex">
            <label for="select" class="y">L7-3:Organs</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <p>Select one of L8.1, L8.2 or L8.3 to precise the above L7</p>
          <div class="a d-flex">
            <label for="select" class="y">L8,1:</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a d-flex">
            <label for="select" class="y">L8,2:</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a d-flex">
            <label for="select" class="y">L8,3:</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a d-flex">
            <label for="select" class="y">L8,3:Services</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>
          <div class="a">
            <label for="select" class="y-5">Question/Request/Wishes/comment</label>
            <select class="form-select form-select-sm" aria-label=".form-select-sm example">
              <option selected>Open this select menu</option>
              <option value="1">One</option>
              <option value="2">Two</option>
              <option value="3">Three</option>
            </select>
          </div>

          <div class="mb-3">
            <label for="Textarea1" class="form-label">Why/Reason/Clarification/Arguments</label>
            <textarea class="form-control" id="Textarea1" rows="3" placeholder="Message"></textarea>
            <button class="vg">Send Message</button>
            <button class="gv">Reset</button>
          </div>
          
           

          


        </form>

      </div>
      <div class="address">
        <div>
          <h2>Our Location</h2>
        </div>
        <div>
          <div class="images">
           <a href="#"><img src="./assets/epr.png" alt=""></a> 
          </div>
        </div>
        <div>
            <h2>Mailing Address</h2>
        </div>
        <div>
          <h4>Presbyterian Church in Rwanda</h4>
        </div>
        <div>
            <p>Kigali-City,</p>
            <p>Nyarugenge District</p>
            <p>Nyarugenge sector</p>
        </div>
        <div>
            <p>Tel:+250252573789</p>
            <p>Tel:+250252573692</p>
            <p>Fax: +250252573692</p>
            <p>Po.Box: 56 Kigali</p>
            <p>Email: secreatariat@epr.rw</p>
            <p>Website: www.epr.rw</p>
            
            
        </div>
      </div>
   
    </div>
    <div>
      <footer>
  <p  class="text-secondary">
    Copyright © 2018 EPR designed in BFT by Youth General Services Ltd
  </p>
  <li><a href="" class="text-secondary">IT Support</a></li>
</footer>
    </div>
  </div>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {


  background-color: rgb(240, 240, 240);
  padding: 10px;
  width: 100%
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-align: center;
  margin-left: 1rem;
  text-decoration: none;
}

nav a:hover {
  background-color: gainsboro;
  cursor: pointer;
  padding: 10px 15px;
  border-radius: 15px;
  border: 1 solid #000;
  color: black;
}

.gt {
  align-items: center;
  justify-content: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
  width: 80%;
  margin-left: 12.8rem;
  margin-top: 4rem;
  padding: 10px 10px;
  border-radius: 15px;
  margin-right: 12rem;
  background: rgb(240, 240, 240);



}
.gt:before {
  
content: "";
position: absoliute;
top: 0;
left: 0;
background: black;
transform: skew(0deg, 6deg);


}
.gt:after {
  
  content: "";
  position: absoliute;
  top: 0;
  left: 0;
  background: black;
  transform: skew(0deg, -6deg);
  
  
  }

.ft {

  background-image: url(./assets/c1.webp);
  background-size: cover;
  background-repeat: no-repeat;
  background: rgb(190, 224, 188);
  height: 10rem;

}

.ft a {

  margin-right: 50rem;
  color: black;
  text-decoration: none;

}

nav a.router-link-exact-active {
  color: #42b983;
}

.last {
  background: rgb(240, 240, 240);
  padding-top: 0.2rem;
}

.fom {
  margin-left: 1rem;
  margin-bottom: 2rem;
}

input {
  width: 70%;
  height: 2%;
  margin-left: 0.2rem;
  margin-bottom: 0.4rem;
}

.form-select {
  width: 80%;
  height: 1%;
  margin-left: 0.2rem;
  margin-bottom: 0.4rem;
}

.y {
  margin-left: 2rem;
}

.y-1,
.y-2,
.y-3 {
  margin-left: 2rem;
}

img {
  width: 5rem;
  height: 5rem;
  padding-top: 2rem;
  margin-bottom: 2rem;
}

.tr {
  margin-left: 12rem;
  justify-content: space-between;
}

.bird {
  margin-right: 4rem;
}

#Textarea1 {
  margin-left: 2rem;
  height: 25vh;
  border: 1px solid #000;
}

.form-label {
  margin-right: 6rem;
}

.y-5 {
  margin-right: 7rem;
}

.form-select-sm {
  margin-left: 2rem;
}

.address {
  margin-left: 8rem;
  margin-bottom: 4rem;
}

.images img {
  width: 20rem;
  height: 20rem;
  border: 1px solid gray;
  padding: 10px;
  margin: 2px;
}
.vg
{
  margin-right: 11.8rem;
  margin-left: 2rem;
}
.gv
{
margin-left: 11rem;
margin-right: 0;

}
footer
{
background: rgb(240, 240, 240);

}
</style>
