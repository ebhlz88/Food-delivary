<template>
  <div id="container">
    <div class="flex-container">
      <i class="fa-solid fa-arrow-left backicon"></i>
      <button><b>Copy</b></button>
      <p>2343pg</p>
      <div class="custom-select" style="width: 200px">
        <select v-model="selectedValue">
          <option disabled value="">Please select one</option>
          <option v-for="item in filters" :value="item" :key="item">
            {{ item }}
          </option>
        </select>
      </div>
    </div>
    <div class="ee">
      <div class="subdiv">
        <div class="classborder">
            <div>
          <div id="subdivv" class="subdiv">
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <a href="">OPDRACHTGEVER</a>
                  <p><b>Foodlogics B.V</b></p>
                  <p>kerkstraat 41 <br />Amersfort<br />3423</p>
                </div>

                <div class="group">
                  <p>0316548894654</p>
                  <p>baloch@gmail.com</p>
                </div>

                <div class="group">
                  <p class="header">Contact</p>
                  <p>baloch</p>
                </div>
              </div>
            </div>
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <p class="header">Reference</p>
                  <p>TR453</p>
                </div>
                <div class="group">
                  <p class="header">CRM Number</p>
                  <p>5646243535</p>
                </div>
                <div class="group">
                  <p class="header">Soort transport</p>
                  <p>Gekoeld transport</p>
                </div>
              </div>
            </div>
            <!-- <br>
            <div>
                <p class="header">Note</p>
                <p class="note">this is a note</p>
            </div> -->
          </div>
          </div>
          
        </div>
        <div class="classborder">
          <div class="left">
            <div class="group">
              <a href="">VERSOPBER</a>
              <p><b>Foodlogics B.V</b></p>
              <p>kerkstraat 41 <br />Amersfort<br />3423</p>
            </div>

            <div class="group">
              <p>0316548894654</p>
              <p>baloch@gmail.com</p>
            </div>

            <div class="group">
              <p class="header">Contact</p>
              <p>baloch</p>
            </div>
          </div>
        </div>
      </div>
          <div class="subdiv">
              <div class="classborder">
                  <div class="subdiv">
                      <a href="">INKOOP</a>
                      <p class="right fontsize110"><b>100,00  $</b></p>
                  </div>
                  <div class="subdiv form">
                      <input class="firstinput" type="text" placeholder="Basis transport">
                      <input type="text" placeholder="Price">
                      <input type="text" placeholder="Percent">
                      <p class="pardollar">10000 $</p>
                  </div>
                  <div class="subdiv form">
                        <img src="../assets/plus.png" alt="Add">
                        <img class="right" src="../assets/warning.png" alt="waring">
                        <button class="btn-primary">Send</button>
                  </div>
                  <div class="subdiv form">
                        <input type="text" placeholder="Inkoop factummemer">
                  </div>
              </div>
              <div class="classborder">
                   <div class="subdiv">
                      <a href="">MARGE</a>
                      <p class="right fontsize110"><b>100,00  $</b></p>
                  </div>
              </div>
              <div class="classborder">
                  <div class="subdiv">
                      <a href="">INKOOP</a>
                      <p class="right fontsize110"><b>100,00  $</b></p>
                  </div>
                  <div class="subdiv form">
                      <input class="firstinput" type="text" placeholder="Basis transport">
                      <input type="text" placeholder="Price">
                      <input type="text" placeholder="Percent">
                      <p class="pardollar">10000 $</p>
                  </div>
                  <div class="subdiv form">
                        <button class="btn-primary verbutton">Invoice</button>
                        <button class="btn-primary verbutton">10/20/2022</button>
                  </div>
                  
              </div>
          </div>
          <div class="subdiv">
              <div class="classborder">
                  <div id="subdivv" class="subdiv">
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <a href="">LADADRES</a>
                  <p><b>Foodlogics B.V</b></p>
                  <p>kerkstraat 41 <br />Amersfort<br />3423</p>
                </div>

                <div class="group">
                  <p>0316548894654</p>
                  <p>baloch@gmail.com</p>
                </div>
                <div class="group">
                  <p>M  07:00-12:00  13:00-17:00</p>
                </div>
              </div>
            </div>
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <p class="header">Laadatum</p>
                  <p>TR453</p>
                </div>
                <div class="group">
                  <p class="header">Van</p>
                  <p>5646243535</p>
                </div>
                <div class="group">
                  <p class="header">Load Reference</p>
                  <p>5646243535</p>
                </div>
                <div class="group">
                  <p class="header">Contact</p>
                  <p>Gekoeld transport</p>
                </div>
                <div class="group">
                  <p class="header">Note</p>
                  <p class="note">This is a note</p>
                </div>
              </div>
            </div>
          </div>
              </div>
              <div class="classborder">
                <div id="subdivv" class="subdiv">
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <a href="">OPDRACHTGEVER</a>
                  <p><b>Foodlogics B.V</b></p>
                  <p>kerkstraat 41 <br />Amersfort<br />3423</p>
                </div>

                <div class="group">
                  <p>0316548894654</p>
                  <p>baloch@gmail.com</p>
                </div>

                <div class="group">
                  <p class="header">Contact</p>
                  <p>baloch</p>
                </div>
              </div>
            </div>
            <div class="classborder">
              <div class="left">
                <div class="group">
                  <p class="header">Reference</p>
                  <p>TR453</p>
                </div>
                <div class="group">
                  <p class="header">CRM Number</p>
                  <p>5646243535</p>
                </div>
                <div class="group">
                  <p class="header">Soort transport</p>
                  <p>Gekoeld transport</p>
                </div>
              </div>
            </div>
          </div>
              </div>
          </div>
          <div class="classborder">
              <div >
                  <table>
      <thead>
        <tr>
          <th>Loading spec</th>
          <th>qty pits</th>
          <th>Packaging</th>
          <th>Packaging/colli</th>
          <th>Pallete places</th>
          <th>Weight bruto(kg)</th>
          <th>Weight netto(kg)</th>
          <th>Marken en ciffers</th>
          <th>Goederen en duoanecode</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Frozen fish</td>
          <td>16</td>
          <td>Euro pallete</td>
          <td></td>
          <td>16</td>
          <td>15400</td>
          <td>14885</td>
          <td></td>
          <td>B89087</td>
        </tr>
       
           
        
      </tbody>
    </table>
              </div>
          </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      filters: ["data1", "data2", "data3"],
      selectedValue: 0,
    };
  },
};
</script>

<style>
#container {
  margin: 7px 15px;
  margin-left: 225px;
}
#container .flex-container {
  justify-content: space-between;
}
.subdiv {
  display: flex;
  align-items: stretch;
  padding: 10px 0px;
}
.backicon {
  background-color: rgb(250, 250, 250);
  border-radius: 50%;
  padding: 10px;
  box-shadow: 0px 1px 2px black;
}
.backicon:hover {
  cursor: pointer;
}
#container .flex-container button {
  padding: 10px 50px;
  border-radius: 25px;
  background-color: rgb(255, 255, 255);
  border: none;
  box-shadow: 0px 1px 2px black;
}
#container .flex-container button:hover {
  cursor: pointer;
}
.classborder {
  border-radius: 20px;
  margin: 3px;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.26);
  padding-left: 27px;
}
.subdiv .classborder {
  width: 50%;
}
.ee {
  border: solid 1px rgb(204, 204, 204);
  font-size: 73%;
  padding: 0px 10px;
}
#subdivv .classborder {
  border: none;
  box-shadow: none;
}
.left {
  text-align: left;
}
.header {
  color: rgb(104, 104, 104);
  font-size: 65%;
}
.group {
  margin: 15px 0px;
}
.subdiv a {
  font-size: 21px;
  margin-bottom: 10px;
}

.subdiv img{
    height: 20px;
}
.right{
    margin: auto 0px;
    margin-left: auto;
    margin-right: 10px
    
}
.fontsize110{
    font-size: 130%;
}
.form{
    margin-right: 10px;
}
.form input{
    border: none;
    border-block-end: solid 1px;
    width: 23%;
    margin: 0px 4px;
    font-size: 90%;
    font-family: Arial, Helvetica, sans-serif;
}
.form input:focus{
    border: none;
    border-block-end: solid 1px;
    outline: 0;
}
.firstinput{
    width: 40% !important;
}
.btn-primary{
    border: none;
    border-radius: 30px;
    width: 70px;
    background-color: #1298eb;
    color: white;
    padding: 7px 25px;
}
.btn-primary:hover{
    cursor: pointer;
}
.verbutton{
    margin: 10px 20px;
    width: 130px;
}
.note{
    color: rgb(72, 129, 235);
}
.subdiv a{
    color: rgb(72, 129, 235);
}
/* table */
table {
  border-spacing: 1;
  border-collapse: collapse;
  background: white;
  border-radius: 6px;
  overflow: hidden;
  width: 100%;
  margin: 0 auto;
  position: relative;
}
table * {
  position: relative;
  
  
}
table td, table th {
  padding-left: 8px;
}
table thead tr {
  height: 60px;
  background: #ffffff00;
  border-block-end: solid 1px;
  font-size: 12px;
}
table tbody tr {
  height: 48px;
  border-bottom: 1px solid #E3F1D5;
}
table tbody tr:last-child {
  border: 0;
}
table td, table th {
  text-align: left;
}
table td.l, table th.l {
  text-align: right;
}
table td.c, table th.c {
  text-align: center;
}
table td.r, table th.r {
  text-align: center;
}

@media screen and (max-width: 35.5em) {
  table {
    display: block;
  }
  table > *, table tr, table td, table th {
    display: block;
  }
  table thead {
    display: none;
  }
  table tbody tr {
    height: auto;
    padding: 8px 0;
  }
  table tbody tr td {
    padding-left: 45%;
    margin-bottom: 12px;
  }
  table tbody tr td:last-child {
    margin-bottom: 0;
  }
  table tbody tr td:before {
    position: absolute;
    font-weight: 300;
    width: 40%;
    left: 10px;
    top: 0;
  }
  table tbody tr td:nth-child(1):before {
    content: "Code";
  }
  table tbody tr td:nth-child(2):before {
    content: "Stock";
  }
  table tbody tr td:nth-child(3):before {
    content: "Cap";
  }
  table tbody tr td:nth-child(4):before {
    content: "Inch";
  }
  table tbody tr td:nth-child(5):before {
    content: "Box Type";
  }
  #container{
    margin-left: 0;
  }
  .subdiv .classborder {
  width: 99%;
  padding-left: 9px;
  margin: 12px 0px;
}
  .subdiv{
    display: block;
  }

}

blockquote {
  color: white;
  text-align: center;
}
.pardollar{
  width: 16%;
}
</style>