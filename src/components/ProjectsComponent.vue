<template>
  <div class="projects-wrapper">
    <div class="header">
      <h1>Projects</h1>
      <h3>CONTACT ME</h3>
    </div>
    <div class="projects">
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-1-large.webp"
          alt="project-1-thumbnail"
        />
        <div class="project-liniks">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>DESIGN PORTFOLIO</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
        </div>
      </div>
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-2-large.webp"
          alt="project-2-thumbnail"
        />
        <div class="project-liniks">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>E-LEARNING LANDING PAGE</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
        </div>
      </div>
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-3-large.webp"
          alt="project-3-thumbnail"
        />
        <div class="project-liniks">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>TODO WEB APP</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
          <p>JAVASCRIPT</p>
        </div>
      </div>
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-4-large.webp"
          alt="project-4-thumbnail"
        />
        <div class="project-liniks">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>ENTERTAINMENT WEB APP</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
          <p>JAVASCRIPT</p>
        </div>
      </div>
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-5-large.webp"
          alt="project-5-thumbnail"
        />
        <div class="project-links">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>MEMORY GAME</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
          <p>JAVASCRIPT</p>
        </div>
      </div>
      <div class="project">
        <img
          src="../assets/images/thumbnail-project-6-large.webp"
          alt="project-6-thumbnail"
        />
        <div class="project-liniks">
          <a href="#">VIEW PROJECT </a>
          <a href="#">VIEW CODE</a>
        </div>
        <h3>ART GALLERY SHOWCASE</h3>
        <div class="langs">
          <p>HTML</p>
          <p>CSS</p>
          <p>JAVASCRIPT</p>
        </div>
      </div>
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

<style lang='css' scoped>
.projects-wrapper {
  display: flex;
  flex-direction: column;
  background-color: var(--main-bg-color);
  padding: 3rem var(--padding-x);
  width: auto;
}
.projects-wrapper .header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 0;
}
.projects-wrapper .header h1 {
  font-size: var(--xl-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 700;
  letter-spacing: var(--xl-char-spacing);
  line-height: var(--xl-line-height);
}
.projects-wrapper .header h3 {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  border-bottom: 2px solid var(--green-color);
  padding-bottom: 0.5rem;
}
.projects-wrapper .projects {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 2rem;
}
.projects-wrapper .projects .project {
  display: flex;
  padding: 1rem 0 5rem 0;
  flex-direction: column;
  width: fit-content;
  flex: 1 1 30rem;
}
.projects-wrapper .projects .project img {
  width: 100%;
  object-fit: cover;
}
.projects-wrapper .projects .project .project-links {
  display: flex;
  flex-direction: column;
  justify-content: center;
  position: absolute;
  padding: 1rem 0;
  gap: 2rem;
  background: none;
}
.projects-wrapper .projects .project .project-links a {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  letter-spacing: var(--s-char-spacing);
  line-height: var(--s-line-height);
  padding: 0.5rem 0;
  background: none;
  margin: auto;
  flex: 1;
  text-decoration: none;
  border-bottom: 2px solid var(--green-color);
}
.projects-wrapper .projects .project h3 {
  font-size: var(--m-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  padding: 1rem 0;
}
.projects-wrapper .projects .project .langs {
  display: flex;
  flex-direction: row;
  gap: 1rem;
}
.projects-wrapper .projects .project p {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--light-gray);
  font-weight: 500;
  letter-spacing: var(--s-char-spacing);
  line-height: var(--s-line-height);
}
</style>