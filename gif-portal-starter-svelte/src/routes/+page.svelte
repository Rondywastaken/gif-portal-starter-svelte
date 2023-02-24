<script lang="ts">
  import twitterLogo from "../assets/twitter-logo.svg";

  const TWITTER_HANDLE = '_buildspace';
  const TWITTER_LINK = `https://twitter.com/${TWITTER_HANDLE}`;
</script>

<div class="App">
    <div class="container">
      <div class="header-container">
        <p class="header">🖼 GIF Portal</p>
        <p class="sub-text">
          View your GIF collection in the metaverse ✨
        </p>
      </div>
      <div class="footer-container">
        <img alt="Twitter Logo" class="twitter-logo" src={twitterLogo} />
        <a
          class="footer-text"
          href={TWITTER_LINK}
          target="_blank"
          rel="noreferrer"
        >{`built on @${TWITTER_HANDLE}`}</a>
      </div>
    </div>
  </div>