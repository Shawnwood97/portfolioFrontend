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
        <div id="welcome" class="wrapper">
          <span class="brackets">{</span>
          <div class="splashText">
            <p>Hello, I'm <span class="blueAcc">Shawn.</span></p>
            <p>I'm a <span class="orangeAcc">Full Stack</span> Developer.</p>
            <p>Based in <span class="blueAcc">Edmonton.</span></p>
          </div>
          <span class="brackets">}</span>
        </div>
        <a href="#quote" class="mainBtn">Get A Quote</a>
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
        <div class="wrapper">
          <h2 class="sectionHeading">About Me</h2>
          <p>
            I am a Full Stack Developer with a
            <span class="blueAcc">Passion</span> for creating an awesome
            <span class="orangeAcc">User Experience</span> through great visual
            design and functional back end systems.
          </p>
        </div>
      </section>
      <section id="projects">
        <div class="wrapper">
          <div class="sectionHeading">Projects</div>
          <div id="projectsContainer">
            <div v-for="project in limitedProjects" :key="project.id">
              <div class="projectCard">
                <img
                  class="projectImage"
                  :src="`${project.image}`"
                  :alt="`Screenshot of ${project.link}`"
                />
                <div class="projectInfoContainer">
                  <div class="projectTitle">
                    <a :href="`${project.link}`" target="_blank"
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
          </div>
          <!-- //todo make this solution nicer later -->
          <div v-if="showProj === 3" @click="showProj = null" class="mainBtn">
            Show More
          </div>
          <div v-if="showProj === null" @click="showProj = 3" class="mainBtn">
            Show Less
          </div>
        </div>
      </section>
      <section id="skills">
        <h2 class="sectionHeading">Skills</h2>
        <h3 class="skillsHeading">Front End</h3>
        <div class="skillMainGrid">
          <div v-for="skill in frontend" :key="skill.id">
            <div class="skillSecGrid">
              <img
                class="skillLogo"
                :src="`${skill.logo}`"
                :alt="`${skill.name} Logo`"
              />
              <span class="skillText">{{ skill.name }}</span>
            </div>
          </div>
        </div>
        <h3 class="skillsHeading">Back End</h3>
        <div class="skillMainGrid">
          <div v-for="skill in backend" :key="skill.id">
            <div class="skillSecGrid">
              <img
                class="skillLogo"
                :src="`${skill.logo}`"
                :alt="`${skill.name} Logo`"
              />
              <span class="skillText">{{ skill.name }}</span>
            </div>
          </div>
        </div>
        <h3 class="skillsHeading">Tools</h3>
        <div class="skillMainGrid">
          <div v-for="skill in tools" :key="skill.id">
            <div class="skillSecGrid">
              <img
                class="skillLogo"
                :src="`${skill.logo}`"
                :alt="`${skill.name} Logo`"
              />
              <span class="skillText">{{ skill.name }}</span>
            </div>
          </div>
        </div>
      </section>
      <section id="contact">
        <h2 class="sectionHeading">Contact Me</h2>
        <div class="contactMainGrid">
          <div class="contactSecGrid">
            <a
              href="https://www.linkedin.com/in/shawn-wood-8a037374/"
              target="_blank"
            >
              <svg
                class="contactSocialImage"
                width="40px"
                height="40px"
                viewBox="0 0 256 256"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                preserveAspectRatio="xMidYMid"
              >
                <g>
                  <path
                    d="M218.123122,218.127392 L180.191928,218.127392 L180.191928,158.724263 C180.191928,144.559023 179.939053,126.323993 160.463756,126.323993 C140.707926,126.323993 137.685284,141.757585 137.685284,157.692986 L137.685284,218.123441 L99.7540894,218.123441 L99.7540894,95.9665207 L136.168036,95.9665207 L136.168036,112.660562 L136.677736,112.660562 C144.102746,99.9650027 157.908637,92.3824528 172.605689,92.9280076 C211.050535,92.9280076 218.138927,118.216023 218.138927,151.114151 L218.123122,218.127392 Z M56.9550587,79.2685282 C44.7981969,79.2707099 34.9413443,69.4171797 34.9391618,57.260052 C34.93698,45.1029244 44.7902948,35.2458562 56.9471566,35.2436736 C69.1040185,35.2414916 78.9608713,45.0950217 78.963054,57.2521493 C78.9641017,63.090208 76.6459976,68.6895714 72.5186979,72.8184433 C68.3913982,76.9473153 62.7929898,79.26748 56.9550587,79.2685282 M75.9206558,218.127392 L37.94995,218.127392 L37.94995,95.9665207 L75.9206558,95.9665207 L75.9206558,218.127392 Z M237.033403,0.0182577091 L18.8895249,0.0182577091 C8.57959469,-0.0980923971 0.124827038,8.16056231 -0.001,18.4706066 L-0.001,237.524091 C0.120519052,247.839103 8.57460631,256.105934 18.8895249,255.9977 L237.033403,255.9977 C247.368728,256.125818 255.855922,247.859464 255.999,237.524091 L255.999,18.4548016 C255.851624,8.12438979 247.363742,-0.133792868 237.033403,0.000790807055"
                    fill="#0E76A8"
                  ></path>
                </g></svg
            ></a>
            <div class="contactText">LinkedIn</div>
          </div>
          <div class="contactSecGrid">
            <a href="https://twitter.com/GiveMeArrays" target="_blank">
              <svg
                class="contactSocialImage"
                width="49px"
                height="40px"
                viewBox="0 0 256 209"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                preserveAspectRatio="xMidYMid"
              >
                <g>
                  <path
                    d="M256,25.4500259 C246.580841,29.6272672 236.458451,32.4504868 225.834156,33.7202333 C236.678503,27.2198053 245.00583,16.9269929 248.927437,4.66307685 C238.779765,10.6812633 227.539325,15.0523376 215.57599,17.408298 C205.994835,7.2006971 192.34506,0.822 177.239197,0.822 C148.232605,0.822 124.716076,24.3375931 124.716076,53.3423116 C124.716076,57.4586875 125.181462,61.4673784 126.076652,65.3112644 C82.4258385,63.1210453 43.7257252,42.211429 17.821398,10.4359288 C13.3005011,18.1929938 10.710443,27.2151234 10.710443,36.8402889 C10.710443,55.061526 19.9835254,71.1374907 34.0762135,80.5557137 C25.4660961,80.2832239 17.3681846,77.9207088 10.2862577,73.9869292 C10.2825122,74.2060448 10.2825122,74.4260967 10.2825122,74.647085 C10.2825122,100.094453 28.3867003,121.322443 52.413563,126.14673 C48.0059695,127.347184 43.3661509,127.988612 38.5755734,127.988612 C35.1914554,127.988612 31.9009766,127.659938 28.694773,127.046602 C35.3777973,147.913145 54.7742053,163.097665 77.7569918,163.52185 C59.7820257,177.607983 37.1354036,186.004604 12.5289147,186.004604 C8.28987161,186.004604 4.10888474,185.75646 0,185.271409 C23.2431033,200.173139 50.8507261,208.867532 80.5109185,208.867532 C177.116529,208.867532 229.943977,128.836982 229.943977,59.4326002 C229.943977,57.1552968 229.893412,54.8901664 229.792282,52.6381454 C240.053257,45.2331635 248.958338,35.9825545 256,25.4500259"
                    fill="#00ACEE"
                  ></path>
                </g></svg
            ></a>
            <div class="contactText">Twitter</div>
          </div>
          <div class="contactSecGrid">
            <a href="https://www.instagram.com/givemearrays/" target="_blank">
              <svg
                class="contactSocialImage"
                width="40px"
                height="40px"
                viewBox="0 0 256 256"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                preserveAspectRatio="xMidYMid"
              >
                <g>
                  <path
                    d="M127.999746,23.06353 C162.177385,23.06353 166.225393,23.1936027 179.722476,23.8094161 C192.20235,24.3789926 198.979853,26.4642218 203.490736,28.2166477 C209.464938,30.5386501 213.729395,33.3128586 218.208268,37.7917319 C222.687141,42.2706052 225.46135,46.5350617 227.782844,52.5092638 C229.535778,57.0201472 231.621007,63.7976504 232.190584,76.277016 C232.806397,89.7746075 232.93647,93.8226147 232.93647,128.000254 C232.93647,162.177893 232.806397,166.225901 232.190584,179.722984 C231.621007,192.202858 229.535778,198.980361 227.782844,203.491244 C225.46135,209.465446 222.687141,213.729903 218.208268,218.208776 C213.729395,222.687649 209.464938,225.461858 203.490736,227.783352 C198.979853,229.536286 192.20235,231.621516 179.722476,232.191092 C166.227425,232.806905 162.179418,232.936978 127.999746,232.936978 C93.8200742,232.936978 89.772067,232.806905 76.277016,232.191092 C63.7971424,231.621516 57.0196391,229.536286 52.5092638,227.783352 C46.5345536,225.461858 42.2700971,222.687649 37.7912238,218.208776 C33.3123505,213.729903 30.538142,209.465446 28.2166477,203.491244 C26.4637138,198.980361 24.3784845,192.202858 23.808908,179.723492 C23.1930946,166.225901 23.0630219,162.177893 23.0630219,128.000254 C23.0630219,93.8226147 23.1930946,89.7746075 23.808908,76.2775241 C24.3784845,63.7976504 26.4637138,57.0201472 28.2166477,52.5092638 C30.538142,46.5350617 33.3123505,42.2706052 37.7912238,37.7917319 C42.2700971,33.3128586 46.5345536,30.5386501 52.5092638,28.2166477 C57.0196391,26.4642218 63.7971424,24.3789926 76.2765079,23.8094161 C89.7740994,23.1936027 93.8221066,23.06353 127.999746,23.06353 M127.999746,0 C93.2367791,0 88.8783247,0.147348072 75.2257637,0.770274749 C61.601148,1.39218523 52.2968794,3.55566141 44.1546281,6.72008828 C35.7374966,9.99121548 28.5992446,14.3679613 21.4833489,21.483857 C14.3674532,28.5997527 9.99070739,35.7380046 6.71958019,44.1551362 C3.55515331,52.2973875 1.39167714,61.6016561 0.769766653,75.2262718 C0.146839975,88.8783247 0,93.2372872 0,128.000254 C0,162.763221 0.146839975,167.122183 0.769766653,180.774236 C1.39167714,194.398852 3.55515331,203.703121 6.71958019,211.845372 C9.99070739,220.261995 14.3674532,227.400755 21.4833489,234.516651 C28.5992446,241.632547 35.7374966,246.009293 44.1546281,249.28042 C52.2968794,252.444847 61.601148,254.608323 75.2257637,255.230233 C88.8783247,255.85316 93.2367791,256 127.999746,256 C162.762713,256 167.121675,255.85316 180.773728,255.230233 C194.398344,254.608323 203.702613,252.444847 211.844864,249.28042 C220.261995,246.009293 227.400247,241.632547 234.516143,234.516651 C241.632039,227.400755 246.008785,220.262503 249.279912,211.845372 C252.444339,203.703121 254.607815,194.398852 255.229725,180.774236 C255.852652,167.122183 256,162.763221 256,128.000254 C256,93.2372872 255.852652,88.8783247 255.229725,75.2262718 C254.607815,61.6016561 252.444339,52.2973875 249.279912,44.1551362 C246.008785,35.7380046 241.632039,28.5997527 234.516143,21.483857 C227.400247,14.3679613 220.261995,9.99121548 211.844864,6.72008828 C203.702613,3.55566141 194.398344,1.39218523 180.773728,0.770274749 C167.121675,0.147348072 162.762713,0 127.999746,0 Z M127.999746,62.2703115 C91.698262,62.2703115 62.2698034,91.69877 62.2698034,128.000254 C62.2698034,164.301738 91.698262,193.730197 127.999746,193.730197 C164.30123,193.730197 193.729689,164.301738 193.729689,128.000254 C193.729689,91.69877 164.30123,62.2703115 127.999746,62.2703115 Z M127.999746,170.667175 C104.435741,170.667175 85.3328252,151.564259 85.3328252,128.000254 C85.3328252,104.436249 104.435741,85.3333333 127.999746,85.3333333 C151.563751,85.3333333 170.666667,104.436249 170.666667,128.000254 C170.666667,151.564259 151.563751,170.667175 127.999746,170.667175 Z M211.686338,59.6734287 C211.686338,68.1566129 204.809755,75.0337031 196.326571,75.0337031 C187.843387,75.0337031 180.966297,68.1566129 180.966297,59.6734287 C180.966297,51.1902445 187.843387,44.3136624 196.326571,44.3136624 C204.809755,44.3136624 211.686338,51.1902445 211.686338,59.6734287 Z"
                    fill="#CD486B"
                  ></path>
                </g></svg
            ></a>
            <div class="contactText">Instagram</div>
          </div>
          <div class="contactSecGrid">
            <a href="#" target="_blank">
              <svg
                height="40px"
                width="40px"
                class="contactSocialImage"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 512 512"
              >
                <path
                  d="M485.88,512H26.12V0h293L485.88,161.64ZM44.12,494H467.88V169.26L311.82,18H44.12Z"
                  fill="#DE6449"
                />
                <polygon
                  points="477.08 174.17 306.66 174.17 306.66 8.96 324.66 8.96 324.66 156.17 477.08 156.17 477.08 174.17"
                  fill="#DE6449"
                />
                <path
                  d="M170,182a68,68,0,1,1,68-68A68.08,68.08,0,0,1,170,182Zm0-118a50,50,0,1,0,50,50A50.06,50.06,0,0,0,170,64Z"
                  fill="#DE6449"
                />
                <path
                  d="M257.83,230h-18V209.67a35,35,0,0,0-35-35h-5.17l-6.1-10.46,11.27-6.58v-1l1.6,0,2.67-1.56,1,1.8a53.07,53.07,0,0,1,47.68,52.73Z"
                  fill="#DE6449"
                />
                <path
                  d="M104.83,230h-18V209.67a53.07,53.07,0,0,1,48.85-52.84l2.87-3.18,13.38,12-8.08,9h-4a35,35,0,0,0-35,35Z"
                  fill="#DE6449"
                />
                <rect x="87" y="261.5" width="338" height="18" fill="#DE6449" />
                <rect
                  x="87"
                  y="315.83"
                  width="338"
                  height="18"
                  fill="#DE6449"
                />
                <rect
                  x="87"
                  y="370.17"
                  width="338"
                  height="18"
                  fill="#DE6449"
                />
                <rect
                  x="87"
                  y="424.5"
                  width="176.67"
                  height="18"
                  fill="#DE6449"
                /></svg
            ></a>
            <div class="contactText">Resume</div>
          </div>
        </div>
        <div class="contactEmail">
          <h4>Or email me at:</h4>
          <span>hi@shawnwood.me</span>
        </div>
      </section>

      <section id="quote">
        <div class="wrapper">
          <h2 class="sectionHeading">Get A Quote</h2>

          <FormulateForm id="contactForm">
            <p>
              Send me a brief description of your perfect app, and I will get
              back to you within 24 hours.
            </p>
            <FormulateInput
              id="nameInput"
              placeholder="Name"
              type="text"
              name="name"
              validation="required"
            />
            <FormulateInput
              id="emailInput"
              placeholder="Email Address"
              type="email"
              name="email"
              validation="required|email"
            />
            <FormulateInput
              id="messageInput"
              placeholder="Message"
              type="textarea"
              name="message"
              validation="required"
            />
            <div id="formMessage" v-if="showMessage">{{ message }}</div>
            <button @click="submitMessage" class="mainBtn">Send</button>
          </FormulateForm>
        </div>
      </section>
    </main>
    <footer id="footer">
      <svg
        width="20"
        height="26"
        viewBox="0 0 28 33"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M22.1418 11.8165C24.0914 11.8165 26.0409 11.8165 27.9885 11.8165C25.7782 12.5191 25.5026 14.5178 24.9033 16.2207C23.2202 21.0168 21.6073 25.837 19.9537 30.6424C19.7577 31.21 19.4784 31.7499 19.2379 32.3027C19.0992 32.299 18.9605 32.2953 18.8218 32.2935C18.6276 31.8349 18.4093 31.3856 18.2428 30.916C16.7872 26.8335 15.3408 22.7492 13.8925 18.665C13.5023 17.5648 12.9992 16.5091 11.6508 16.4869C11.1403 16.4777 10.4467 16.7679 10.1655 17.1581C9.94728 17.4594 10.0564 18.3247 10.3431 18.6021C11.2809 19.5025 12.3666 20.2495 13.5836 21.2035C12.3351 24.7202 10.9942 28.5031 9.65134 32.2879C9.50337 32.2898 9.3554 32.2916 9.20743 32.2953C9.00952 31.8405 8.78571 31.3967 8.6174 30.9308C6.71598 25.6447 4.82382 20.3549 2.9261 15.0669C2.43595 13.6969 2.07713 12.2048 0 12.2695C0.0721353 12.1382 0.142421 12.0051 0.214556 11.8738C2.80958 11.8738 5.4046 11.8738 8.30481 11.8738C5.27883 13.0793 5.27513 13.0793 6.35531 16.1707C7.57236 19.6523 8.79681 23.1283 10.1674 27.0314C10.8832 25.0031 11.464 23.3575 12.0669 21.6528C11.5176 21.2793 11.0201 20.9817 10.5688 20.6248C9.23147 19.5672 8.38435 18.2711 8.72653 16.4666C8.98177 15.1205 9.91953 14.4475 11.1662 14.2441C13.0084 13.9428 14.5972 14.5159 15.6626 16.0764C16.1657 16.8142 16.4654 17.7035 16.7779 18.554C17.773 21.2609 18.733 23.9825 19.8502 27.0998C21.3743 22.5902 22.8207 18.456 24.1505 14.2867C24.5482 13.0442 24.2153 12.7983 22.1418 11.8165Z"
          fill="#FFFFEE"
        />
        <path
          d="M18.72 20.8689C18.6405 20.218 18.3908 19.5321 18.5147 18.9219C18.9586 16.7199 18.6368 15.6678 16.7354 14.4549C14.8414 13.2457 12.8678 12.1659 10.9609 10.9771C9.39979 10.0027 8.25857 8.68809 8.11615 6.7541C7.8498 3.14313 11.3104 0.369728 15.1577 1.1204C15.8883 1.26276 16.617 1.48649 17.3014 1.77677C18.3483 2.22051 19.2638 2.39986 20.0055 1.10006C20.0055 3.36685 20.0055 5.63365 20.0055 7.90044C19.9112 7.93187 19.8169 7.9633 19.7244 7.99474C19.6005 7.54914 19.4691 7.10355 19.3545 6.65611C18.6294 3.85682 16.4413 2.13731 13.7834 2.29632C12.3185 2.38322 11.1921 3.03589 10.6964 4.45218C10.197 5.87955 10.824 7.00741 12.0041 7.75438C14.1274 9.0967 16.3396 10.2985 18.4666 11.6371C21.0376 13.2568 22.0827 15.4385 21.2725 17.8255C20.8822 18.9756 20.0314 19.9703 19.3878 21.0334C19.1658 20.9798 18.942 20.9243 18.72 20.8689Z"
          fill="#FFFFEE"
        />
      </svg>

      <span>&copy; Made with 💜 by Shawn Wood</span>
    </footer>
  </div>
</template>

<script>
import axios from "axios";
export default {
  name: "App",

  data() {
    return {
      allProjects: [],
      frontend: [],
      backend: [],
      tools: [],
      showProj: 3,

      showMessage: false,
      message: "",
    };
  },

  computed: {
    limitedProjects() {
      return this.showProj
        ? this.allProjects.slice(0, this.showProj)
        : this.allProjects;
    },
  },

  created() {
    axios
      .request({
        url: `${process.env.VUE_APP_API_LINK}/projects`,
        method: "GET",
      })
      .then((res) => {
        console.log(res.data);
        this.allProjects = res.data.reverse();
      })
      .catch((err) => {
        console.log(err.response);
      });
    axios
      .request({
        url: `${process.env.VUE_APP_API_LINK}/skills/frontend`,
        method: "GET",
      })
      .then((res) => {
        this.frontend = res.data;
      })
      .catch((err) => {
        console.log(err.response);
      });
    axios
      .request({
        url: `${process.env.VUE_APP_API_LINK}/skills/backend`,
        method: "GET",
      })
      .then((res) => {
        this.backend = res.data;
      })
      .catch((err) => {
        console.log(err.response);
      });
    axios
      .request({
        url: `${process.env.VUE_APP_API_LINK}/skills/tools`,
        method: "GET",
      })
      .then((res) => {
        this.tools = res.data;
      })
      .catch((err) => {
        console.log(err.response);
      });
  },

  methods: {
    submitMessage() {
      axios
        .request({
          url: `${process.env.VUE_APP_API_LINK}/messages`,
          method: "POST",
          headers: {
            "Content-Type": "application/json",
          },
          data: {
            users_name: document.getElementById("nameInput").value,
            email_address: document.getElementById("emailInput").value,
            message: document.getElementById("messageInput").value,
          },
        })
        .then(() => {
          this.showMessage = true;
          this.message = "Your Message Was Sent!";
        })
        .catch(() => {
          this.showMessage = true;
          this.message =
            "There was an error sending your message, please try again!";
        });
    },
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
  background: $secondary;
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
.wrapper {
  max-width: 1100px;
  display: grid;
  justify-self: center;
}
.blueAcc {
  font-weight: bold;
  color: $secAcc;
}
.orangeAcc {
  font-weight: bold;
  color: $priAcc;
}
.mainBtn {
  @include mainBtn;
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
  padding-bottom: 12px;
  place-self: center;
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
  padding-bottom: 30px;

  .sectionHeading {
    color: $secondary;
    border-bottom: 3px solid $priAcc;
    margin-bottom: 18px;
  }

  #projectsContainer {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;

    .projectCard {
      margin-bottom: 40px;
      display: grid;

      .projectImage {
        max-width: 100%;
        display: block;
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
}
#skills {
  display: grid;
  margin: auto;
  color: $altAcc;
  gap: 20px;
  max-width: 1100px;

  .skillsHeading {
    border-bottom: 2px solid $priAcc;
    place-self: center;
    padding-bottom: 4px;
    font-size: 1.2rem;
    letter-spacing: 0.05rem;
  }
  .skillMainGrid,
  .contactMainGrid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    place-items: end center;
    row-gap: 26px;
    margin-bottom: 20px;
  }
  .skillSecGrid,
  .contactSecGrid {
    display: grid;
    place-items: center;
    gap: 6px;

    .skillLogo,
    .contactLogo {
      height: 40px;
    }
    .skillText,
    .contactText {
      font-size: 0.8rem;
    }
  }
}

#contact {
  display: grid;
  background: $primary;
  place-items: center;

  .sectionHeading {
    color: $secondary;
    border-bottom: 3px solid $priAcc;
    margin-bottom: 18px;
  }
  .contactMainGrid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    place-items: end center;
    max-width: 1100px;
    width: 100%;
    row-gap: 26px;
  }

  .contactSecGrid {
    display: grid;
    place-items: center;
    gap: 6px;

    .contactText {
      font-size: 0.8rem;
      color: $secondary;
    }
  }
  .contactEmail {
    place-self: center;
    margin: 20px 0;
    display: grid;
    gap: 16px;
    place-items: center;
    h4 {
      color: $secondary;
      font-size: 0.85rem;
    }
    span {
      color: $secondary;
      font-size: 0.8rem;
    }
  }
}

#quote {
  display: grid;
  color: $altAcc;
  padding-bottom: 18px;
  gap: 20px;
  place-items: center;
}
li.formulate-input-error {
  color: $errorTx;
  list-style-type: none;
}
#contactForm {
  width: 100%;
  display: grid;
  padding: 20px 20px 0 20px;
  gap: 20px;
}
#nameInput,
#emailInput,
#messageInput {
  font-size: 1.3rem;
  width: 100%;
  padding-left: 4px;
  border: 2px solid $altAcc;
  border-radius: 3px;

  &:focus {
    border: 2px solid $priAcc;
    border-radius: 3px;
    outline: none;
  }
}
#messageInput {
  height: 80px;
  font-size: 1rem;
}

#formMessage {
  justify-self: center;
}

#footer {
  background: $primary;
  display: grid;
  height: 30px;
  place-items: center;
  position: relative;

  svg {
    position: absolute;
    left: 4px;
    top: 2px;
    margin: 0;
  }
  span {
    color: $secondary;
    font-size: 0.9rem;
    font-weight: 200;
  }
}
</style>
