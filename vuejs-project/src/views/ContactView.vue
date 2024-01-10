<template>
    <div class="headings">
      <h2 class="display-3">Reach Me</h2>
    </div>
    <div id="form1">
        <form action="https://formspree.io/f/xnqkldqw" method="post">
          <div class="mb-3 w-25">
            <label for="#FirstName" class="form-label">Name</label>
            <input
              type="text"
              class="form-control"
              name="Fullname"
              id="FirstName"
              aria-describedby="#Fullname"
              placeholder="enter name here"
              required
            />
          </div>
          <div class="mb-3 w-25">
            <label for="#Surname" class="form-label">Surname</label>
            <input
              type="text"
              class="form-control"
              name="Surname"
              required
              id="Surname"
              aria-describedby="#Surname"
              placeholder="enter surname here"
            />
          </div>
          <div class="mb-3">
            <label for="#Email" class="form-label">Email address</label>
            <input
              type="Email"
              class="form-control"
              name="Email"
              required
              id="Email"
              aria-describedby="#Email"
              placeholder="name@example.com
              "
            />
          </div>
          <div class="mb-3">
            <label for="#Message" class="form-label">Message</label>
            <textarea
              class="form-control"
              id="Message"
              rows="3"
              placeholder="Message"
            ></textarea>
          </div>
          <button type="submit" class="btn btn-dark" target="_blank">
            Submit
          </button>
        </form>
      </div>
  </template>
  
  