<template>
  <div>
    <div class="footer container-md p-0">
      <!-- Footer -->
      <footer class="text-white" style="background-color: #000000">
        <!-- Grid container -->
        <div class="container p-4">
          <!-- Section: Form -->
          <section class="col font-quicksand">
            <form action="">
              <!--Grid row-->
              <div class="row d-flex py-3 justify-content-lg-center">
                <!--Grid column-->
                <div class="col-auto">
                  <p class="pt-2">
                    <strong>Sign up for our newsletter</strong>
                  </p>
                </div>
                <!--Grid column-->

                <!--Grid column-->
                <div class="col-md-5 col-12 font-quicksand">
                  <!-- Email input -->
                  <div class="form-outline form-white mb-3">
                    <input id="form5Example2" type="email" class="form-control" />
                    <label class="form-label" for="form5Example2">Email address</label>
                  </div>
                </div>
                <!--Grid column-->

                <!--Grid column-->
                <div class="col-auto font-quicksand">
                  <!-- Submit button -->
                  <button type="submit" class="btn btn-outline-light mb-4">Subscribe</button>
                </div>
                <!--Grid column-->
              </div>
              <!--Grid row-->
            </form>
          </section>
          <!-- Section: Form -->

          <!-- Section: Text -->
          <section class="my-2 link-section font-quicksand">
            <p class="link-section-caption">We are a bitcoin investment platform for people who have come to realize the value of bitcoin and wants to earn through bitcoin but have little or less knowledge, or prefer not to go through the hassle it takes to set up a mining farm, or the time it takes to learn and master the skills of forex trading.Unlike other bitcoin mining contract providers we have managed to gauge in-between providing the best profit sensation and staying effective in that way serving you better. With our years of service and teams of expert we have come to understand what Investors seek and have adopted several mission objectives to achieve this. We believe in bitcoin as the new wealth of the world.</p>
          </section>
          <!-- Section: Text -->

          <!-- Section: Links -->
          <div class="container">
            <!--Grid row-->
            <div class="row">
              <!--Grid column-->
              <div class="col-md-3 mb-4 mb-md-0 font-quicksand">
                <h5 class="text-capitalize">Contact Us</h5>

                <ul class="list-unstyled mb-0">
                  <li>
                    <a href="mail:aurocapitalinvestment@aol.com" target="_blank" class="text-white">aurocapitalinvestment@aol.com</a>
                  </li>
                  <li>
                    <a href="tel:+1(812)214-5262" target="_blank" class="text-white">Customer Support : +1(812)214-5262</a>
                  </li>
                </ul>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-3 col-md-6 mb-4 mb-md-0 font-quicksand">
                <h5 class="text-capitalize">Sponsors</h5>

                <ul class="list-unstyled mb-0">
                  <li>
                    <a href="https://coinmarketcap.com/" target="_blank" class="text-white">CoinMarketCap</a>
                  </li>
                  <li>
                    <a href="https://www.wsj.com/" target="_blank" class="text-white">WallStreet Investors</a>
                  </li>
                </ul>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-3 col-md-6 mb-4 mb-md-0 font-quicksand">
                <h5 class="text-capitalize">Affiliates</h5>

                <ul class="list-unstyled mb-0">
                  <li>
                    <a href="https://blockexplorer.com/" target="_blank" class="text-white">BlockExplorer</a>
                  </li>
                  <li>
                    <a href="https://crypto.com/" target="_blank" class="text-white">Crypto.com</a>
                  </li>
                </ul>
              </div>
              <!--Grid column-->

              <!--Grid column-->
              <div class="col-lg-3 col-md-6 mb-4 mb-md-0 font-quicksand">
                <h5 class="text-capitalize">Blog</h5>

                <ul class="list-unstyled mb-0">
                  <li>
                    <router-link :to="{ path: '/About_us' }">
                      <a href="#!" class="text-white">Our Vision</a>
                    </router-link>
                  </li>
                  <li>
                    <router-link :to="{ path: '/Investment_Plans' }">
                      <a href="#!" class="text-white"> Annual Index Chart</a>
                    </router-link>
                  </li>
                </ul>
              </div>
              <!--Grid column-->
            </div>
            <!--Grid row-->
          </div>
          <!-- Section: Links -->
        </div>
        <!-- Grid container -->
        <!-- INVESTMENT REGULATION container -->

        <div class="container-md">
          <h5 class="footer-note mx-2 font-quicksand">The SEC’s Office of Investor Education and Advocacy is issuing this Investor Alert to make investors aware about the potential risks of investments involving Bitcoin and other forms of virtual currency. The rise of Bitcoin and other virtual and digital currencies creates new concerns for investors. A new product, technology, or innovation – such as Bitcoin – has the potential to give rise both to frauds and high-risk investment opportunities. Potential investors can be easily enticed with the promise of high returns in a new investment space and also may be less skeptical when assessing something novel, new and cutting-edge. We previously issued an Investor Alert about the use of Bitcoin in the context of a Ponzi scheme. The Financial Industry Regulatory Authority (FINRA) also recently issued an Investor Alert cautioning investors about the risks of buying and using digital currency such as Bitcoin. In addition, the North American Securities Administrators Association (NASAA) included digital currency on its list of the top 10 threats to investors for 2013.Using Bitcoin may limit your recovery in the event of fraud or theft. If fraud or theft results in you or your investment losing bitcoins, you may have limited recovery options. Third-party wallet services, payment processors and Bitcoin exchanges that play important roles in the use of bitcoins may be unregulated or operating unlawfully. Law enforcement officials may face particular challenges when investigating the illicit use of virtual currency. Such challenges may impact SEC investigations involving Bitcoin: Tracing money. Traditional financial institutions (such as banks) often are not involved with Bitcoin transactions, making it more difficult to follow the flow of money. International scope. Bitcoin transactions and users span the globe. Although the SEC regularly obtains information from abroad (such as through cross-border agreements), there may be restrictions on how the SEC can use the information and it may take more time to get the information. In some cases, the SEC may be unable to obtain information located overseas. No central authority. As there is no central authority that collects Bitcoin user information, the SEC generally must rely on other sources, such as Bitcoin exchanges or users, for this type of information. Seizing or freezing bitcoins. Law enforcement officials may have difficulty seizing or freezing illicit proceeds held in bitcoins. Bitcoin wallets are encrypted and unlike money held in a bank or brokerage account, bitcoins may not be held by a third-party custodian.</h5>

          <div class="footer-img-sec">
            <img :src="image" alt="" srcset="" class="footer-img" />
            <img :src="image2" alt="" srcset="" class="footer-img" />
            <img :src="image3" alt="" srcset="" class="footer-img-flag" />
          </div>
        </div>
        <!-- Copyright -->
        <div class="text-center p-5 font-quicksand copyright" style="background-color: rgba(0, 0, 0, 0.2)">
          © 2020 Copyright:
          <a class="text-white" href="/Sign_up">Auro Capital Investment </a>
        </div>
        <!-- Copyright -->
      </footer>
      <!-- Footer -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterNav',
  data() {
    return {
      image: require('@/assets/images/icon/uk2.png'),
      image2: require('@/assets/images/icon/us.png'),
      image3: require('@/assets/images/icon/uswhite.png'),
    }
  },
}
</script>

<style scoped>
.font-quicksand {
  font-family: 'Quicksand', sans-serif;
}
.link-section p {
  width: 100%;
  font-size: 15px;
  padding: 30px 0px;
  margin: 0px auto;
}

footer a {
  text-decoration: none;
}
.footer-note {
  color: #434242;
  font-size: 13px;
}
.footer-img {
  margin: 5px 10px;
  width: 30px;
}

.footer-img-flag {
  margin: 10px 10px;
  color: #434242;
  width: 50px;
}
.copyright {
  font-size: 10px;
}
/* mobile view */
@media (max-width: 886px) {
  .link-section p {
    width: 100%;
    padding: 40px 0px;
    margin: 0px;
  }

  .form-label {
    margin: 20px 0px 0px 0px;
  }
}
</style>
