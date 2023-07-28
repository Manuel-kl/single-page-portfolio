<template>
  <div class="contact">
    <div class="contact-wrapper">
      <div class="left">
        <h1>Contact</h1>
        <p>
          I would love to hear about your project and how I could help. Please
          fill in the form, and I'll get back to you as soon as possible.
        </p>
      </div>
      <div class="right">
        <form @submit.prevent="">
          <div class="form-group">
            <input type="text" id="name" placeholder="NAME" />
          </div>
          <div class="form-group">
            <input type="email" id="email" placeholder="EMAIL" />
          </div>
          <div class="form-group">
            <textarea id="message" placeholder="MESSAGE"></textarea>
          </div>
          <button type="submit">SEND MESSAGE</button>
        </form>
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
.contact {
  padding: 0 var(--padding-x);
  background-color: var(--dark-gray);
  width: auto;
}
.contact-wrapper {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  background-color: var(--dark-gray);
  border-bottom: 1px solid var(--white);
  grid-column-gap: 15rem;
  padding: 3rem 0;
}
.contact-wrapper .left {
  display: flex;
  background-color: var(--dark-gray);
  flex-direction: column;
  padding: 2rem 0;
}
.contact-wrapper .left h1 {
  font-size: var(--xl-font);
  font-family: var(--font-family-main);
  background-color: var(--dark-gray);
  color: var(--white);
  font-weight: 700;
  letter-spacing: var(--xl-char-spacing);
  line-height: var(--xl-line-height);
  padding-bottom: 2rem;
}
.contact-wrapper .left p {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  background-color: var(--dark-gray);
  color: var(--light-gray);
  font-weight: 500;
  line-height: var(--s-line-height);
  padding: 1rem 0;
}
.contact-wrapper .right {
  display: flex;
  background-color: var(--dark-gray);
  flex-direction: column;
  padding: 2rem 0;
}
.contact-wrapper .right form {
  display: flex;
  flex-direction: column;
  background-color: var(--dark-gray);
  gap: 1rem;
}
.contact-wrapper .right form .form-group {
  display: flex;
  background-color: var(--dark-gray);
  flex-direction: column;
  gap: 0.5rem;
}

.contact-wrapper .right form .form-group input,
.contact-wrapper .right form .form-group textarea {
  background-color: var(--dark-gray);
  border: none;
  padding: 1rem 1.5rem;
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  border-bottom: 1px solid var(--white);
}
.contact-wrapper .right form .form-group input:focus,
.contact-wrapper .right form .form-group textarea:focus {
  outline: none;
}
.contact-wrapper .right form .form-group textarea {
  resize: none;
  height: 7rem;
}

.contact-wrapper .right form button {
  background-color: var(--dark-gray);
  border: none;
  display: flex;
  border-bottom: 2px solid var(--green-color);
  padding: 0.5rem;
  margin: auto 0 1rem auto;
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
}
</style>