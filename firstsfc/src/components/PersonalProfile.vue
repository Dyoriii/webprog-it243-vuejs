<template>
  <div class="container">

    <!-- Decorative triangles -->
    <div class="triangle-decoration triangle-1"></div>
    <div class="triangle-decoration triangle-2"></div>

    <!-- LEFT: PROFILE -->
    <div class="profile">
      <h1>My Profile</h1>

      <div class="profile-img">
        <img
          src="https://i.pinimg.com/736x/c0/8f/0c/c08f0cfd48cfc651d61daec38e8c74ea.jpg"
          alt="Profile Image"
        />
      </div>

      <h2>Jhorie M. Ranario</h2>
      <p><a href="#">View photos</a></p>

      <div class="separator-container">
        <img
          src="https://i.pinimg.com/1200x/2f/3e/f0/2f3ef0eaa0a87a8e291f62e28c8a89d7.jpg"
          alt="separator"
          class="separator"
        />
      </div>

      <h3>About Me</h3>
      <blockquote>
        “I carry my past, but I don't live there.”
      </blockquote>
    </div>

    <!-- CENTER / RIGHT: DETAILS -->
    <div class="details">

      <section>
        <h3>Education / Achievement</h3>
        <p>San Diego Elementary School – Grade 1 – 6</p>
        <p>Ramon Magsaysay (Cubao) High School – Grade 7 – 12</p>
        <p>Asia Pacific College – Current</p>
      </section>

      <section>
        <h3>Course</h3>
        <p>BSIT</p>
      </section>

      <section>
        <h3>IT Experience</h3>
        <p>Outsystems, MS Apps, Java Programming, Python</p>
      </section>

      <div class="likes-hobbies">
        <div class="likes">
          <h4>Likes</h4>
          <ul class="triangle-list">
            <li>Eminence and Black Colors</li>
            <li>Reading Windbreaker</li>
          </ul>
        </div>

        <div class="hobbies">
          <h4>Hobbies</h4>
          <ul class="triangle-list">
            <li>Playing Instruments</li>
            <li>Playing Games</li>
            <li>Sleeping</li>
            <li>Cleaning</li>
          </ul>
        </div>
      </div>

      <div class="goals">
        <strong>Goals:</strong> To graduate and fulfill my dream of traveling.
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: "ProfileTemplate"
}
</script>

<style></style>
