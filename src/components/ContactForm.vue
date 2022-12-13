<template>
    <div>
        <h1 class="text-center">Contact</h1>
        <form name="contact-form" action="https://formspree.io/f/xwkzrbbv" method="POST">
<div class="row">
    <div class="col-6">
      <label for="name" class="form-label">First name:</label>
      <input type="text" name="name" class="form-control" placeholder="First name" aria-label="First name">
    </div>
    <div class="col-6">
        <label for="name" class="form-label">Last name:</label>
      <input type="text" name="name" class="form-control" placeholder="Last name" aria-label="Last name">
    </div>
    <div class="col-6">
        <label for="number" class="form-label">Phone number:</label>
        <input type="number" name="number" class="form-control" placeholder="Phone number" aria-label="Phone number">
      </div>
      <div class="col-6">
        <label for="email" class="form-label">Email address:</label>
        <input type="email" name="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message:</label>
        <textarea class="form-control" name="message" id="exampleFormControlTextarea1" placeholder="Write something..." rows="3"></textarea>
      </div>
      <button type="submit" class="btn btn-dark">Submit</button>
  </div>
</form>
    </div>
</template>
<script>
export default {
  name: 'Contact',
}
</script>
<style>
    
</style>