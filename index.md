# AcroLib

<!--![acrolib-logo](assets/acrolib-logo.png)-->

![acrolib-splash](assets/Reading-Acrobats-Refined-Colorised.png)

International Library of Acrobatic Gymnastics

<h2 class="h2-news">Initiatives</h2>
<ul class="news">
  <li>Revive Recreational Acrobatics<br>
  <span><a>read more</a></span></li>
  <li>Extra Points for Extra Strength<br>
  <span><a>read more</a></span></li>
</ul>

<h2 class="h2-events">Events</h2>
<ul class="events">
  <li><div class="date"><time>16-20 <br> APR</time></div> <div><span>Luxembourg</span> <br> European Championships 2025</div></li>
  <li><div class="date"><time>07-17 <br> AUG</time></div> <div><span>Chengdu, China</span> <br> World Games 2025</div></li>
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

  img {
    /* background: var(--light); */
    border: 1px solid;
    filter: grayscale(100%);
    margin-bottom: -40px;
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
    padding: 0 30px;
    margin-top: 50px;
    font-weight: normal;
  }

  .news {
    color: black;
    list-style: none;
    padding: 20px;
  }
  
    .news ul {
    }
  
    .news li {
      background: light-dark(grey, #212121);
      color: light-dark(black, var(--light));
      margin-bottom: 1px;
      padding-left: 20px;
    }

    .news span {
      text-align: right;
      font-size: 14px;
    }
  
  .events {
    background: var(--highlight);
    color: black;
    list-style: none;
    padding: 20px;
    margin: 0 -10px;
  }
    .events ul {
      list-style: none;
      padding: 10px;
      margin: 0 -10px;
    }
    .news li, .events li {
      border: 1px solid;
      height: 60px;
      display: flex;
      align-items: center;
    }

    .events li {
      margin-bottom: -1px;
      text-transform: uppercase;
    }

    .news li {
      justify-content: space-between;
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
    }

  main {
    padding-bottom: 0;
  }

  footer {
    display: none;
  }
</style>
