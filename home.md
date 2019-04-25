<!-- TITLE: Home -->
<!-- SUBTITLE: A quick summary of Home -->
<header>
        <nav  class="h-menu flex-align-self-center">
          <ul class="h-menu bg-red fg-white">
              <li><a href="#">Home</a></li>
              <li><a href="#">Entretenimiento</a></li>
              <li><a href="#" class="dropdown-toggle">Deportes</a></li>
              <ul class="d-menu" data-role="dropdown">
                <li><a href="#">Futbol</a></li>
                <li><a href="#">Baloncesto</a></li>
                <li><a href="#">Ciclismo</a></li>
              </ul>
              <li><a href="#">Judiciales</a></li>
          </ul>
        </nav>
        <div class="row">
          <div class="cell-sm">
            <img src="img/logo.jpg" width="20%">
          </div>
          <div class="cell-sm">
            <p>&nbsp;</p>
              <input type="text" data-role="input" data-search-button="true">
          </div>
      </div>
    </br>
      <div data-role="carousel"
           data-cls-controls="fg-cyan"
           data-ato-start="true"
           data-height="@ (max-width: 1366px),150 |(max-width: 992px),150 | (max-width: 768px),100 | (max-width: 576px),100">
          <div class="slide" data-cover="img/slide1.jpg"></div>
          <div class="slide" data-cover="img/slide2.jpg"></div>
          <div class="slide" data-cover="img/slide3.jpg"></div>
      </div>                      
  </header>
  <div class="row">
  <div class="cell-sm-3">
    <ul class="h-menu bg-red fg-white"><h4>Barra izquierda</h4></ul>
    <section>
      <h1>Barra izquierda</h1>
    </section>
  </div>
  <div class="cell-sm-6">
      <ul class="h-menu bg-red fg-white"><h4>News</h4></ul>
      <section>
          <table class="table table-border cell-border">
              <tbody>
                  <tr>
                      <td class="alert">
                        <img src="https://www.placecage.com/200/200">
                      </td>
                      <td>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iste amet atque qui laborum rem cumque veritatis odit natus consequuntur obcaecati quod iusto, omnis sint quas dignissimos odio aspernatur, commodi velit?
                        <a href="">Leer mas</a>
                      </td>
                    </tr>
                    <tr>    
                      <td class="alert">
                          <img src="https://placeimg.com/200/200/people">
                        </td>
                        <td>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iste amet atque qui laborum rem cumque veritatis odit natus consequuntur obcaecati quod iusto, omnis sint quas dignissimos odio aspernatur, commodi velit?
                            <a href="">Leer mas</a>
                        </td>
                        
                  </tr>
              </tbody>
          </table>
      </section>
    </div>
    <div class="cell-sm-3">
        <ul class="h-menu bg-red fg-white"><h4>Destacadas</h4></ul>
        <section>
          <h1>Barra izquierda</h1>
        </section>
      </div>
  </div>
  <footer>
  <div class="row">
    <div class="cell">
      <ul class="h-menu bg-red fg-white"><h4>Pie de pagina</h4></ul>
    </div>
  </div>
  </footer>
</div>