<template>
  <div class="contacts" style="color: aliceblue">
    <div class="container">
      <p class="display-2">Contact Form</p>

      <form name="contact" netlify>
            <label for="email">Email</label><br />
            <input type="email" name="email" placeholder="alamat email" />
            <br />
            <label for="message">Pesan</label><br />
            <textarea name="message" placeholder="Tulis pesan anda..." rows="4" cols="80"></textarea>
            <br />
            <br />
            <input type="submit" value="Kirim" />
        </form>


    </div>
  </div>
</template>
