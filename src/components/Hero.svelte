<style>
  .Hero {
    margin: 2em 0 0 0;
    min-height: 400px;
  }
  .Hero-content {
    display: flex;
    justify-content: space-between;
  }
  .Hero-project h2 {
    font-size: 28px;
    font-weight: bold;
    margin: 0 0 1em 0;
  }
  .Hero-project span {
    font-size: 16px;
    font-weight: 300;
    padding: 0.3em 1.5em;
    background-color: rgba(255, 255, 255, 0.2);
    border: 1px solid rgba(255, 255, 255, 0.6);
    border-radius: 30px;
    margin: 0 0 0 1em;
  }
  .Hero-stats p {
    font-size: 18px;
    font-weight: bold;
  }
  .Hero-stats span {
    font-size: 38px;
    display: block;
    text-align: right;
  }
  .Hero-project ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
  }
  .Hero-project li {
    display: inline-block;
    margin: 0 0.4em 0 0;
    font-size: 16px;
    font-weight: 300;
    padding: 0.3em 1em;
    background-color: rgba(255, 255, 255, 0.2);
    border-radius: 30px;
    color: rgba(255, 255, 255, 0.6);
    cursor: pointer;
  }
  .Hero-project li:hover {
    background-color: rgba(255, 255, 255, 0.4);
    color: white;
  }
</style>

<div class="Hero">
  <div class="Hero-container">
    <div class="Hero-content">
      <div class="Hero-project">
        <h2>
          Firebase Demo Project
          <span>Plan Blaze</span>
        </h2>
        <ul>
          <li>2 Applicaciones</li>
          <li>Flood-it Android</li>
          <li>Flood-it iOS</li>
        </ul>
      </div>
      <div class="Hero-stats">
        <p>
          Número de usuarios:
          <span>72</span>
        </p>
      </div>
    </div>
  </div>
</div>
