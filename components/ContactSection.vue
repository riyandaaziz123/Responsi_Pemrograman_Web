<template>
  <section class="contact">
    <div id="contact">
        <h2>Contact Me</h2>
        <div id="contact-form">
            <form method="POST" action="https://formspree.io/email@email.com">
                <input type="hidden" name="_subject" value="Contact request from personal website" />
                <input type="email" name="_replyto" placeholder="Your email" required>
                <textarea name="message" placeholder="Your message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
        <!-- End #contact-form -->
    </div>
    <!-- End #contact -->
    <div >
      <h2 class="footer">Contact Me</h2>
      <p class="gmail">Email: riyandaazizi@example.com</p>
    </div>
    
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
.contact {
  padding: 50px 0;
}

#contact {
    padding: 50px 15px;
    background: #f5f5f5;
    text-align: center;

    h2 {
        margin: 0 0 15px 0;
        color: #000000;
        font-weight: 500;
    }
}

#contact-form {
    max-width: 500px;
    margin: 0 auto;

    input, textarea {
        display: block;
        width: 100%;
        padding: 10px;
        border-radius: 4px;
        border: none;
        margin-bottom: 10px;
        background: darken($base-color, 15%);
        color: #000000;
        @include transition();
        @include placeholder {
            color: #fff;
        }

        &:focus {
            outline: none;
            background: darken($base-color, 25%);
        }
    }

    textarea {
        height: 150px;
        resize: none;
    }

    button {
        display: block;
        width: 100%;
        background: #fff;
        border-radius: 4px;
        padding: 5px 10px;
        border: none;
        color: $base-color;
        font-weight: 700;
        box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
        @include transition();

        &:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
        }
    }
}

.footer{
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center; 
  height: 80px;
}
.gmail {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 10px; /* Atur sesuai kebutuhan Anda */
}
</style>
