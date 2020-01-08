<template>
<body>
  <div class="child">
    <div class="summoner">
      <div class="data"><img src="https://ddragon.leagueoflegends.com/cdn/7.8.1/img/profileicon/1439.png"/></div>
      <div class="data">
        <p>Gwangjin</p>
        <div class="level">Level 30</div>
      </div>
      <div class="data"></div>
      <div class="data"><img class="rank" src="https://vignette.wikia.nocookie.net/leagueoflegends/images/8/8a/Season_2019_-_Gold_2.png/revision/latest?cb=20181229234921"/></div>
      <div class="data">
        <p>Gold I</p>
        <div class="stats">Ranked Solo</div>
        <div class="stats">34W - 22 L | 75LP</div>
        <div class="stats">Win Ratio: <span>61%</span></div>
      </div>
      <div class="data"><img class="rank" src="https://elofactory.com/sites/default/files/gold_1.png"/></div>
      <div class="data">
        <p>Gold V</p>
        <div class="stats">Ranked Flex</div>
        <div class="stats">10W - 11 L | 75LP</div>
        <div class="stats">Win Ratio: <span>48%</span></div>
      </div>
      <div class="data"></div>
    </div>
  </div>
  <div class="child">

    <div class="container">
      <div class="champ"> <img src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Graves.png"/>
        <div class="title">Graves</div>
      </div>
      <div class="summoners">
        <div class="real"><img class="item" src="http://ddragon.leagueoflegends.com/cdn/7.8.1/img/spell/SummonerFlash.png"/>
        <img class="item" src="http://ddragon.leagueoflegends.com/cdn/7.8.1/img/spell/SummonerSmite.png"/></div>
        <div class="keystone"><img class="item key" src="http://ddragon.leagueoflegends.com/cdn/img/perk-images/Styles/Domination/Predator/Predator.png"/></div>
      </div>
      <div class="gameinfo">
        <div class="match-status">Loss
          <div class="match-type">Ranked Solo</div>
        </div>
        <div class="kda">
          <div class="score">0 <span>| </span>9 <span>|</span>1</div>
          <div class="kdatotal">0.80:1 KDA</div>
        </div>
      </div>
      <div class="equips">
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/>
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/>
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/>
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/>
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/>
        <img class="item" src="http://static.inven.co.kr/image_2011/site_image/lol/dataninfo/icon/item/1001.png?v=20191212a"/></div>
      <div class="teams">
        <div class="team">
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Lux.png"/>
          <span>Fuck League</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/LeeSin.png"/>
          <span>Peter Lee</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Vayne.png"/>
          <span>Maniac7</span></div>
          <div class="player"> <img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Ezreal.png"/>
          <span>Imistakento</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Thresh.png"/>
          <span>Owenbz</span></div>
        </div>
      </div>
      <div class="teams">
        <div class="team">
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Caitlyn.png"/>
          <span>Tobi Sways</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Graves.png"/>
          <span>orctamer</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Fiora.png"/>
          <span>IPortgasDAce</span></div>
          <div class="player"> <img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/AurelionSol.png"/>
          <span>khs9700</span></div>
          <div class="player"><img class="icon" src="http://ddragon.leagueoflegends.com/cdn/7.9.1/img/champion/Blitzcrank.png"/>
          <span>Oct 18</span></div>
        </div>
      </div>
    </div>
  </div>
</body>
</template>
<style scoped>
body {
  font-family: "Open Sans";
  background-color: #030404;
}

.container {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.win {
  color: #90C048;
}

.match-status {
  width: 50%;
  text-align: center;
}

.container .summoners {
  display: flex;
}

.summoners .real {
  width: 50%;
  text-align: right;
}

.summoners .keystone {
  width: 50%;
  display: flex;
  align-items: center;
}

.container .gameinfo {
  display: flex;
  font-weight: 200;
  font-size: 38px;
  color: #ED4337;
}

.match-type {
  font-size: 14px;
  color: #777;
}

.games {
  max-width: 1600px;
  margin: auto;
}

.title {
  position: relative;
  font-size: 12px;
  top: -24px;
  width: 115px;
  padding: 6px 2px;
  margin: auto;
  text-shadow: 0px 1px 1px #000;
  text-align: center;
  text-transform: uppercase;
  background-color: rgba(0, 0, 0, 0.6);
  color: white;
  font-weight: bold;
}

.champ img {
  margin: auto;
  display: block;
}

.score {
  display: flex;
  color: white;
  font-size: 18px;
  margin-top: 10px;
  justify-content: center;
}
.score span {
  color: #666;
}

.kda {
  width: 50%;
}

.kdatotal {
  font-size: 14px;
  margin: 13px 0 0 0;
  flex-direction: column;
  color: #777;
  text-align: center;
}

.equips {
  text-align: center;
}

.item {
  display: inline-block;
  border-radius: 6px;
  margin: 0 5px 10px 5px;
  width: auto;
  height: 55px;
}

.key {
  height: 45px;
  width: auto;
}

.child {
  display: flex;
  flex-direction: column;
  margin: 10px;
  background-color: #131616;
  border-top: 1px solid #242424;
  border-bottom: 1px solid #242424;
}

.teams {
  flex-grow: 1;
}

.team {
  font-size: 16px;
  color: white;
  text-align: center;
  flex-direction: row;
  height: 180px;
  margin: 10px 0;
  padding-left: 15%;
  flex-direction: row;
}

.player {
  text-align: left;
  display: flex;
  item-align: center;
  padding: 5px;
}

.player span {
  margin-left: 10px;
  padding-top: 2px;
  color: #777;
}

.icon {
  display: flex;
  width: 25px;
  height: 25px;
}

.champion {
  display: flex;
}

.info {
  background-color: #222;
  display: flex;
  font-size: 16px;
  width: 100%;
  color: #999;
  text-transform: uppercase;
  flex-direction: row;
  text-align: center;
}

.champ {
  width: 15%;
}

.summoners {
  width: 15%;
}

.gameinfo {
  width: 20%;
}

.equips {
  width: 20%;
}

.teams {
  width: 20%;
}

.summoner {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.summoner p {
  display: flex;
  margin: 0 10px;
  font-size: 32px;
  color: #ddd;
  text-align: center;
}

.level {
  font-size: 18px;
  text-align: center;
  margin: 0 10px;
  color: #777;
}

.stats {
  font-size: 14px;
  text-align: left;
  margin: 0 10px;
  color: #777;
}

.stats span {
  color: #90C048;
}

.data {
  display: flex;
  flex-direction: column;
}

.rank {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100px;
}

.data:nth-child(3) {
  flex-grow: 1;
}

.data:last-child {
  flex-grow: 1;
}

.logo {
  text-align: center;
  font-size: 3em;
  color: #777;
}

.fa-cube {
  color: black;
  margin-top: 30%;
}

.fa-circle {
  color: #777;
  margin-top: 30%;
}

.logo h4 {
  font-size: 0.8em;
}

.footer {
  background: #111;
  color: #777;
  text-align: center;
  display: flex;
  flex-direction: column;
  text-align: center;
  font-size: 0.8em;
  padding: 30px;
}

.footer p {
  width: 80%;
  margin: 0 auto;
}

.fa-cube:before {
  margin-left: 6px;
}

</style>