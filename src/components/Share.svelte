<style>
  .Share {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    background-color: white;
    margin: 0 0 2em 0;
    width: 300px;
    height: 80px;
    position: absolute;
    top: 300px;
    left: 30%;
    z-index: 9;
    padding: 1em;
  }
  .Share-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  .Share-head h2 {
    font-size: 16px;
  }
  .Share-head button {
    cursor: pointer;
  }
  .Share-content span {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: black;
    font-size: 14px;
    margin: 2em 0 0 0;
  }
  .Share-content a {
    color: #3b5998;
    margin: 0 0.5em 0 0;
    font-size: 20px;
  }
</style>

<div class="Share">
  <div class="Share-head">
    <h2>Compartir</h2>
    <button on:click>
      X
    </button>
  </div>
  <div class="Share-content">
    <a
      href="https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co"
      target="_blank">
      <span>
      Compartir en Facebook 🌝
      </span>
    </a>
  </div>
</div>
