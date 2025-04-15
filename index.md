<div>
  <h1>AcroLib</h1>
  <img src="/assets/acrolib-splash-1.png" alt="">
  <p>International Library of Acrobatic Gymnastics</p>
</div>

<div>
  <p>AcroLib is a non-commercial project supposed to become a comprehensive online library of Acrobatic Gymnastics and floor-based partner acrobatics (hand to hand) in general. It is meant to become a place to promote new initiatives to bring the sports forward and an international “Hub”, where you can find all the necessary information, programmes and research in form of a simple website without any scripts and other clutter. The largest part of the library is the <a href="/terminology">Terminology</a> of Acrobatic Gymnastics (an ongoing work in progress to which you can contribute <a href="https://github.com/floshin/acrolib/edit/main/glossary.md">here</a>), where you’ll find all kinds of terms known from or associated with acrobatics in different languages (to be added), terms from hand-to-hand, floor acro, dance, as well as guidelines and principles for training and planning of Acro.</p> 
  
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
</div>

<style>
  h1 {
    font-size: 100px;
    text-align: center;
    padding-bottom: 0;
    padding-top: 0;
    margin: 25px 0 -20px;
  }

  main div:first-child p {
    text-align: center;
  }

    main div:nth-child(2) p {
      padding: 10px;
      margin-top: 50px;
      margin-bottom: 30px;
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

  @media (min-width: 1000px) {
  
    main {
      display: flex;
      max-width: initial;
      gap: 100px;
      justify-content: center;
    }
      main > div {
        width: 580px;
        margin: 50px 0;
      }
        main div:nth-child(2) p {
          margin-top: 110px;
        }
  }

</style>
