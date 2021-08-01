<template>
  <div id="app">
    <header id="header">
      <svg
        x="0"
        y="0"
        width="40"
        height="44"
        viewBox="0 0 28 32"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M22.1418 11.8165C24.0914 11.8165 26.0409 11.8165 27.9885 11.8165C25.7782 12.5191 25.5026 14.5178 24.9033 16.2207C23.2202 21.0168 21.6073 25.837 19.9537 30.6424C19.7577 31.21 19.4784 31.7499 19.2379 32.3027C19.0992 32.299 18.9605 32.2953 18.8218 32.2935C18.6276 31.8349 18.4093 31.3856 18.2428 30.916C16.7872 26.8335 15.3408 22.7492 13.8925 18.665C13.5023 17.5648 12.9992 16.5091 11.6508 16.4869C11.1403 16.4777 10.4467 16.7679 10.1655 17.1581C9.94728 17.4594 10.0564 18.3247 10.3431 18.6021C11.2809 19.5025 12.3666 20.2495 13.5836 21.2035C12.3351 24.7202 10.9942 28.5031 9.65134 32.2879C9.50337 32.2898 9.3554 32.2916 9.20743 32.2953C9.00952 31.8405 8.78571 31.3967 8.6174 30.9308C6.71598 25.6447 4.82382 20.3549 2.9261 15.0669C2.43595 13.6969 2.07713 12.2048 0 12.2695C0.0721353 12.1382 0.142421 12.0051 0.214556 11.8738C2.80958 11.8738 5.4046 11.8738 8.30481 11.8738C5.27883 13.0793 5.27513 13.0793 6.35531 16.1707C7.57236 19.6523 8.79681 23.1283 10.1674 27.0314C10.8832 25.0031 11.464 23.3575 12.0669 21.6528C11.5176 21.2793 11.0201 20.9817 10.5688 20.6248C9.23147 19.5672 8.38435 18.2711 8.72653 16.4666C8.98177 15.1205 9.91953 14.4475 11.1662 14.2441C13.0084 13.9428 14.5972 14.5159 15.6626 16.0764C16.1657 16.8142 16.4654 17.7035 16.7779 18.554C17.773 21.2609 18.733 23.9825 19.8502 27.0998C21.3743 22.5902 22.8207 18.456 24.1505 14.2867C24.5482 13.0442 24.2153 12.7983 22.1418 11.8165Z"
          class="logo"
        />
        <path
          d="M18.72 20.8689C18.6405 20.218 18.3908 19.5321 18.5147 18.9219C18.9586 16.7199 18.6368 15.6678 16.7354 14.4549C14.8414 13.2457 12.8678 12.1659 10.9609 10.9771C9.39979 10.0027 8.25857 8.68809 8.11615 6.7541C7.8498 3.14313 11.3104 0.369728 15.1577 1.1204C15.8883 1.26276 16.617 1.48649 17.3014 1.77677C18.3483 2.22051 19.2638 2.39986 20.0055 1.10006C20.0055 3.36685 20.0055 5.63365 20.0055 7.90044C19.9112 7.93187 19.8169 7.9633 19.7244 7.99474C19.6005 7.54914 19.4691 7.10355 19.3545 6.65611C18.6294 3.85682 16.4413 2.13731 13.7834 2.29632C12.3185 2.38322 11.1921 3.03589 10.6964 4.45218C10.197 5.87955 10.824 7.00741 12.0041 7.75438C14.1274 9.0967 16.3396 10.2985 18.4666 11.6371C21.0376 13.2568 22.0827 15.4385 21.2725 17.8255C20.8822 18.9756 20.0314 19.9703 19.3878 21.0334C19.1658 20.9798 18.942 20.9243 18.72 20.8689Z"
          class="logo"
        />
      </svg>
    </header>
    <main>
      <section id="splash">
        <div id="welcome">
          <span class="brackets">{</span>
          <div class="splashText">
            <p>Hello, I'm <span class="blueAcc">Shawn.</span></p>
            <p>I'm a <span class="orangeAcc">Full Stack</span> Developer.</p>
            <p>Based in <span class="blueAcc">Edmonton.</span></p>
          </div>
          <span class="brackets">}</span>
        </div>
        <button class="mainBtn">Get A Quote</button>
        <div id="socialsText">
          <hr class="socialsLineOne" />
          <div>Socials</div>
          <hr class="socialsLineTwo" />
        </div>
        <div id="socialsLogoContainer">
          <a href="https://twitter.com/GiveMeArrays" target="_blank">
            <img
              class="socialImage"
              src="../src/assets/twitter.svg"
              alt="Twitter Logo"
          /></a>
          <a
            href="https://www.linkedin.com/in/shawn-wood-8a037374/"
            target="_blank"
          >
            <img
              class="socialImage"
              src="../src/assets/linkedin.svg"
              alt="LinkedIn Logo"
          /></a>
          <a href="https://www.instagram.com/givemearrays/" target="_blank">
            <img
              class="socialImage"
              src="../src/assets/instagram.svg"
              alt="Instagram Logo"
          /></a>
        </div>
      </section>
      <section id="about">
        <h2 class="sectionHeading">About Me</h2>
        <p>
          I am a Full Stack Developer with a
          <span class="blueAcc">Passion</span> for creating an awesome
          <span class="orangeAcc">User Experience</span> through great visual
          design and functional back end systems.
        </p>
      </section>
      <section id="projects">
        <h2 class="sectionHeading">Projects</h2>
        <div v-for="project in projects" :key="project.id">
          <div class="projectCard">
            <img
              class="projectImage"
              :src="`${project.image}`"
              :alt="`Screenshot of ${project.link}`"
            />
            <div class="projectInfoContainer">
              <div class="projectTitle">
                <a :href="`${project.link}`"
                  ><h4>{{ project.name }}</h4></a
                >
                <a
                  class="codeLink"
                  :href="`${project.code_link}`"
                  target="_blank"
                  >View Code</a
                >
              </div>
              <div class="projectTech">{{ project.tech }}</div>
              <div class="projectDesc">{{ project.description }}</div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "App",

  data() {
    return {
      projects: [],
    };
  },

  created() {
    axios
      .request({
        url: `${process.env.VUE_APP_API_LINK}/projects`,
        method: "GET",
      })
      .then((res) => {
        this.projects = res.data.reverse();
      })
      .catch((err) => {
        console.log(err.response);
      });
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: $mainFont;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: $primary;
}

#header {
  background: $primary;
  display: grid;
  place-items: center;
  padding-top: 8px;
  .logo {
    fill: $secondary;
  }
}
.blueAcc {
  font-weight: bold;
  color: $secAcc;
}
.orangeAcc {
  font-weight: bold;
  color: $priAcc;
}
#splash {
  background: $primary;
  display: grid;
  gap: 20px;

  #welcome {
    font-size: 1.375rem;
    color: $secondary;
    display: grid;
    grid-template-columns: max-content 1fr max-content;
    place-items: center;
    padding: 20px;
    padding-bottom: 0;

    .brackets {
      font-size: 5.9rem;
      font-weight: bold;
      margin-bottom: 7px;
      color: $altAcc;
    }

    .splashText {
      line-height: 1.6;
    }
  }
  .mainBtn {
    background: $priAcc;
    border: 0;
    color: $secondary;
    font-weight: bold;
    font-size: 0.95rem;
    border-radius: 3px;
    margin: auto;
    padding: 10px 20px;
    box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.25);
  }
  #socialsText {
    display: grid;
    color: $smAcc;
    grid-template-columns: 1fr max-content 1fr;
    font-size: 0.95rem;

    .socialsLineOne {
      width: 22px;
      margin: auto 0;
      justify-self: end;
      margin-right: 5px;
      border: 1px solid $smAcc;
    }
    .socialsLineTwo {
      width: 22px;
      margin: auto 0;
      justify-self: start;
      margin-left: 5px;
      border: 1px solid $smAcc;
    }
  }
  #socialsLogoContainer {
    display: grid;
    grid-template-columns: repeat(3, max-content);
    place-self: center;
    gap: 20px;
    margin-bottom: 20px;
    .socialImage {
      max-height: 22px;
    }
  }
}

.sectionHeading {
  border-bottom: 3px solid $secAcc;
  place-self: center;
  padding-bottom: 12px;
  font-size: 1.5rem;
  letter-spacing: 0.1rem;
  margin-top: 14px;
}

#about {
  display: grid;
  color: $altAcc;
  margin-bottom: 18px;

  p {
    padding: 0 16px;
    padding-top: 12px;
    text-align: center;
    font-size: 1.125rem;
  }
}

#projects {
  display: grid;
  background: $primary;
  margin-bottom: 18px;
  .sectionHeading {
    color: $secondary;
    border-bottom: 3px solid $priAcc;
    margin-bottom: 18px;
  }

  .projectCard {
    padding: 0 20px;
    margin-bottom: 40px;
    display: grid;

    .projectImage {
      max-width: 100%;
    }
    .projectInfoContainer {
      padding: 4px 6px;
      background: $altAcc;
      border-radius: 0 0 4px 4px;
      box-shadow: 0px 2px 2px rgba(0, 0, 0, 0.25);
      display: grid;
      gap: 4px;
      .projectTitle {
        display: grid;
        grid-auto-flow: column;
        grid-auto-columns: max-content 1fr;

        a {
          text-decoration: none;
        }

        h4 {
          color: $priAcc;
        }

        .codeLink {
          color: $secondary;
          font-size: 0.8rem;
          place-self: center end;
          margin-left: 10px;
        }
      }

      .projectTech {
        color: $secAcc;
        font-size: 0.8rem;
      }
      .projectDesc {
        color: $secondary;
        font-size: 0.9rem;
      }
    }
  }
}
</style>
