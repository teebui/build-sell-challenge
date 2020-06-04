<template>
  <div  >
    <div><nuxt-link to="/">Back to the start</nuxt-link></div>
    <h1>
      Let’s create together the tailor-made support you need
    </h1>
    
    <div>
      <form name="contact" action="" method="post">
        <input class="form-field" name="first-name" id="first-name" value="First Name" />
        <input class="form-field" name="last-name" id="last-name" value="Last Name" /><br />
        <input class="form-field" name="job-title" id="job-title" value="Job Title" /><br />
        <input class="form-field" name="company" id="company" value="Company" /><br />
        <input class="form-field" name="email" id="email" value="name@example.com" /><br />
        <textarea class="form-field" name="message" id="message">
          Tell us how we can help you
        </textarea>
        <input type="checkbox" id="informed" value="Please keep me informed about Wemanity services, offerings and" />
        <br />
        <input class="form-button" type="submit" value="Send" />
      </form>
    </div>
  </div>
</template>