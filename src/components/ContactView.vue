<template>
    <div class="contact">
        <h1 class="text-center">Contact Us</h1>
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
      <button type="submit" class="btn btn-primary">Submit</button>
  </div>
</form>
    <footer>
    <div class="container">
    <div class="row">
      <div class="col-4">
    <p>Copyright &copy; 2022</p>
  </div>
  <div class="col-4">
    <a id="email" class="text-dark" href="mailto:info@volkano.com">info@volkano.com</a>
  </div>
  <div class="col-4 lead">
    <a id="socials" href="https://www.facebook.com/VolkanoRSA/" class="fa-brands fa-facebook text-dark"></a>
    <a id="socials" href="https://twitter.com/volkanorsa" class="fa-brands fa-twitter text-dark"></a>
    <a id="socials" href="https://www.instagram.com/volkanorsa/" class="fa-brands fa-instagram text-dark"></a>
    <a id="socials" href="https://www.youtube.com/channel/UCoed-TO2TSnlKOcMU2zjBsA" class="fa-brands fa-youtube text-dark"></a>
  </div>
  </div>
    </div>
    </footer>
    </div>
</template>
<script>

</script>
<style>
body {
    background-color: aqua;
}

#socials, #email {
    text-decoration: none;
    padding: 6px
}
</style>