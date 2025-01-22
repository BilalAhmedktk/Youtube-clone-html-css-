<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles/general.css" />
    <link rel="stylesheet" href="styles/video.css" />
    <link rel="stylesheet" href="styles/header.css" />
    <link rel="stylesheet" href="styles/sidebar.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <title>youtube</title>
  </head>
  <body>
    <nav></nav>
    <header class="header">
      <div class="left-section">
        <img
          class="hamburger-menu"
          src="exercises/icons/hamburger-menu.svg"
          alt=""
        />
        <img class="youtube-logo" src="exercises/icons/youtube-logo.svg" />
      </div>
      <div class="middle-section">
        <input class="search-bar" type="text" placeholder="search" />
        <button class="search-button">
          <img class="search-icon" src="exercises/icons/search.svg" />
          <div class="tooltip">Search</div>
        </button>
        <button class="voice-search-button">
          <img
            class="voice-search-icon"
            src="exercises/icons/voice-search-icon.svg"
          />
          <div class="tooltip">Search with your voice</div>
        </button>
      </div>
      <div class="right-section">
        <div class="upload-icon-container">
          <img class="upload-icon" src="exercises/icons/upload.svg" />
          <div class="tooltip">Create</div>
        </div>
        <div class="youtube-apps-icon-container">
          <img
            class="youtube-apps-icon"
            src="exercises/icons/youtube-apps.svg"
          />
          <div class="tooltip">YouTube-apps</div>
        </div>
        <div class="notifications-icon-container">
          <div class="notifications-icon-container-1">
            <img
              class="notifications-icon"
              src="exercises/icons/notifications.svg"
            />
            <div class="tooltip">Notifications</div>
          </div>

          <div class="notifications-count">3</div>
        </div>

        <img class="bilal" src="exercises/channel-pictures/bilal.jpg" />
      </div>
    </header>
    <nav class="Sidebar">
      <div class="sidebar-link">
        <img src="exercises/icons/home.svg" />
        <div>Home</div>
      </div>
      <div class="sidebar-link">
        <img src="exercises/icons/explore.svg" />
        <div>Explore</div>
      </div>
      <div class="sidebar-link">
        <img src="exercises/icons/subscriptions.svg" />
        <div>Subscriptions</div>
      </div>
      <div class="sidebar-link">
        <img src="exercises/icons/originals.svg" />
        <div>Originals</div>
      </div>
      <div class="sidebar-link">
        <img src="exercises/icons/youtube-music.svg" />
        <div>Youtube-music</div>
      </div>
      <div class="sidebar-link">
        <img src="exercises/icons/library.svg" />
        <div>Library</div>
      </div>
    </nav>
    <main>
      <section class="video-grid">
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=n2RNcPRtAiY"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-1.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">14:20</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a href="https://www.youtube.com/c/mkbhd">
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-1.jpeg"
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-1.jpeg"
                  />
                  <div>
                    <div class="channel-tooltip-name">Marques Brownlee</div>
                    <div class="channel-tooltip-stats">15M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=n2RNcPRtAiY"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">
                  Talking Tech and AI with Google CEO Sundar Pichai!
                </p>
              </a>

              <p class="video-author">Marques Brownlee</p>
              <p class="video-stats">4M views &#183; 6 months ago</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=mP0RAo9SKZk"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-2.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">8:22</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a href="https://www.youtube.com/c/markiplier">
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-2.jpeg"
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-2.jpeg"
                  />
                  <div>
                    <div class="channel-tooltip-name">Markiplier</div>
                    <div class="channel-tooltip-stats">30M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=mP0RAo9SKZk"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">Try Not To Laugh Challenge #9</p>
              </a>
              <p class="video-author">Markiplier</p>
              <p class="video-stats">19M views · 4 years ago</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=FgjPQQeTh1w"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-3.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">9:13</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a href="https://www.youtube.com/user/SSSniperWolf">
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-3.jpeg"
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-3.jpeg"
                  />
                  <div>
                    <div class="channel-tooltip-name">SSSniperWolf</div>
                    <div class="channel-tooltip-stats">31M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=FgjPQQeTh1w"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">
                  Crazy Tik Toks Taken Moments Before DISASTER
                </p>
              </a>

              <p class="video-author">SSSniperWolf</p>
              <p class="video-stats">12M views &#183; 1 year ago</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=094y1Z2wpJg"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-4.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">22:09</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a href="https://www.youtube.com/c/veritasium">
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-4.jpeg"
                    alt=""
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-4.jpeg"
                    alt=""
                  />
                  <div>
                    <div class="channel-tooltip-name">veritasium</div>
                    <div class="channel-tooltip-stats">11.5M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=094y1Z2wpJg"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">
                  The Simplest Math Problem No One Can Solve - Collatz
                  Conjecture
                </p>
              </a>

              <p class="video-author">Veritasium</p>
              <p class="video-stats">18M views &#183; 4 months ago</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=86CQq3pKSUw"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-5.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">11:17</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a href="https://www.youtube.com/c/CSDojo">
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-5.jpeg"
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-5.jpeg"
                  />
                  <div>
                    <div class="channel-tooltip-name">CS Dojo</div>
                    <div class="channel-tooltip-stats">1.79M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=86CQq3pKSUw"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">
                  Kadane's Algorithm to Maximum Sum Subarray Problem
                </p>
              </a>

              <p class="video-author">CS Dojo</p>
              <p class="video-stats">519K views &#183; 5 years ago</p>
            </div>
          </div>
        </div>
        <div class="video-preview">
          <div class="thumbnail-row">
            <a
              href="https://www.youtube.com/watch?v=yXWw0_UfSFg"
              target="_blank"
              class="video-title-link"
            >
              <img
                class="image-youtube"
                src="exercises/channel-pictures/thumbnail-6.webp"
                alt="thumbnail"
              />
            </a>

            <div class="video-time">19:59</div>
          </div>
          <div class="video-info-grid">
            <div class="channel-picture">
              <div class="profile-picture-container">
                <a
                  href="https://www.youtube.com/channel/UCX6OQ3DkcsbYNE6H8uQQuVA"
                >
                  <img
                    class="profile-picture"
                    src="exercises/channel-pictures/channel-6.jpeg"
                    alt=""
                  />
                </a>
                <div class="channel-tooltip">
                  <img
                    class="channel-tooltip-picture"
                    src="exercises/channel-pictures/channel-6.jpeg"
                    alt=""
                  />
                  <div>
                    <div class="channel-tooltip-name">MrBeast</div>
                    <div class="channel-tooltip-stats">90.6M subscribers</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="video-info">
              <a
                href="https://www.youtube.com/watch?v=yXWw0_UfSFg"
                target="_blank"
                class="video-title-link"
              >
                <p class="video-title">
                  Anything You Can Fit In The Circle I’ll Pay For
                </p>
              </a>

              <p class="video-author">MrBeast</p>
              <p class="video-stats">141M views &#183; 1 year ago</p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </body>
</html>
