# Github
Bages

<p align="center">
  <a href="https://wayhomelive.vercel.app/">
    <img
      src="https://img.shields.io/badge/🌐%20EXPLORE%20LIVE%20WEBSITE-2563EB?style=for-the-badge&labelColor=0F172A"
      alt="Explore Website"
    />
  </a>
</p>

<p align="center">
  <a href="https://wayhomelive.vercel.app/">
    <img
      src="https://img.shields.io/badge/🏠%20Explore%20WayHome-2563EB?style=for-the-badge&logoColor=white"
      alt="Explore WayHome"
    />
  </a>
</p>

<a href="https://wayhomelive.vercel.app/" class="live-link">
  <span>Live Website</span>
  <span class="arrow">→</span>
  <span class="animated-line"></span>
</a>
.live-link {
  position: relative;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  padding-bottom: 8px;

  color: #2563eb;
  text-decoration: none;
  font-size: 16px;
  font-weight: 500;

  overflow: hidden;
}

.live-link .arrow {
  font-size: 24px;
  line-height: 1;
  transition: transform 0.3s ease;
}

.live-link:hover .arrow {
  transform: translateX(5px);
}

/* Animated blue line */
.animated-line {
  position: absolute;
  bottom: 0;
  left: -100%;
  width: 100%;
  height: 2px;
  background: #2563eb;

  animation: lineMove 2s ease-in-out infinite;
}

@keyframes lineMove {
  0% {
    left: -100%;
  }

  50% {
    left: 0;
  }

  100% {
    left: 100%;
  }
}
