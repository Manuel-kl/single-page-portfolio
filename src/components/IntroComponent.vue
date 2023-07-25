<template>
  <div class="intro-wrapper">
    <header>
      <div class="name">
        <a href="#" target="_blank">adamkeyes</a>
      </div>
      <div class="social-links">
        <a href="#">
          <font-awesome-icon :icon="['fab', 'github']" />
        </a>
        <a href="#" class="front-end-mentor" target="_blank">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 26 23"
            width="26"
            height="23"
            aria-hidden="true"
          >
            <path
              fill="#FFF"
              d="M13.084.23a.751.751 0 0 0-.736.75v14.267a.75.75 0 1 0 1.5 0V.98a.75.75 0 0 0-.763-.75ZM24.44 4.504a.752.752 0 0 0-.284.064l-6.44 2.875a.752.752 0 0 0 0 1.37l6.44 2.884a.75.75 0 0 0 .612-1.369L19.861 8.13l4.907-2.191a.753.753 0 0 0 .38-.99.752.752 0 0 0-.708-.444ZM1.371 9.663a.752.752 0 0 0-.74.938C2.41 17.447 8.603 22.23 15.685 22.23a.75.75 0 1 0 0-1.501A14.053 14.053 0 0 1 2.083 10.225a.75.75 0 0 0-.712-.561v-.001Z"
            />
          </svg>
        </a>
        <a href="#">
          <font-awesome-icon :icon="['fab', 'linkedin']" />
        </a>
        <a href="#">
          <font-awesome-icon :icon="['fab', 'twitter']" />
        </a>
      </div>
    </header>

    <div class="intro">
      <h1>
        Nice to meet you! <br />
        I'm Adam Keyes.
      </h1>
      <p>
        Based in the UK, I'm a front-end developer passionate about building
        accessible web apps that users love.
      </p>
      <h2>CONTACT ME</h2>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  props: {},
  data() {
    return {};
  },
  created() {},
  methods: {},
  mounted() {},
};
</script>
<style scoped lang="css">
.intro-wrapper {
  display: flex;
  flex-direction: column;
  background-color: var(--main-bg-color);
  margin: 0 7rem;
  height: 100vh;
  border-bottom: 1px solid var(--white);
}
.intro-wrapper header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 0;
}
.intro-wrapper header .name a {
  font-size: var(--m-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  text-decoration: none;
}
.intro-wrapper header .social-links {
  display: flex;
  flex-direction: row;
  gap: 2rem;
}
.intro-wrapper header .social-links a,
.intro-wrapper header .social-links .front-end-mentor svg path {
  color: var(--white);
  text-decoration: none;
  font-size: var(--m-font);
  font-family: var(--font-family-main);
}
.intro-wrapper header .social-links a:hover,
.intro-wrapper header .social-links .front-end-mentor:hover svg path {
  color: var(--green-color);
  fill: var(--green-color);
}
.intro-wrapper .intro {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  padding: 5rem 0;
}
.intro-wrapper .intro h1 {
  font-size: var(--xl-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 700;
  letter-spacing: var(--xl-char-spacing);
  line-height: var(--xl-line-height);
}
.intro-wrapper .intro p {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--light-gray);
  font-weight: 400;
  line-height: var(--s-line-height);
  max-width: 500px;
}
.intro-wrapper .intro h2 {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  line-height: var(--s-line-height);
  border-bottom: 0.2rem solid var(--green-color);
  width: fit-content;
  padding-bottom: 0.5rem;
}
</style>