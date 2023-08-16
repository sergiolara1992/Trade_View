<script setup>
import { FaFacebookF, FaTwitter, FaYoutube, FaInstagram } from "react-icons/fa";

</script>

<template>
    <footer class="footer contenedor">

        <div class="footer-main">

            <div class="card">
              <img src="/public/Logo.svg" alt="">
              <p class="footer-frag"> Tradeview Markets | Grand Cayman, KY1-1002, 4th Floor Harbour Place | 103 South Church St, PO Box 1105</p>
              <p class="footer-frag">  Main Oﬃce: +1 345 945 6271</p>
               <p class="footer-frag">    Direct Phone: +1 345 946 4532</p>
                <p class="footer-frag">  Website: www.tvmarkets.com</p>
            </div>


            <div class="card">
                    <div class="subscribe-container">
                <h4 class="footer-frag">Suscríbete a nuestro boletín</h4>
                <form class="subscribe-form">
                    <label for="email">Correo electrónico:</label>
                    <input type="email" id="email" name="email" placeholder="Tu correo electrónico" required>
                    <button type="submit">Suscribirse</button>
                </form>
            </div>
            
            </div>


            <div class="card">
                <p>FIND US ON:</p>

                <div>
                    <FaFacebookF class="footer-frag" size={20} />
                     <FaTwitter size={20} />
                     <FaYoutube size={20} />
                     <FaInstagram size={20} />
                </div> 
            </div>

            <div class="card">


                <div class="footer-grid">

                    <div>
                        <ul>
                            <li class="footer-frag">Forex</li>
                            <li class="footer-frag">Stocks </li>
                            <li class="footer-frag">Futures</li>
                            <li class="footer-frag">TradeGATEHUB</li>
                            <li class="footer-frag">Markets</li>
                            <li class="footer-frag">Pricing</li>
                            <li class="footer-frag">Introducing</li>
                            <li class="footer-frag">Brokers</li>
                            <li class="footer-frag">Education </li>
                            <li class="footer-frag">Contact US</li>
                        </ul>
                    </div>
                    <div>
                        <span>Accounts</span>
                        <p class="footer-frag">Open account</p>
                        <p class="footer-frag">Individual</p>
                        <p class="footer-frag">Joint</p>
                        <p class="footer-frag">Corporate</p>

                         <SPAN>ABOUT TRADEVIEW</SPAN>
                            <p class="footer-frag">Out Story</p>
                            <p class="footer-frag">Out Team</p>
                            <p class="footer-frag">Our Vision</p>

                            <span>COMPANY</span>
                                <p class="footer-frag">Why Tradeview</p>
                                <p class="footer-frag">Sponsorships</p>
                                <p class="footer-frag">Press</p>
                           
                    </div>
                    <div>
                      <span>SOFTWARE</span>
                            <p class="footer-frag">MetaTrader 4</p>
                            <p class="footer-frag">MetaTrader 5</p>
                            <p class="footer-frag">cTrader</p>
                            <p class="footer-frag">cTrader Copy</p>
                             <p class="footer-frag">CurreneX</p>

                             <span>SUPPORT</span>
                                <p class="footer-frag">Forms and Documents</p>
                                <p class="footer-frag">FAQ</p>
                                
                    </div>



                </div>

             
            </div>

        </div>





        <div class="footer-text-contain">

          <div>
            <p class="footer-frag">
              <span>IMPORTANT NOTICE TO CLIENTS REGARDING CRYPTO CURRENCY PROHIBITION.</span> Please be advised that Tradeview
              Markets does not accept cryptocurrency for deposit into client accounts. All deposits to client accounts must be
              made in fiat currency, such as USD, JPY, EUR, GBP, CAD and MXN. Clients using third party payment providers are
              prohibited from depositing cryptocurrency into the Tradeview Markets account with the third party payment
              provider and then converting the crypto currency to fiat currency for further deposit into their account.
              Tradeview must be able to trace all deposits back to a regulated financial institution. Violations of this
              anti-money laundering compliance provision regarding the use of crypto currency as a source for deposit into
              your Tradeview Markets account will result in the immediate liquidation of all open positions in your account
              and the permanent closure of your account.
            </p>

          </div>


          <div class="terms">
            <p class="footer-frag">
              There is a risk of loss in trading foreign currencies and it is not suitable for everyone. We are compensated
              for our services throught the bid-ask spread. Tradeview is not responsable for any gains or losses on currency
              rates or exchanges during any transaction.

            </p>
            <p class="footer-frag">The services and products offered by Tradeview Markets are not being offered within the
              United States(US) and not being offered to US Persons, as defined unde US law. the information on this website
              is not directed to residents of any country where FX and/or CFDs trading is restricted or prohibited by local
              laws or regulations</p>


          </div>
        </div>



        <div class="licensed">
          <div>
            <h4 class="footer-tittle">Tradeview Ltd</h4>
            <p class="footer-frag">Is licensed to carry on securities investment business and is regulated by the Cayman
              Islands Monetary Authority (CIMA) as a full securities broker-dealer. (License #585163) Tradeview conducts
              business pursuant to the Cayman Islands Securities Investment Business Law (SIBL) and its activities fall under
              the direct supervision of the Investments and Securities Division of CIMA. Headquarters: Grand Cayman, KY1-1002,
              4th Floor Harbour Place | 103 South Church St, PO Box 1105. Website: www.tradeviewforex.com</p>

          </div>
          <div>
            <h4 class="footer-tittle">TVM Global Ltd.</h4>
            <p class="footer-frag"> Is licensed and regulated by the Labuan Financial Services Authority (FSA) as a Money
              Broker, registration number LL15870 licensed to facilitate transactions in foreign exchange pursuant to Labuan
              Financial Services and Securities Act 2010, the Labuan Companies Act 1990 and the Labuan Business Activity Tax
              Act 1990. Headquarters: International Business Financial Centre at Office 5, Jamie Business Center I, Unit F10,
              First Floor, Paragon Labuan, Jalan Mustapha, 87000 Labuan F.T. Website: www.tvmgloballtd.com</p>

          </div>
          <div>
            <h4 class="footer-tittle">Tradeview Europe Ltd. </h4>
          <p class="footer-frag">Is licensed as a Category 2 Investment Service Company and is regulated by the Malta
            Financial Services Authority (MFSA). The Malta Financial Services Authority (MFSA) is the single regulator for
            financial services in Malta. MFSA is a fully autonomous public institution and reports to Parliament on an
            annual basis. The MFSA is a member of the European Banking Authority (EBA), the European Securities and Markets
            Authority (ESMA) and the International Organization of Securities Commissions (IOSCO) and is a signatory of the
            Multilateral Memorandum of Understanding with other European regulatory Institutions. Tradeview is authorized to
            provide financial services across multiple asset classes and is passported in the EU/EEA under MiFID II (EU
            Markets in Financial Instruments Directive). Headquarters: Floor 6, Suite 3, Airways House, High Street, Sliema
            SLM1549, Malta. Website: www.tradeview.eu</p>

        </div>
        <div>
          <h4 class="footer-tittle">Tradeview Financial Markets S.A.C Global</h4>
          <p class="footer-frag"> Is authorized to conduct business pursuant to and in compliance with the General Law of
            Companies (LGS) promulgated by the government of Peru. Tradeview Financial Markets S.A.C is registered with the
            National Superintendence of Public Registries (SUNARP), company number 13089531. Tradeview Financial Markets
            S.A.C provides financial services in selected OTC derivative markets in compliance with all applicable
            government regulations. Headquarters: Los Mirtos 239 Urb. San Eugenio, Lince, Lima, Perú. Website:
            www.tradeviewlatam.com</p>

        </div>
        <div>
          <h4 class="footer-tittle">iLC Brokers Ltd. iLC Brokers Ltd.</h4>
          <p class="footer-frag"> is authorized under the Mauritius Financial Service Commission with a Global Business
            License and Investment Dealer License #GB20025800 to provide financial services to professional and
            non-professional clients. Headquarters: 6 St. Denis Street, 1/F River Court, Port Louis 11328 Mauritius.
            Website: www.ilcbrokers.com</p>

        </div>
        <div>
          <h4 class="footer-tittle">TVCM Limited (Tradeview UK)</h4>
          <p class="footer-frag"> Is a limited company registered in England & Wales under Company Number 08648747 and is
            authorised and regulated by the Financial Conduct Authority FRN: 990586 Headquarters: 85 Great Portland Street,
            London W1W 7LT. Website: www.tradeview.co.uk</p>

        </div>
      </div>
    </footer>


    
</template>

