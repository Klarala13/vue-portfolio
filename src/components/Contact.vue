<template>
  <div id="contact" class="container contact-form">
    <h1>Contact</h1>
    <hr />
    <form
      class="form text-center m-3 p-3"
      action="https://formspree.io/claradevelopment@gmail.com"
      method="POST"
    >
      <h5 class="about-header contact-title">Contact Me</h5>
      <fieldset>
        <input
          placeholder="Name"
          type="text"
          name="name"
          tabindex="1"
          required
        />
      </fieldset>
      <fieldset>
        <input
          placeholder="Email Address"
          type="email"
          name="name"
          tabindex="2"
          required
        />
      </fieldset>
      <fieldset>
        <textarea
          placeholder="Type your Message Here...."
          name="name"
          tabindex="5"
          required
        ></textarea>
      </fieldset>
      <fieldset>
        <button
          class="btn btn-outline-dark"
          id="contact-submit"
          data-submit="...Sending"
        >
          Submit
        </button>
      </fieldset>
    </form>
  </div>
</template>
