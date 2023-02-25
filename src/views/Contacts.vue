<template>
  <div class="contacts" style="color:aliceblue;">
    <div class="container">
      <p class="display-2">Contact Form</p>
      <form name="contact" method="POST"  netlify>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Nama</label>
          <input
          placeholder="Insert Your Name"
            name="nama"
            type="name"
            class="form-control"
            id="name"
            aria-describedby="namehelp"
          />
          <label for="exampleInputEmail1" class="form-label mt-2"
            >Email address</label
          >
          <input
          placeholder="Insert Your Email..."
            name="email"
            type="email"
            class="form-control"
            id="email"
            aria-describedby="emailHelp"
          />
          <div id="emailHelp" class="form-text">
            We'll never share your email with anyone else.
          </div>
        </div>
        <div class="mb-3">
          <label for="messages" class="form-label">Messages</label>
          <textarea
          placeholder="Enter Message..."
            type="text"
            class="form-control"
            id="messages"
          />
        </div>
        <div class="mb-3 form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1" />
          <label class="form-check-label" for="exampleCheck1"
            >i Agree this message will be read into</label
          >
        </div>
        <input class="btn btn-outline-primary" type="submit" value="Kirim" />
      </form>
    </div>
  </div>
</template>
