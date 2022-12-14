<template>
    <div>
        <h1 class="text-center">Contact</h1>
        <form name="contact-form" action="https://formspree.io/f/xwkzrbbv" method="POST" class="mt-5">
<div class="row">
    <div class="col-6">
      <label for="name" class="form-label">First name:</label>
      <input type="text" name="name" class="form-control" placeholder="First name" v-model="firstname" aria-label="First name">
    </div>
    <div class="col-6">
        <label for="name" class="form-label">Last name:</label>
      <input type="text" name="name" class="form-control" placeholder="Last name" v-model="surname" aria-label="Last name">
    </div>
    <div class="col-6">
        <label for="number" class="form-label">Phone number:</label>
        <input type="number" name="number" class="form-control" placeholder="Phone number" v-model="number" aria-label="Phone number">
      </div>
      <div class="col-6">
        <label for="email" class="form-label">Email address:</label>
        <input type="email" name="email" class="form-control" id="exampleFormControlInput1" v-model="email" placeholder="name@example.com">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message:</label>
        <textarea class="form-control" name="message" id="exampleFormControlTextarea1" v-model="message" placeholder="Write something..." rows="3"></textarea>
      </div>
      <button type="submit" class="btn btn-dark" v-on:click.prevent="submit">Submit</button>
  </div>
</form>
    </div>
</template>
<script>
export default {
  name: 'Contact',
  methods: {
    submit(){
      alert(`${this.firstname} with the surname ${this.surname} with the number ${this.number} with the email ${this.email} with the message ${this.message}`)
    }
  },
}
// methods: {
//            thanks: function(event){
//                  event.preventDefault();
//                  alert('Hello there');
//           }
//       }
// } 
</script>
<style>

</style>
