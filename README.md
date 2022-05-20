<html>
  <body>
    <style>
      #card {
        display: inline-block;
        padding: 0;
        margin: 0;
      }

      #card-front,
      #card-back {
        display: inline-block;
        border: 1px solid black;
        border-radius: 15px;
        width: calc(3.5*96px);
        height: calc(2.0*96px);
        background-color: #fff;
        font-size: .7rem;
        display: inline-block;
        margin: 0;
        padding: 3px;
      }

      #card-front:hover,
      #card-back:hover {
        outline: 2px solid #ccc;
        box-shadow: 2px 2px #333;
        cursor: pointer;
      }

      #card_checkbox {
        display: none;
      }
      #card_checkbox + label > div {
        display: block;
      }
      #card_checkbox + label > div + div {
        display: none;
      }
      #card_checkbox:checked + label > div {
        display: none;
      }
      #card_checkbox:checked + label > div + div {
        display: block;
      }

      #card-front ul {
        list-style: none;
        margin: 0;
        padding: 0;
        text-align: center;
        margin-left: auto;
        margin-right: auto;
      }
      #card-front ul > li {
        margin: 0;
        padding: 0;
        text-align: center;
        margin-left: auto;
        margin-right: auto;
      }
      #card-back h1 {
        margin: 0;
        font-size: .9rem;
        border-bottom: 2px outset black;
        margin-bottom: 5px;
        display: block;
        width: 100%;
        text-align: center;
      }

      #card-back ul {
        list-style: none;
        margin: 0;
        padding: 0;
      }

      #card-back ul ul {
        list-style: square;
        margin: 0;
        padding: 0;
      }

      #card-back ul > li {
        margin-left: .66rem;
        font-weight: bold;
        padding-bottom: 1px;
      }

      #card-back ul ul > li {
        margin-left: 1.5rem;
        font-weight: normal;
        padding-bottom: 1px;
      }


      #card-front h1 {
        text-align: center;
        width: 100%;
        margin-bottom: 2px;
      }
      #card-front h2 {
        text-align: center;
        width: 100%;
        margin-bottom: 2px;
      }
      #card-front h3 {
        text-align: center;
        width: 100%;
        margin-bottom: 2px;
      }

      .scale-content-to-fit * {
        width: -moz-fit-content;
        width: fit-content;
        block-size: fit-content;
      }
    </style>
  </head>
  <body>
    <div id='card'>
      <input type='checkbox' id='card_checkbox' />
      <label for='card_checkbox'>
        <div id='card-front' class='scale-content-to-fit'>
          <h1>DSaster Designs</h1>
          <h2>Web Design, Programming, Tutoring</h2>
          <h3>Alan Lovitt</h3>
          <ul>
            <li>
              📧<br /><a href='mailto:alandsaster@outlook.com'>alandsaster@outlook.com</a>
            </li class='noselect'>
            <li class='noselect'>
              💻<br /><a href='github.com/AlanDSaster'>github.com/AlanDSaster</a>
            </li>
            <li class='noselect'>
              📞<br /><a href='tel:9892516600'>989-251-6600</a>
            </li>
          </ul>
        </div>
        <div id='card-back' class='scale-content-to-fit'>
          <div id='card-back-text'>
            <ul>
              <h1>Services Provided</h1>
              <li>
                Web Design
                <ul>
                  <li>
                    HTML / CSS / JavaScript
                  </li>
                </ul>
              </li>
              <li>
                <div>
                  Windows and Linux Application Design
                  <ul>
                    <li>
                      JavaScript packaged in Electron for Cross Platform Compatability.
                    </li>
                    <li>
                      C# programs with User Interface or Command Line Interface
                    </li>
                    <li>
                      Batch and Powershell Scripts
                    </li>
                    <li>
                      RegEx
                    </li>
                  </ul>
                </div>
              </li>
              <li>
                API Development with NodeJS
              </li>
              <li>
                Data Extraction, Input, and Management
              </li>
              <li>
                Tutoring for Microsoft Windows and Excel
                <ul>
                  <li>
                    Basic Windows Usage and Quality of Life Tips and Tricks
                  </li>
                  <li>
                    Basic Excel Usage, Cell Formulas, .csv imports, VBA Macro Design
                  </li>
                </ul>
              </li>
            </ul>
            <p>

            </p>
          </div>

          <img id='card-back-qr' />
        </div>
      </label>
    </div>
    <div>
      <a href=https://github.com/anuraghazra/github-readme-stats><img align=left src=https://github-readme-stats.vercel.app/api?username=AlanDSaster&show_icons=true&theme=dark></a>
    </div>
    <div>
      <a href=https://github.com/anuraghazra/github-readme-stats><img align=left src=https://github-readme-stats.vercel.app/api/top-langs/?username=AlanDSaster&theme=dark></a>
    </div>
  </body>
 </html>
