<template>
  <div class="contact-wrapper">
    <div class="left">
      <h1>Contact</h1>
      <p>
        I would love to hear about your project and how I could help. Please
        fill in the form, and I'll get back to you as s[n as possible.
      </p>
    </div>
    <div class="right">
      <form @submit.prevent="">
        <div class="form-group">
          <label for="name">NAME</label>
          <input type="text" id="name" placeholder="NAME" />
        </div>
        <div class="form-group">
          <label for="email">EMAIL</label>
          <input type="email" id="email" placeholder="EMAIL" />
        </div>
        <div class="form-group">
          <label for="message">MESSAGE</label>
          <textarea id="message" placeholder="MESSAGE"></textarea>
        </div>
        <button type="submit">SEND MESSAGE</button>
      </form>
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
.contact-wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 0 7rem;
  border-bottom: 1px solid var(--white);
}
.contact-wrapper .left {
  display: flex;
  background-color: var(--dark-gray);
  flex-direction: column;
  flex: 1 1 40rem;
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
}
.contact-wrapper .left p {
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  background-color: var(--dark-gray);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  padding: 1rem 0;
}
.contact-wrapper .right {
  display: flex;
  background-color: var(--dark-gray);
  flex-direction: column;
  flex: 1 1 40rem;
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
.contact-wrapper .right form .form-group label {
  font-size: var(--s-font);
  background-color: var(--dark-gray);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
}
.contact-wrapper .right form .form-group input,
.contact-wrapper .right form .form-group textarea {
  background-color: var(--dark-gray);
  border: none;
  border-radius: 0.5rem;
  padding: 1rem;
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
}
.contact-wrapper .right form .form-group input:focus,
.contact-wrapper .right form .form-group textarea:focus {
  outline: none;
}

.contact-wrapper .right form button {
  background-color: var(--green-color);
  border: none;
  border-radius: 0.5rem;
  padding: 1rem;
  font-size: var(--s-font);
  font-family: var(--font-family-main);
  color: var(--white);
  font-weight: 500;
  letter-spacing: var(--m-char-spacing);
  line-height: var(--m-line-height);
  cursor: pointer;
}
.contact-wrapper .right form button:hover {
  background-color: var(--dark-gray);
}

.contact-wrapper .right form button:focus {
  outline: none;
}
</style>