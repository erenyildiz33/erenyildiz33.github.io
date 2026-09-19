---
# Leave the homepage title empty to use the site title
title: 'Eren Yildiz - Georgia Tech'
date: 2022-10-24
type: landing
favicon: 
  logo: "media/icon/icon.png"

design:
  # Default section spacing
  spacing: '0'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume1.pdf
      headings:
        about: 'About Me'
        education: ''
        interests: Research Interests
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      spacing:
        padding: ["0", "0", "0", "0"]
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text:
        My research focuses on <b>enabling sustainable, ultra–low‐power computing platforms</b>  that operate reliably under <b>intermittent power conditions</b>  by leveraging ambient energy sources such as RF, solar, and vibration. I have developed novel timekeeping architectures, energy‐aware runtime systems, and resilient hardware/software co‐designs for the deployment of <b>self‐powered IoT devices</b> . With more than 10 peer‐reviewed publications, including in top‐tier venues such as   <b>OSDI, EuroSys, SenSys, MobiSys</b> and <b>EWSN</b>, my work advances energy‐efficient sensing technologies for applications in smart infrastructure, healthcare monitoring, and environmental systems. These contributions were recently recognized with the <b>EWSN 2025</b> and <b>MobiSys 2026 Rising Star</b>, highlighting the impact of my work on sustainable mobile and embedded systems.

    design:
      columns: '1'
      spacing:
        padding: [2rem, 0, 0, 0]
      css_class: "full-width-text"
  - block: markdown
    id: news
    content:
      title: Recent News
      text: |-
        <div class="recent-news-list" role="region" aria-label="Recent news updates">
          <ul class="recent-news-items">
            <li><strong class="recent-news-date">[Sep 2026]</strong> Our paper entitled <em>“<a href="https://arxiv.org/pdf/2607.23000">Magnetic Tunnel Junctions for Timekeeping in Intermittent Computing Systems</a>”</em> has been accepted to appear in <strong>ACM SenSys 2027</strong>.</li>
            <li><strong class="recent-news-date">[May 2026]</strong> Invited to serve on the TPC of <a href="https://sensys.acm.org/2027/tpc_committee.html"><strong>SenSys 2027</strong></a>.</li>
            <li><strong class="recent-news-date">[May 2026]</strong> Selected as a <strong>MobiSys Rising Star 2026</strong> and honored to participate in the <a href="https://www.sigmobile.org/mobisys/2026/rising_stars_program/"><strong>MobiSys 2026 Rising Stars Forum</strong></a> with a talk titled <em>“System Support for Reliable Edge Computing under Intermittent Energy.”</em></li>
            <li><strong class="recent-news-date">[Feb 2026]</strong> Our paper entitled <em>“<a href="https://dl.acm.org/doi/pdf/10.1145/3745756.3809207">BIONIC: A Co-Designed Hardware and Runtime for Time-Sensitive Battery-Free IoT</a>”</em> has been accepted to appear in <strong>ACM MobiSys 2026</strong>.</li>
            <li><strong class="recent-news-date">[Feb 2026]</strong> Our paper entitled <em>“<a href="https://dl.acm.org/doi/pdf/10.1145/3745756.3809201">A Greener Edge: A Framework on Carbon-aware Edge ML System Design</a>”</em> has been accepted to appear in <strong>ACM MobiSys 2026</strong>.</li>
            <li><strong class="recent-news-date">[Jan 2026]</strong> Invited to serve on the TPC of <a href="https://www.enssys.org/2026/tpc.php"><strong>ENSsys 2026</strong></a>.</li>
            <li><strong class="recent-news-date">[Sep 2025]</strong> Our paper entitled <em>“CapDYN: Adaptive Self-Scaling Energy Storage for Powering Batteryless IoT”</em> has been published in <strong>ACM Transactions on Embedded Computing Systems (TECS)</strong>.</li>
            <li><strong class="recent-news-date">[Sep 2025]</strong> I am honored to participate in the <a href="https://www.ewsn25.cs.kuleuven.be/rising-stars-forum"><strong>EWSN 2025 Rising Stars Forum</strong></a>.</li>
            <li><strong class="recent-news-date">[Feb 2025]</strong> Started as a Postdoctoral Researcher in the <a href="https://kamoamoa.com"><strong>Ka Moamoa Lab</strong></a> at the Georgia Institute of Technology.</li>
            <li><strong class="recent-news-date">[Sep 2024]</strong> Our paper entitled <em>“Fast-Inf: Ultra-Fast Embedded Intelligence on the Batteryless Edge”</em> has been accepted to appear in <strong>ACM SenSys</strong>.</li>
            <li><strong class="recent-news-date">[Jul 2024]</strong> I visited <strong>the University of Trento</strong> through the Erasmus+ programme for a research exchange.</li>
            <li><strong class="recent-news-date">[Feb 2024]</strong> Our paper entitled <em>“Adaptable Runtime Monitoring for Intermittent Systems”</em> has been accepted to appear in <strong>ACM EuroSys 2024</strong>.</li>
            <li><strong class="recent-news-date">[Jun 2023]</strong> I completed my Ph.D. in <strong>Computer Engineering</strong> at <strong>Ege University</strong>, marking the culmination of my doctoral research on energy-efficient and battery-free computing systems.</li>
            <li><strong class="recent-news-date">[Jan 2023]</strong> Our paper entitled <em>“Efficient and Safe I/O Operations for Intermittent Systems”</em> has been accepted to appear in <strong>ACM EuroSys 2023</strong>.</li>
            <li><strong class="recent-news-date">[Mar 2022]</strong> Our paper entitled <em>“Immortal Threads: Multithreaded Event-driven Intermittent Computing on Ultra-Low-Power Microcontrollers”</em> has been accepted to appear in <strong>USENIX OSDI 2022</strong>.</li>
            <li><strong class="recent-news-date">[Dec 2021]</strong> I joined <strong>Northwestern University</strong> as a Visiting Researcher for a one-year research appointment.</li>
            <li><strong class="recent-news-date">[Mar 2020]</strong> I was awarded the <strong>2214-A International Research Fellowship Programme for PhD Students</strong> by TÜBİTAK.</li>
          </ul>
        </div>
        <p class="recent-news-hint">Showing the latest items by default. Scroll to view earlier updates.</p>
    design:
      columns: '1'
      spacing:
        padding: [2rem, 0, 0, 0]
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: admin
  - block: markdown
    id: service
    content:
      title: Service Record
      text: |-
        <div class="service-record">
          <div class="service-record-category">
            <h3>Conference &amp; Workshop TPCs</h3>
            <ul>
              <li>ACM Conference on Embedded Networked Sensor Systems (<a href="https://sensys.acm.org/2027/tpc_committee.html">SenSys 2027</a>)</li>
              <li>14th International Workshop on Energy Harvesting &amp; Energy-Neutral Sensing Systems (<a href="https://www.enssys.org/2026/tpc.php">ENSsys 2026</a>)</li>
            </ul>
          </div>
          <div class="service-record-category">
            <h3>Journal Reviews</h3>
            <ul>
              <li>ACM Transactions on Interactive, Mobile, Wearable and Ubiquitous Technologies</li>
              <li>IEEE Internet of Things Journal</li>
              <li>Future Generation Computer Systems</li>
              <li>IEEE Transactions on Very Large Scale Integration Systems</li>
              <li>IEEE Transactions on Sustainable Computing</li>
              <li>IEEE Transactions on Mobile Computing</li>
              <li>IEEE Open Journal of the Communications Society</li>
            </ul>
          </div>
          <div class="service-record-category">
            <h3>External Reviewer</h3>
            <ul>
              <li>ACM SIGBED International Conference on Embedded Software (EMSOFT)</li>
              <li>ACM SIGCAS/SIGCHI Conference on Computing and Sustainable Societies (COMPASS 2026)</li>
            </ul>
          </div>
          <div class="service-record-category">
            <h3>Other</h3>
            <ul>
              <li>Session Chair, Rising Stars Forum, ACM <a href="https://www.sigmobile.org/mobisys/2026/rising_stars_program/">MobiSys 2026</a></li>
            </ul>
          </div>
        </div>
    design:
      columns: '1'
      spacing:
        padding: [2rem, 0, 0, 0]
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
