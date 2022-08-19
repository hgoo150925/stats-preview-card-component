<div class="container">
  <div class="container__card">
    <h1>Get <span>insights</span> that help your business grow.</h1>
    <p>
      Discover the benefits of data analytics and make better decisions
      regarding revenue, customer experience, and overall efficiency.
    </p>
    <div class="container__flex">
      <div>
        <ul>
          <li class="inter">10k+</li>
          <li class="lexer">companies</li>
        </ul>
      </div>

      <div>
        <ul>
          <li class="inter">314</li>
          <li class="lexer">templates</li>
        </ul>
      </div>

      <div>
        <ul>
          <li class="inter">12m+</li>
          <li class="lexer">queries</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<style>
  .container {
    background-color: hsl(244, 38%, 16%);
    background-image: url('https://dimmageiras.github.io/frontend-mentor-stats-preview-card-component/images/image-header-desktop.jpg');
    background-position: right;
    background-repeat: no-repeat;
    background-size: 50%;
    border-radius: 0.5rem;
    width: 111.2rem;
    height: 45.4rem;
    margin: 17.8rem auto;
  }

  span {
    color: hsl(277, 64%, 61%);
  }
  .container__card {
    display: flex;
    flex-direction: column;
    color: #fff;
    padding: 7.4rem;
    width: 55.5rem;
  }
  ul li {
    list-style: none;
  }
  .container__flex {
    display: flex;
    justify-content: space-between;
    margin: 7.4rem 0 0 0;
  }
  .inter {
    font-family: 'Inter', sans-serif;
    font-size: 2.4rem;
    font-weight: 700;
  }
  .lexer {
    color: hsla(0, 0%, 100%, 0.75);
    font-family: 'Lexend Deca', sans-serif;
    font-size: 1.3rem;
    text-transform: uppercase;
    letter-spacing: 0.2rem;
  }
</style>
