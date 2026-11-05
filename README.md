<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GOD FLOW TV | Faith That Transforms Lives</title>

<meta name="description" content="GOD FLOW TV - Christian teachings, powerful prayers and messages of faith.">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  background: #07111f;
  color: #fff;
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

:root {
  --gold: #d9b66b;
  --dark: #07111f;
  --card: #122238;
  --muted: #aab5c4;
}

header {
  background: #091525;
  padding: 18px 6%;
  display: flex;
  align-items: center;
  justify-content: space-between;
  border-bottom: 1px solid #493c25;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  color: var(--gold);
  font-size: 23px;
  font-weight: 900;
  letter-spacing: 2px;
}

.logo small {
  display: block;
  font-size: 9px;
  color: white;
  letter-spacing: 3px;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 20px;
  font-size: 14px;
}

nav a:hover {
  color: var(--gold);
}

.button {
  display: inline-block;
  background: var(--gold);
  color: #101827;
  padding: 13px 22px;
  border-radius: 4px;
  text-decoration: none;
  font-weight: bold;
  margin: 8px 5px 0 0;
}

.button:hover {
  background: white;
}

.hero {
  min-height: 520px;
  padding: 110px 7%;
  background:
    radial-gradient(circle at 80% 30%, #59451f55, transparent 35%),
    linear-gradient(120deg, #07111f, #152942);
}

.eyebrow {
  color: var(--gold);
  letter-spacing: 4px;
  font-size: 12px;
  font-weight: bold;
}

.hero h1 {
  font-size: clamp(40px, 7vw, 75px);
  line-height: 1.1;
  max-width: 750px;
  margin: 20px 0;
}

.hero h1 span {
  color: var(--gold);
}

.hero p {
  color: var(--muted);
  max-width: 580px;
  font-size: 17px;
  margin-bottom: 20px;
}

section {
  padding: 75px 7%;
}

.section-title {
  font-size: 36px;
  margin: 10px 0 15px;
}

.description {
  color: var(--muted);
  max-width: 650px;
  margin-bottom: 30px;
}

.about {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 25px;
}

.about-box {
  background: var(--card);
  padding: 30px;
  border: 1px solid #493c25;
  border-radius: 7px;
}

.about-box p {
  color: var(--muted);
}

.about-box h3 {
  color: var(--gold);
  margin-bottom: 15px;
}

.verse {
  font-family: Georgia, serif;
  font-size: 23px;
  color: white;
}

.videos-section {
  background: #0b192a;
}

.video-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
}

.video-card {
  background: var(--card);
  border: 1px solid #24354b;
  border-radius: 7px;
  overflow: hidden;
  transition: .3s;
}

.video-card:hover {
  transform: translateY(-5px);
  border-color: var(--gold);
}

.video-card img {
  width: 100%;
  display: block;
  aspect-ratio: 16/9;
  object-fit: cover;
}

.video-info {
  padding: 17px;
}

.video-info h3 {
  font-size: 16px;
  margin-bottom: 12px;
}

.stats {
  color: var(--muted);
  font-size: 12px;
  display: flex;
  gap: 18px;
}

.stats b {
  color: var(--gold);
}

.watch {
  display: inline-block;
  color: var(--gold);
  margin-top: 12px;
  font-size: 13px;
  text-decoration: none;
}

.cta {
  text-align: center;
  background: linear-gradient(120deg, #152942, #091525);
}

.cta p {
  color: var(--muted);
  max-width: 600px;
  margin: 15px auto;
}

footer {
  padding: 35px 7%;
  background: #050c16;
  color: var(--muted);
  text-align: center;
  font-size: 13px;
}

footer strong {
  color: var(--gold);
  font-size: 20px;
  letter-spacing: 2px;
}

@media(max-width: 800px) {
  .video-grid {
    grid-template-columns: repeat(2, 1fr);
  }
  .about {
    grid-template-columns: 1fr;
  }
}

@media(max-width: 550px) {
  header {
    padding: 15px 5%;
  }
  nav {
    display: none;
  }
  .hero {
    padding: 85px 6%;
  }
  section {
    padding: 55px 6%;
  }
  .video-grid {
    grid-template-columns: 1fr;
  }
  .section-title {
    font-size: 29px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">
    GOD FLOW TV
    <small>FAITH THAT TRANSFORMS LIVES</small>
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#videos">Messages</a>
    <a href="#contact">Contact</a>
  </nav>

  <a class="button" href="https://www.youtube.com/@GODFLOWTV-p2n?sub_confirmation=1">
    SUBSCRIBE
  </a>
</header>

<!-- HOME -->
<div class="hero" id="home">
  <div class="eyebrow">WELCOME TO GOD FLOW TV</div>

  <h1>
    Faith That <span>Transforms</span> Lives.
  </h1>

  <p>
    Discover powerful Christian teachings, prayers,
    biblical encouragement and messages that strengthen
    your relationship with God.
  </p>

  <a class="button" href="#videos">WATCH MESSAGES</a>

  <a class="button" href="https://www.youtube.com/@GODFLOWTV-p2n?sub_confirmation=1">
    JOIN OUR CHANNEL
  </a>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="eyebrow">OUR PURPOSE</div>
  <h2 class="section-title">Growing Together In God.</h2>

  <div class="about">
    <div class="about-box">
      <h3>ABOUT GOD FLOW TV</h3>
      <p>
        GOD FLOW TV is dedicated to sharing faith-building
        messages, powerful prayers, Christian teachings
        and biblical encouragement.
        <br><br>
        Our desire is to inspire people to seek God,
        grow spiritually and live according to His Word.
      </p>
    </div>

    <div class="about-box">
      <h3>OUR FOUNDATION</h3>
      <div class="verse">
        "Faith comes by hearing, and hearing by the
        word of God."
      </div>
      <p style="margin-top:15px">Romans 10:17</p>
    </div>
  </div>
</section>

<!-- VIDEOS -->
<section class="videos-section" id="videos">
  <div class="eyebrow">WATCH AND BE INSPIRED</div>
  <h2 class="section-title">Featured Messages</h2>

  <p class="description">
    Watch our latest messages and teachings.
    Click any video to continue watching on YouTube.
  </p>

  <div class="video-grid" id="videoGrid"></div>

  <p id="statsMessage" style="color:#aab5c4;font-size:12px;margin-top:20px">
    Video views and likes will appear when YouTube API is connected.
  </p>
</section>

<!-- SUBSCRIBE -->
<section class="cta" id="contact">
  <div class="eyebrow">STAY CONNECTED</div>

  <h2 class="section-title">
    Keep Your Faith Alive.
  </h2>

  <p>
    Subscribe to GOD FLOW TV for more prayers,
    teachings and powerful messages.
    Share the Word and encourage someone today.
  </p>

  <a class="button" href="https://www.youtube.com/@GODFLOWTV-p2n?sub_confirmation=1">
    SUBSCRIBE ON YOUTUBE
  </a>

  <a class="button" href="https://www.youtube.com/@GODFLOWTV-p2n">
    VISIT OUR CHANNEL
  </a>
</section>

<footer>
  <strong>GOD FLOW TV</strong>
  <p>Faith That Transforms Lives.</p>
  <p>© <span id="year"></span> GOD FLOW TV. All Rights Reserved.</p>
</footer>

<script>
const videoIDs = [
  "s2aqnYKDYiQ",
  "fdUiemxVwqg",
  "w6i90MmNJu4",
  "EbgoMjIopYE",
  "T_VA8bnxZSY",
  "b1NsvJkG8wU"
];

// Add your YouTube API key here later.
const API_KEY = "";

const grid = document.getElementById("videoGrid");

document.getElementById("year").textContent =
  new Date().getFullYear();

function addVideo(id, title, views = "—", likes = "—") {
  const card = document.createElement("div");
  card.className = "video-card";

  const link = document.createElement("a");
  link.href = "https://www.youtube.com/watch?v=" + id;
  link.target = "_blank";
  link.rel = "noopener";

  const img = document.createElement("img");
  img.src = "https://i.ytimg.com/vi/" + id + "/hqdefault.jpg";
  img.alt = title;
  img.loading = "lazy";

  link.appendChild(img);

  const info = document.createElement("div");
  info.className = "video-info";

  const heading = document.createElement("h3");
  heading.textContent = title;

  const stats = document.createElement("div");
  stats.className = "stats";

  const view = document.createElement("span");
  view.textContent = "Views: " + views;

  const like = document.createElement("span");
  like.textContent = "Likes: " + likes;

  stats.append(view, like);

  const watch = document.createElement("a");
  watch.className = "watch";
  watch.href = link.href;
  watch.target = "_blank";
  watch.rel = "noopener";
  watch.textContent = "WATCH VIDEO →";

  info.append(heading, stats, watch);
  card.append(link, info);
  grid.appendChild(card);
}

// Display your six videos.
videoIDs.forEach((id, index) => {
  addVideo(id, "GOD FLOW TV Message " + (index + 1));
});

// Load real video titles, views and likes when API key is added.
async function loadYouTubeStats() {
  if (!API_KEY) return;

  try {
    const url =
      "https://www.googleapis.com/youtube/v3/videos" +
      "?part=snippet,statistics" +
      "&id=" + videoIDs.join(",") +
      "&key=" + encodeURIComponent(API_KEY);

    const response = await fetch(url);

    if (!response.ok) {
      throw new Error("API request failed");
    }

    const data = await response.json();
    const found = new Map(
      (data.items || []).map(video => [video.id, video])
    );

    grid.innerHTML = "";

    videoIDs.forEach((id, index) => {
      const video = found.get(id);

      if (!video) {
        addVideo(id, "GOD FLOW TV Message " + (index + 1));
        return;
      }

      const stats = video.statistics || {};

      addVideo(
        id,
        video.snippet.title,
        Number(stats.viewCount || 0).toLocaleString(),
        stats.likeCount
          ? Number(stats.likeCount).toLocaleString()
          : "Hidden"
      );
    });

    document.getElementById("statsMessage").textContent =
      "Video statistics loaded from YouTube.";
  } catch (error) {
    document.getElementById("statsMessage").textContent =
      "Could not load video statistics. Please check your API key.";
  }
}

loadYouTubeStats();
</script>

</body>
</html>
