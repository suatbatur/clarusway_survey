<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="sign_up_facebook_style.css">
  </head>
  <body>
    <h1 id="f_head"> <span>facebook</span> </h1>
    <div>
      <div id="form-container">
        <header id="form-header">
          <h1 id="form-description">Yeni Bir Hesap Oluştur</h1> 
          <h3 id="hızlı" >Hızlı ve kolaydır.</h3>
          
        </header>
        <section id="survey-form-container">
          <div id="survey-form">
            <form action="result.html" method="GET" target="_blank">
              <hr />
              <div id="ad">
                <input type="text" name="ad" placeholder="Adın" />
                <input type="text" name="soyad" placeholder="Soyadın" />
                
              </div> 
             
              <br>
              <div id="tel">
                <input
                  type="text"
                  name="tel_email"
                  placeholder="Cep Telefonu numarası veya e-posta"
                  
                />
              </div> <br>
              <div id="sifre">
                <input type="password" name="sifre" placeholder="Yeni Şifre" />
              </div> <br>
              <label id="etiket-1"> Doğum Tarihi</label> <br>
              <div class="d_tarih">
                  
                <select name="gün">
                  <option value="0">Gün</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                  <option value="5">5</option>
                  <option value="6">6</option>
                  <option value="7">7</option>
                  <option value="8">8</option>
                  <option value="9">9</option>
                  <option value="10">10</option>
                  <option value="11">11</option>
                  <option value="12">12</option>
                  <option value="13">13</option>
                  <option value="14">14</option>
                  <option value="15">15</option>
                  <option value="16" selected>16</option>
                  <option value="17">17</option>
                  <option value="18">18</option>
                  <option value="19">19</option>
                  <option value="20">20</option>
                  <option value="21">21</option>
                  <option value="22">22</option>
                  <option value="23">23</option>
                  <option value="24">24</option>
                  <option value="25">25</option>
                  <option value="26">26</option>
                  <option value="27">27</option>
                  <option value="28">28</option>
                  <option value="29">29</option>
                  <option value="30">30</option>
                  <option value="31">31</option>
                </select>
                <select name="ay">
                  <option value="0">Ay</option>
                  <option value="1">Oca</option>
                  <option value="2">Sub</option>
                  <option value="3">Mar</option>
                  <option value="4">Nis</option>
                  <option value="5">May</option>
                  <option value="6" selected>Haz</option>
                  <option value="7">Tem</option>
                  <option value="8">Agu</option>
                  <option value="9">Eyl</option>
                  <option value="10">Eki</option>
                  <option value="11">Kas</option>
                  <option value="12">Ara</option>
                </select>
                <select name="yıl">
                  <option value="2003">2003</option>
                  <option value="2002">2002</option>
                  <option value="2001">2001</option>
                  <option value="2000">2000</option>
                  <option value="1999">1999</option>
                  <option value="1998">1998</option>
                  <option value="1997">1997</option>
                  <option value="1996">1996</option>
                  <option value="1995">1995</option>
                  <option value="1994">1994</option>
                  <option value="1993">1993</option>
                  <option value="1992" selected>1992</option>
                  <option value="1991">1991</option>
                  <option value="1990">1990</option>
                  <option value="1989">1989</option>
                  <option value="1988">1988</option>
                  <option value="1987">1987</option>
                  <option value="1986">1986</option>
                  <option value="1985">1985</option>
                  <option value="1984">1984</option>
                  <option value="1983">1983</option>
                  <option value="1982">1982</option>
                </select>
              </div> <br>

              <label id="etiket-2">Cinsiyet</label> 
              <div id="cinsiyet">
                
                <input
                  type="radio"
                  name="cinsiyet"
                  id="first-radio"
                  value="kadın"
                />
                <label for="first-radio">Kadın</label>
                <input
                  type="radio"
                  name="cinsiyet"
                  id="second-radio"
                  value="erkek"
                  
                  
                />
                <label for="second-radio">Erkek</label>
                <input
                  type="radio"
                  name="cinsiyet"
                  id="third-radio"
                  value="ozel"
                />
                <label for="third-radio">Özel</label>
              </div>
              <div style="text-align: justify;" id="alt_paragraf">
                <p>
                  Kaydol düğmesine tıklayarak,  <a href="#">Koşullarımızı,</a> <a href="#">Veri İlkemizi</a> ve
                  <a href="#">Çerezler İlkemizi</a> kabul etmiş olursun. Bizden SMS Bildirimleri
                  alabilir ve bu bildirimleri istediğin zaman durdurabilirsin.
                </p>
              </div>
              <div id="button">
                <button  id="button" type="submit">Kaydol</button>

              </div>
              <div id="zaten-var-mı">
                  <p><a href="#" style="text-decoration: none;">Hesabın zaten var mı?</a></p>
              </div>
            </form>
          </div>
        </section>
      </div>
    </div>
  </body>
</html>
