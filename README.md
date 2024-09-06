<!DOCTYPE html>
<html lang="en">
<style>
    :root {
  --primaryColor: #ff274b;
  --secondaryColor: #f7bcf7;
  --lightColor: #ffffff;
  --bgColor-1: #171a1c;
  --bgColor-2: #22282a;
  --padding: 8%;
  --sectionPadding: 2rem var(--padding);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Josefin Sans", sans-serif;
}

span {
  color: var(--primaryColor);
}

h1 {
  color: var(--lightColor);
  margin: 1.7rem 0;
  font-size: 4.68rem;
}

h2 {
  color: var(--lightColor);
  font-size: 2.2rem;
  letter-spacing: 0.12rem;
  cursor: pointer;
  margin: 1.7rem 0;
}

h3 {
  color: var(--lightColor);
  font-size: 1.5rem;
  margin-bottom: 50px;
}

h4 {
  color: var(--secondaryColor);
  letter-spacing: 0.12rem;
  font-size: 1.25rem;
}

h5 {
  color: var(--lightColor);
  letter-spacing: 2px;
  font-size: 1.37rem;
  margin-bottom: 1.5rem;
  text-transform: capitalize;
}

/* home Section start */

.home {
  height: 100vh;
  width: 100%;
  background-color: var(--bgColor-1);
  display: flex;
  flex-direction: column;
}

nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 2.8rem;
  padding-left: var(--padding);
  padding-right: var(--padding);
}

nav ul li {
  list-style-type: none;
  display: inline-block;
  padding: 0.8rem 1.5rem;
}

nav ul li a {
  color: var(--lightColor);
  text-decoration: none;
  text-transform: capitalize;
}

nav ul li a:hover {
  color: var(--primaryColor);
  transition: 0.4s;
}

.lun-but {
  padding: 3px;
  display: flex;
  align-items: center;
  border: 2px solid var(--primaryColor);
  border-radius: 30px;
}

.btn {
  background-color: var(--primaryColor);
  color: var(--lightColor);
  text-decoration: none;
  border: 2px solid transparent;
  font-weight: bold;
  padding: 13px 30px;
  border-radius: 30px;
  transition: 0.4s;
}

.btn:hover {
  background-color: transparent;
  border: 2px solid var(--primaryColor);
  cursor: pointer;
}

.content {
  flex-grow: 1;
  padding: 0 var(--padding);
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.content-texts {
  position: relative;
  bottom: 70px;
}

.social {
  margin-top: 100px;
}

.social img {
  margin-right: 30px;
  width: 40px;
}

.social img:hover {
  transform: scale(1.2);
  transition: 0.4s;
}

.content-images {
  width: 45%;
  height: 90%;
  align-self: flex-end;
  position: relative;
}

.content-images img {
  height: 100%;
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translateX(-50%);
  transition: bottom 1s, left 1s;
}

.content-images:hover .shape {
  bottom: 40px;
}

.content-images:hover .pic {
  left: 45%;
}

</style>
<body>
    <section class="home" id="home">
        <!----content Section start---->
        <div class="content">
          <div class="content-texts" data-sal-duration="1200" data-sal="slide-right" data-sal-delay="300"
            data-sal-easing="ease-out-bounce">
            <h4>Welcome to our big world</h4>
            <h1>Mars <span>Store</span></h1>
            <h3>The best <span>application</span> for selling clothes and personal belongings</h3>
    
            <div class="social">
              <a href="https://www.facebook.com/underground.clothes.fj?mibextid=LQQJ4d" target="_blank"><img
                  src="icons/facebook-logo.svg" alt="shape" class="social-icon" /></a>
    
              <a href="https://www.instagram.com/mars_store0/?igsh=Y241Y2Y0bGIweGls&utm_source=qr" target="_blank"><img src="icons/instagram-logo.svg" alt="shape" class="social-icon" /></a>
    
              <a href="https://www.whatsapp.com/channel/0029VaJi5QB2phHId2nCEf0f3" target="_blank"><img
                  src="icons/whatsapp-logo.svg" alt="shape" class="social-icon" /></a>
    
    
    
            </div>
          </div>
    
          <div class="content-images" data-sal-duration="1200" data-sal="slide-left" data-sal-delay="300"
            data-sal-easing="ease-out-bounce">
            <img src="imgs/shape1.png" alt="shape" class="shape" />
            <img src="icons/mars-logo.svg" alt="Fathellah TAHIRI" class="pic" />
          </div>
        </div>
      </section>
</body>
</html>
