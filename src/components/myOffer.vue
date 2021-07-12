<template>
  <div class="Info">
      <div class="InfoHead">
        <p>Предложения</p>
        <form>
            <i class='bi bi-search'></i>
            <input class="form-control" type="search" placeholder="Поиск" aria-label="Search">
            <img class="avatar" src="../assets/avatar-2.png">
        </form>
      </div>
      <div class="FilterButtons">
          <div class="ActiveButton"><i class='bi bi-check2-circle'></i><p>Активные</p></div>
          <div><i class='bi bi-clock'></i><p>На модерации</p></div>
          <div><i class='bi bi-pen'></i><p>Черновики</p></div>
          <div><i class='bi bi-archive'></i><p>Архив</p></div>
      </div>

    <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
            <div class="card">
                <div class="CardHead">
                    <div class="CardLogo">
                        <img src="https://i.pinimg.com/originals/af/fa/c8/affac8291f25d7a2b8ed53df44922e6c.png">
                        <p>Nike</p>
                    </div>
                    <div class="State">Активное</div>
                </div>
            <div class="WearImg"></div>
            <div class="card-body">
                <h5 class="card-title">Записать сторис в кросcовках Nike Air Max 720</h5>
                <div class="GiftMessage">
                    <i class='bi bi-gift'></i>
                    <div>Репост строис в официальном аккаунте NikeRussia</div>
                </div>
                <div class="CardFunction NewMessages">
                    <p>Новые сообщения</p>
                    <div>
                        <div>55</div> 
                        <i class='bi bi-arrow-right-short'></i>
                    </div>
                </div>
                <div class="CardFunction NewApplications">
                    <p>Новые заявки</p>
                    <div>
                        <div>44</div> 
                        <i class='bi bi-arrow-right-short'></i>
                    </div>
                </div>
                <div class="CardFunction Timer">
                    <p>До завершения</p>
                    <div>00:00:00</div>
                </div>
                <div class="CardFunction Executed">
                    <p>Выполнено</p>
                    <div>250/3000</div>
                </div>
            </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <div class="CardHead">
                    <div class="CardLogo">
                        <img src="https://i.pinimg.com/originals/af/fa/c8/affac8291f25d7a2b8ed53df44922e6c.png">
                        <p>Nike</p>
                    </div>
                    <div class="State">Активное</div>
                </div>
            <div class="WearImg"></div>
            <div class="card-body">
                <h5 class="card-title">Записать сторис в кросcовках Nike Air Max 720</h5>
                <div class="GiftMessage">
                    <i class='bi bi-gift'></i>
                    <div >Репост строис в официальном аккаунте NikeRussia</div>
                </div>
                <div class="CardFunction NewMessages">
                    <p>Новые сообщения</p>
                    <div>
                        <div>55</div> 
                        <i class='bi bi-arrow-right-short'></i>
                    </div>
                </div>
                <div class="CardFunction NewApplications">
                    <p>Новые заявки</p>
                    <div>
                        <div>44</div> 
                        <i class='bi bi-arrow-right-short'></i>
                    </div>
                </div>
                <div class="CardFunction Timer">
                    <p>До завершения</p>
                    <div>00:00:00</div>
                </div>
                <div class="CardFunction Executed">
                    <p>Выполнено</p>
                    <div>250/3000</div>
                </div>
            </div>
            </div>
        </div>
        <div class="col">
            <div class="card">
                <div class="CardHead">
                    <div class="CardLogo">
                        <img src="https://i.pinimg.com/originals/af/fa/c8/affac8291f25d7a2b8ed53df44922e6c.png">
                        <p>Nike</p>
                    </div>
                    <div class="State">Активное</div>
                </div>
            <div class="WearImg"></div>
            <div class="card-body">
                <h5 class="card-title">Записать сторис в кросcовках Nike Air Max 720</h5>
                <div class="GiftMessage">
                    <i class='bi bi-gift'></i>
                    <div >Репост строис в официальном аккаунте NikeRussia</div>
                </div>
            </div>
            </div>
        </div>
         <div class="col">
            <div class="card">
                <div class="CardHead">
                    <div class="CardLogo">
                        <img src="https://i.pinimg.com/originals/af/fa/c8/affac8291f25d7a2b8ed53df44922e6c.png">
                        <p>Nike</p>
                    </div>
                    <div class="State">Активное</div>
                </div>
            <div class="WearImg"></div>
            <div class="card-body">
                <h5 class="card-title">Записать сторис в кросcовках Nike Air Max 720</h5>
                <div class="GiftMessage">
                    <i class='bi bi-gift'></i>
                    <div >Репост строис в официальном аккаунте NikeRussia</div>
                </div>
            </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name:"myOffer"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway&display=swap');
*{
    font-family: 'Raleway', sans-serif;
}
.Info{
    display: block;
    max-width: 100%;
    max-height:auto;
    right:0;
    background: #FAF5F2;
    margin:2vh;
    border: 6px solid rgba(39, 41, 49, 0.07);
    border-radius: 20px;
}
.InfoHead>p{
    font-family: 'Raleway', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    margin-left:4vh;
    margin-top:2vh;
}
.InfoHead{
    display:flex;
    justify-content: space-between;
    position: relative;
    margin-top:2vh;
}
.form-control{
    height:4vh;
    margin-top:2vh;
    border-radius:15px;
    width:30vh;
}
.avatar{
    width:5vh;
    height:5vh;
    border-radius: 50%;
    margin:1.5vh 3vh 0 1.5vh;
}
.InfoHead>form{
    display: flex;
}
.bi{
    font-size:2vh;
}
.InfoHead>form>i{
    line-height:8vh;
    vertical-align: center;
    margin: 0 1vh 0 1vh;
}
.FilterButtons{
    display:flex;
    max-width: 100%;
    margin:0 3vh 0 3vh;
    padding-bottom:2.5vh;
    padding-top:1.5vh;
    border-bottom: 0.5px solid #D9C4B7;
    overflow: auto;
}
.FilterButtons>div{
    display: flex;
    padding:2vh;
    white-space: nowrap;
    height: 5vh;
    margin-right:2vh;
    border-radius: 15px;
    cursor:pointer;
}
.FilterButtons>div>i{
    font-size:3vh;
    margin-right:2vh;
    margin-top:-1.5vh;
}
.FilterButtons>div>p{
    line-height: 1vh;
    vertical-align: center;
    font-weight:600;
    color: #2D3134;
}
.bi-check2-circle{
    color:#00C667;
}
.bi-clock{
    color:#2C98F0;
}
.bi-pen{
    color:#FE8862;
}
.bi-archive{
    color:#9A99B8;
}
.ActiveButton{
    background-color: white;
}
.row{
    padding: 3vh;
}
.card{
    border:none;
    box-shadow: 0px 10px 20px rgba(233, 216, 207, 0.3);
    border-radius: 4px 20px 20px 20px;
}
.CardHead{
    display:flex;
    justify-content: space-between;
    padding:2vh 2vh 0 2vh;
}
.CardLogo>img{
    width:5vh;
    height:5vh;
    border-radius: 15px;
}
.CardLogo{
    display:flex;
    line-height:5vh;
    vertical-align: center;
    color: #272931;
}
.CardLogo>p{
    margin-left:1vh;
    font-weight: 700;
}
.State{
    background-color: #ebfbf3;
    color: #00C667;
    width:10vh;
    height:3vh;
    font-weight:600;
    text-align: center;
    line-height:3vh;
    vertical-align: center;
    border-radius: 8px;
    margin-top:1vh;
}
.WearImg{
    width:auto;
    height: 20vh;
    margin:0vh 2vh 0 2vh;
    border-radius: 0 15px 15px 15px;
    background-image: url("../assets/boots1.png");
    background-size: 100% ;
    background-position: bottom;
}
.card-title{
    font-weight:700;
    color: #272931;
    margin-bottom: 2vh;
}
.GiftMessage{
    display:flex;
    color:#FC5A8B;
    font-weight: 700;
    min-height:5vh;
}
.GiftMessage>i{
    margin-right:2vh ;
    font-size:2vh;
    line-height: 4vh;
    vertical-align: center;
}
.GiftMessage>div{
    line-height: 3.5vh;
    vertical-align: center;
}
.CardFunction{
    padding: 2vh 0 0 0;
    border-top: 0.5px solid #D4D8E3;
    font-weight: 600;
    color:#272931;
    display:flex;
    justify-content: space-between;
    line-height: 4vh;
    vertical-align: middle;
}
.NewMessages>div>div,.NewApplications>div>div{
    width:5vh;
    height: 5vh;
    color:white;
    background-color: #F93C47;;
    border-radius: 50%;
    line-height: 4.5vh;
    vertical-align: middle;
    text-align: center;
    margin-top:-0.5vh;
}
.NewMessages>div,.NewApplications>div{
    display: flex;
}
.NewMessages>div>i,.NewApplications>div>i{
   font-size:4vh;
}
.Timer>div{
    background-color: #fff6f3;
    color:#FE8862;
    height:4vh;
    padding:0 2vh 0 2vh;
    border-radius: 15px;
}
.Executed>div{
    background-color: #00C667;
    color:#FFFFFF;
    height:4vh;
    padding:0 2vh 0 2vh;
    border-radius: 15px;
}
@media(max-width:500px){
.Info{
    position:absolute;
    width: auto;
    max-height:auto;
    left:0;
    background: #FAF5F2;
    margin:0;
    margin-top:15vh;
    border:none;
    border-top: 6px solid rgba(39, 41, 49, 0.07);
    border-radius: 20px 20px 0 0;
}
.WearImg{
    width:auto;
    height: 20vh;
    margin:0vh 2vh 0 2vh;
}
.col{
    padding:3vh;

}
.GiftMessage{
    margin-bottom:2vh ;
}
.State{
    width:15vh;
    height:5vh;
    text-align: center;
    line-height:5vh;
    vertical-align: center;
    margin-top:0vh;
}
.FilterButtons>div>p{
    font-weight:600;
    color: #2D3134;
}
.InfoHead{
    display: block;
}
.InfoHead>p{
    text-align: center;
    margin-bottom:0;
}
.form-control{
    height:4vh;
    border-radius:15px;
    width:90%;
    padding:0 4vh 0 2vh;
}
.avatar{
    width:5vh;
    height:5vh;
    border-radius: 50%;
    display: none;
}
}
</style>