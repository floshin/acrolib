# AcroLib

![acrolib-splash](assets/acrolib-splash-3.png)

International Library of Acrobatic Gymnastics

<h2 class="h2-news">Initiatives</h2>
<ul class="news">
  <li>Revive Recreational Acrobatics<br>
  <span><a href="">read more</a></span></li>
  <li>Extra Points for Extra Strength<br>
  <span><a href="">read more</a></span></li>
</ul>

<h2 class="h2-events">Events</h2>
<ul class="events">
  <li><div class="date"><time>16-20 <br> APR</time></div> <a href="https://www.europeangymnastics.com/event/2025-european-championships-acrobatic-gymnastics-luxembourg-lux/overview"><div><span>Luxembourg</span> <br> European Championships 2025</div></a></li>
  <li><div class="date"><time>07-17 <br> AUG</time></div> <a href="https://www.theworldgames.org/sports/Gymnastics-59"><div><span>Chengdu, China</span> <br> World Games 2025</div></a></li>
</ul>

<style>
  h1 {
    font-size: 100px;
    text-align: center;
    padding-bottom: 0;
    padding-top: 0;
    margin: 0;
    margin-bottom: -50px;
  }

  p {
    text-align: center;
  }

  .up {
    display: none;
  }

  main img {
    /* background: var(--light); */
    border: 1px solid light-dark(var(--dark), var(--light));
    margin-bottom: -10px;
  }

  .h2-events {
    background: light-dark(var(--h2-bg), var(--dark));
    padding: 15px;
    font-size: 16px;
    margin: 50px 0 0;
    display: inline-block;
    color: light-dark(black, var(--light));
    font-weight: normal;
  }

  .h2-news {
    font-size: 16px;
    margin-top: 50px;
    padding: 0 10px;
    font-weight: normal;
  }

  .news {
    color: black;
    list-style: none;
    padding: 10px;
  }
  
    .news ul {
    }
  
    .news li {
      background: light-dark(grey, #212121);
      color: light-dark(black, var(--light));
      margin-bottom: 5px;
      padding-left: 20px;
      height: 80px;
      font-size: 20px;
    }

    .news span {
      text-align: right;
      font-size: 14px;
      padding-right: 15px;
    }

    .news span a {
      color: inherit;
      text-decoration: none;
    }

    .news span a:hover {
      text-decoration: underline;
    }
  
  .events {
    /*background: #734E50;*/
    color: white;
    list-style: none;
    padding: 20px 10px;
  }
    .events ul {
      list-style: none;
      padding: 10px;
    }
    .news li, .events li {
      display: flex;
    }

    .events a {
      color: inherit;
      text-decoration: none;
    }

    .events a:hover {
      text-decoration: underline;
    }

    .events li {
      /* border: 1px solid; 
      margin-bottom: -1px; */
      margin: 30px;
      font-size: 18px;
      /* height: 60px;
      align-items: center; */
    }

    .news li {
      flex-direction: column;
      justify-content: space-evenly;
      align-items: stretch;
    }
  
    .date {
      font-style: normal;
      border-right: 1px solid;
      padding-right: 20px;
      height: 100%;
      margin-right: 20px;
      width: 100px;
    }

    time {
      align-self: center;
      text-align: center;
    }
  
    .events span {
      font-size: 12px;
      text-transform: uppercase;
    }

  main {
    padding-bottom: 0;
  }

  footer p {
    text-align: initial;
  }

</style>
